Testing the datasets in Meshroom

## Meshroom Benchmark test ##

# Horse dataset from tanksandtemples.org
images: 151
total size: 71MB

# Meshroom defaults
GPU usage up to 60% (GTX 1070 / 8GB)
CPU usage up to 97% (i7-7820 @ 3.3 GHz)
RAM usage up to 7GB (32GB total)

Processing time (Meshroom default): 64 minutes
Result: Horse was not reconstructed, but the surroundings were
Note: no masks were used

Mesh
File size: 37MB
Vertices: 269749
Faces: 538311

![alt text](https://github.com/natowi/photogrammetry_datasets/blob/master/screenshots/horse1pt.JPG "Image 1")
![alt text](https://github.com/natowi/photogrammetry_datasets/blob/master/screenshots/horse1mesh.JPG "Image 1")

# Meshroom + Ultra + AKAZE
GPU usage up to 60% (GTX 1070 / 8GB)
CPU usage up to 99% (i7-7820 @ 3.3 GHz)
RAM usage up to 7.5GB (32GB total)

Processing time: 180 min

# Meshroom + Ultra + all algorithms
GPU usage up to 60% (GTX 1070 / 8GB)
CPU usage up to 99% (i7-7820 @ 3.3 GHz)
RAM usage up to 12GB (32GB total)
Processing time: 7h 
no horse

--> test again with masks
