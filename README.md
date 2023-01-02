# apartmentHunting-problem
To solve this problem, my approach is to find the block with the minimum maximum distance to any of the required buildings. To do this, we can iterate through each block in the list and calculate the minimum distance from that block to any of the required buildings.

For each block, we can iterate through each required building and find the minimum distance from that block to the building. We can do this by searching both forward and backward from the current block, until we find a block with the required building.

We can then take the maximum of these distances for all the required buildings, which gives us the maximum distance from the current block to any of the required buildings.

Finally, we can return the index of the block with the minimum maximum distance to any of the required buildings. This block will be the most optimal one for the given requirements.
