qlobe
=====

This quine was presented at RubyConf by **Yusuke Endoh**.<br/>
The globe turns 45 degrees when executed and will come around eight times.
You can make it any-degree turn by giving an integer as an command-line argument.

To run this code, just add this line to your terminal:
`clear; for ((;;)); do for i in {1..360}; do tput cup 0 0; ruby qlobe.rb $i; sleep 0.1; done; done;`
