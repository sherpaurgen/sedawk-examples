# sedawk-examples
sed awk practical examples

#remove leading tabs and spaces
vi attendence
2015-11-08 10:07 16:32pm
2015-11-09 09:45:30
    spaces in side
			tabs outsid
	tabssd d sf
    spacedsf dsfdsf
===solution below == ===

# cat attendence | sed 's/^[ \t]\+//g'

2015-11-08 10:07 16:32pm
2015-11-09 09:45:30
spaces in side
tabs outsid
tabssd d sf
spacedsf dsfdsf

