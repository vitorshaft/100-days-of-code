# 100 Days Of Code - Log

### Day 1: April 23, 2020

**Today's Progress**: Added Serial Reading to get motor rotation info and angular position differential control to handle latency.

**Thoughts:** Nice to finally write down the idea I had last night to the problem I found this week testing Raspberry Pi Mobile Robot (RMR). I have to test its performance before proceed to next step of this project.

**Link to work:** [RMR Robot (Portuguese only)](https://github.com/vitorshaft/roboMovel)

### Day 2: April 24, 2020

**Today's Progress**: Changed pair emitter/receiver of my lasertag robot project: "Kabuto 2". The code now uses interrupt and I also changed bluetooth communication pins to avoid conflict to USB communication pins (0 and 1) during code upload to Arduino.

**Thoughts:** I ask my self how did I procrastinated so long to solve this issue on Kabuto 2. It was thankful to see how I have grown because it was simple to code and solve an old problem (from 2 years ago) with some experience acquired during this time.

**Link to work:** [Kabuto 2 project (lasertag robot controlled via smartphone app)](https://github.com/vitorshaft/kabuto)

### Day 3: April 25, 2020

**Today's Progress**: Modified the management of data received from LoRa via Serial port. It was needed to use dictionaries instead of lists to insert a kind of index to each entry and the index is the number of package (non-sequential).

**Thoughts:** My mind has burnt! handling data perhaps is not my major skill because of its "long-thread" way of thinking and power of co-relation between different data. Fortunately, I found an easier way to handle and update data on the JSON file.

**Link to work:** [Cubesat Raspberry ground station](https://github.com/vitorshaft/RaspFixaM1)
