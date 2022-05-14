# CACHE EVICTION STRATEGIES

### Please visit ```Experiment.ipynb``` in order to view my experiment.

# My Overview

### Definition

<b>In computing, <u>Cache</u> is a hardware or software component that stores data so that future requests for that data can be served faster. </b>
    
### Problems With Cache
    
<li><b>Cache gets full</b>: In order to make caches relatively faster at retrieving data, there is a substantial tradeoff with storage and hence the cache gets full and requires a policy for replacing data stored in cache.</li>
  
<li><b>Cache goes stale</b>: Cache needs to know when to flush data out as eventually the data provided to us might change overtime and thus requires to be flushed out. </li>
   
</ul>

Hence, there is a need for various <b>Cache Eviction Strategies</b> in order to guide us what data is to be removed when we need to write in new data to the cache.

### Cache Eviction Strategies used by me in this Lab:
  
 <ul>
     <li><b>Random</b>: Replaces any one randomly chosen data from the cache.</li>
     <li><b>Least Recently Used(LRU)</b>: Keeps track of an entry that hasn't been used for the longest time and replaces it.</li>
     <li><b>Cyclic(FILO)</b>: Replaces the oldest entry of the cache.</li></ul>
     
 # My Objective
   
   <ul>
        <li>Compare between the performances of <b>LRU</b>, <b>Cyclic</b> and <b>Random</b> Cache Eviction algorithms.</li>
        <li>To provide test cases with varying cache size (Test 1 - Test 3).</li>
        <li>To provide test cases with varying data size and thus experimenting with <b>locality</b> (Test 4 - Test 6).</li>
        <li>To provide separate test cases experimenting with <b>Spatial Locality</b> (Test 8 & Test 9).</li>
        <li>To provide separate test cases experimenting with <b>Temporal Locality</b> (Test 10 & Test 11).</li>
        <li>To provide a comprehensive analysis for the results observed in each case.</li>
        <li>To visualise test cases for deeper understanding.</li></ul>     
    <hr><br>



