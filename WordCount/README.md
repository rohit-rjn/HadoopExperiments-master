Word Count
===========
Word Count implementation in Hadoop's MapReduce.

The jar file contains all the classes. To run the program using the jar file:

$javac MyWordCount.java

$hadoop jar mywc.jar MyWordCount test.txt output

To view the output of the program:

$hadoop dfs -cat output/part-r-00000

To compile the program, you need to have the hadoop-core-1.x.x.jar in your classpath. The test.txt should be present in your Hadoop DFS directory.
