This folder contains two sub folders "Executable" and "Source Code".

"Executable" folder contains jar file which illustrates executable file of java.

It only can be run by installing java runtime JRE 1.5 or more. This program can be installed from oracle.com site. After installing this program you can run the program by typing the following command in the command line prompt "java -jar hhc.jar". If an error arrise while executing this command, if the error claims that no "java" command is undefined, you have to include installed JRE "bin" folder path in "PATH" environment variable. The second case an error could be arrised if hhc.jar file is not in the same execution path of the prompt command, in this case you can handle that by entering full "absolute" path of hhc.jar.

After running this file a dialog containing 4 options will be shown asking for the choice you want to do.

Choice 1) Experiment 1 (Execution Time of Algorithms A and B for constant dimension & variable load size).

In this case, a dialog asking for HHC dimension will arrise so you have to enter dimension size. 5 executions of Algorithm A and B will be executed with max load of 10, 100, 1000, 10000, and 100000 on the dimension you have entered. Note that output will be tabular containing three columns "Load Size", "Algorithm A", "Algorithm B".

Load Size: represents max load size of the execution.
Algorithm A: represents execution time in milliseconds of Algorithm A.
Algorithm B: represents execution time in milliseconds of Algorithm B.

Choice 2)Experiment 2 (Execution Time of Algorithms A and B for constant load size & variable dimensions).

In this case, a dialog asking for Max load size will arrise so you have to enter maximum load size per node. 5 executions of Algorithm A and B will be executed with HHC dimension of 1, 2, 3, 4, and 5 on the load size you have entered. Note that output will be tabular containing three columns "Dimension", "Algorithm A", "Algorithm B".

Dimension: represents HHC dimension of the execution.
Algorithm A: represents execution time in milliseconds of Algorithm A.
Algorithm B: represents execution time in milliseconds of Algorithm B.

Choice 3)Experiment 3 (Speed of Algorithms A and B for variable dimensions).

In this case, a dialog asking for Max load size will arrise so you have to enter maximum load size per node. 8 executions of Algorithm A and B will be executed with HHC dimension of 1, 2, 3, 4, 5, 6, 7 and 8 on the load size you have entered. Note that output will be tabular containing three columns "Dimension", "Algorithm A", "Algorithm B".

Dimension: represents HHC dimension of the execution.
Algorithm A: Speed of Algorithm A bit/second.
Algorithm B: Speed of Algorithm B bit/second.

Otherwise) If none of the valid values 1,2, and 3 is entered the program will be terminated.


"Source Code" folder contains source files as JDeveloper 11g workspace.

edu.ju.os.Main class is the main class to start from which contains static main method. Implementation of Algorithm A is done in class edu.ju.os.algorithm1.LBProcessor.This is thread class so that run method is overrided and all the implementation is done inside this method.

Implementation of Algorithm B is done in class edu.ju.os.algorithm2.LBProcessor.This is thread class so that run method is overrided and all the implementation is done inside this method.
