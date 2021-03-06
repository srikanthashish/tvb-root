.. _benchmark_tvb_141:


**********************
Benchmarks - TVB 1.4.1
**********************


+------------+-----------------------------------------------------------------+
|                               System Info                                    |
+============+=================================================================+
|OS          | OS X Yosemite  10.10.5                                          |
+------------+-----------------------------------------------------------------+
|Memory      | 16GB DDR3  @1600MHz                                             |
+------------+-----------------------------------------------------------------+
|Processor   | 4 x 2.5 GHz Intel Core i7                                       |
+------------+-----------------------------------------------------------------+
|TVB version | 1.4.1 #7589 - Mac x64                                           |
+------------+-----------------------------------------------------------------+


A standardized set of benchmarks follows. All unspecified parameters have the default values.
For parameters that influence running times significantly at least two values were used.
The local model parameters are usually irrelevant for the purpose of benchmarking.

+--------------------+------------------------------------+
| Case A                                                  |
+====================+====================================+
|Model               | Generic2dOscillator                |
+--------------------+------------------------------------+
|Coupling            | Linear                             |
+--------------------+------------------------------------+
|Dimension           | 2 state variables                  |
+--------------------+------------------------------------+
|Integration method  | HeunDeterministic                  |
+--------------------+------------------------------------+
|Simulation Length   | 1000 ms                            |
+--------------------+------------------------------------+


+------------------------+--------+-------+-----------+---------+-----------+
|      Results                                                              |
+------------------------+--------+-------+-----------+---------+-----------+
|        Model           | Sim.   | Nodes |Conduction | time    | Execution |
|                        | Length |       |speed      | step    | time      |
+------------------------+--------+-------+-----------+---------+-----------+
|                        |    (ms)|       |    (mm/ms)|     (ms)| min:sec   |
+========================+========+=======+===========+=========+===========+
|    Generic2dOscillator |   1000 |    68 |      30.0 |     0.1 |   00:05.1 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    68 |       3.0 |     0.1 |   00:04.4 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    68 |      30.0 |    0.05 |   00:09.0 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    68 |       3.0 |    0.05 |   00:08.9 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    96 |      30.0 |     0.1 |   00:05.4 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    96 |       3.0 |     0.1 |   00:05.9 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    96 |      30.0 |    0.05 |   00:10.3 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |    96 |       3.0 |    0.05 |   00:11.0 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |   192 |      30.0 |     0.1 |   00:08.4 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |   192 |       3.0 |     0.1 |   00:08.8 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |   192 |      30.0 |    0.05 |   00:16.7 |
+------------------------+--------+-------+-----------+---------+-----------+
|    Generic2dOscillator |   1000 |   192 |       3.0 |    0.05 |   00:17.9 |
+------------------------+--------+-------+-----------+---------+-----------+


+--------------------+------------------------------------+
| Case B                                                  |
+====================+====================================+
|Model               | Epileptor                          |
+--------------------+------------------------------------+
|Coupling            | Linear                             |
+--------------------+------------------------------------+
|Dimension           | 6 state variables                  |
+--------------------+------------------------------------+
|Integration method  | HeunDeterministic                  |
+--------------------+------------------------------------+
|Simulation Length   | 1000 ms                            |
+--------------------+------------------------------------+


+------------------------+--------+-------+-----------+---------+-----------+
|      Results                                                              |
+------------------------+--------+-------+-----------+---------+-----------+
|        Model           | Sim.   | Nodes |Conduction | time    | Execution |
|                        | Length |       |speed      | step    | time      |
+------------------------+--------+-------+-----------+---------+-----------+
|                        |    (ms)|       |    (mm/ms)|     (ms)| min:sec   |
+========================+========+=======+===========+=========+===========+
|              Epileptor |   1000 |    68 |      30.0 |     0.1 |   00:06.6 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    68 |       3.0 |     0.1 |   00:06.8 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    68 |      30.0 |    0.05 |   00:12.4 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    68 |       3.0 |    0.05 |   00:12.7 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    96 |      30.0 |     0.1 |   00:07.5 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    96 |       3.0 |     0.1 |   00:07.5 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    96 |      30.0 |    0.05 |   00:14.0 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |    96 |       3.0 |    0.05 |   00:16.2 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |   192 |      30.0 |     0.1 |   00:11.8 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |   192 |       3.0 |     0.1 |   00:12.3 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |   192 |      30.0 |    0.05 |   00:23.0 |
+------------------------+--------+-------+-----------+---------+-----------+
|              Epileptor |   1000 |   192 |       3.0 |    0.05 |   00:25.5 |
+------------------------+--------+-------+-----------+---------+-----------+

+--------------------+------------------------------------+
| Case C                                                  |
+====================+====================================+
|Model               | LarterBreakspear                   |
+--------------------+------------------------------------+
|Coupling            | HyperbolicTangent                  |
+--------------------+------------------------------------+
|Dimension           | 3 state variables                  |
+--------------------+------------------------------------+
|Integration method  | HeunDeterministic                  |
+--------------------+------------------------------------+
|Simulation Length   | 10 sec                             |
+--------------------+------------------------------------+
|Conduction speed    | 10 mm/ms                           |
+--------------------+------------------------------------+

+------------------------+--------+-------+-----------+---------+-----------+
|      Results                                                              |
+------------------------+--------+-------+-----------+---------+-----------+
|        Model           | Sim.   | Nodes |Conduction | time    | Execution |
|                        | Length |       |speed      | step    | time      |
+------------------------+--------+-------+-----------+---------+-----------+
|                        |    (ms)|       |    (mm/ms)|     (ms)| min:sec   |
+========================+========+=======+===========+=========+===========+
|       LarterBreakspear |  10000 |    68 |      10.0 |     0.2 |   00:37.6 |
+------------------------+--------+-------+-----------+---------+-----------+
|       LarterBreakspear |  10000 |    68 |      10.0 |     0.1 |   01:08.8 |
+------------------------+--------+-------+-----------+---------+-----------+
|       LarterBreakspear |  10000 |    96 |      10.0 |     0.2 |   00:39.0 |
+------------------------+--------+-------+-----------+---------+-----------+
|       LarterBreakspear |  10000 |    96 |      10.0 |     0.1 |   01:29.8 |
+------------------------+--------+-------+-----------+---------+-----------+
|       LarterBreakspear |  10000 |   192 |      10.0 |     0.2 |   01:22.4 |
+------------------------+--------+-------+-----------+---------+-----------+
|       LarterBreakspear |  10000 |   192 |      10.0 |     0.1 |   02:25.4 |
+------------------------+--------+-------+-----------+---------+-----------+
