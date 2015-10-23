This is a review for Group 12 from Group 10

Your group provides detailed explanations of the work completed so far. The reasoning on why the compiler failed to vectorize many of the loops is particularly well described. 

Your analysis of potential improvements is overall excellent. You discuss the key bottlenecks discovered using VTune amplifier, and how they can be optimized, especially from blocking. We would have liked to see timing comparisons between the provided code and your optimizations.

We noticed you were able to naively optimize a few loops in the C++ code and were able to achieve some performance improvements for low thread counts. We found the Strong Scaling plot sufficient for conveying these improvements. However, we recommend that you plot scaling efficiency as a function of thread count instead of time per thread. This would give a clearer quantification of the improvements. We also suggest that you perform a weak scaling analysis.

As your report already mentions, we also suspect that you will gain the greatest performance by implementing domain decomposition. We understand that this is currently being implemented and we look forward to seeing the gains your group achieves with domain decomposition. We agree that manually vectorizations, as you mention, will result in some improvements as well. Another optimization you can try is loop unrolling. 
