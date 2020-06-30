# Guacamole recipe ja jotain uutta

used in teaching git

# pcfumble

Repository for point cloud manipulation tools. Please see section "Quickstart guide by feature" before applying the functions; the functions may need some tricks to work correctly.


---

## Quickstart guide by feature

### Ground point classification

- See section "Classify ground points from a sub set of points" in script demo_pcfumble.m.m
- See following section(s) for visualisation of the results

### Sub-sample point cloud to have more homogeneous point density

See section "Sub sample point cloud uniformly" in script demo_pcfumble.m

### k nearest neighbour search

- See section "k nearest neighbour search" in script demo_pcfumble.m
- The function ??mex.mex contains a small bug, which is not listed in the documentation. Also, the input needs to be modified. See section "k nearest neighbour search" in script demo_pcfumble.m to deal with these issues. 
- Documentation of ??mex.mex can be found in file yy.ppt

### Range search

- See section "Range search" in script demo_pcfumble.m
- The input may need some modifications. See section "Range search" in script demo_pcfumble.m to deal with these issues. 
- Documentation of ??mex.mex can be found in file yy.ppt

### Divide the point cloud into blocks along the trajectory

- See section "Divide the point cloud into blocks along the trajectory" in script demo_pcfumble.m
- See following section(s) for visualisation of the results

### Extract profiles from a point cloud collected using a kinematic 2D scanner

- E.g., mobile laser scanning points clouds collected using FGI Roamer (one scanner)
- See section "Retrieve profiles" in script demo_pcfumble.m
- See following section(s) for visualisation of the results

## Quickstart guide by function

To be added. Please see script demo_pcfumble.m before applying the functions; the functions may need some tricks to work correctly.