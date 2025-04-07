# tcl
puts "Hello, World!"
set k1 [list c1 c2 c3 c4 c5]
set k2 [list c3 c6 c5 c2 c7]
set k3 {}
foreach elem $k1 {
  if {$elem in $k2} {
    lappend k3 $elem
  }
}
puts "$k3"
