#!/bin/bash
#Recursive factorial function
factorial()
{
local=$1
if((local<=2)); then
echo $local
else
f=$((local -1))
#Recursive call
f=$(factorial $f)
f=$((f*local))
echo $f
fi
}
#main script
read -p "Enter the number:" n
if((n==0)); then
echo 1
else
#calling factorial function
factorial $n
fi
