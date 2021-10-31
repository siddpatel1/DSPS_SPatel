|Figure 1 : Original Plot|
| :----------------------------------------------------------: |
| <img src="obj7566old.png" alt = "Figure 1" style= "zoom:10%;"/> |

|Figure 2 : Updated Plot|
| :----------------------------------------------------------: |
| <img src="obj7566new.png" alt = "Figure 2" style= "zoom:10%;"/> |



The original plot's data was way too dense, inherently it is but visually we can change that, and the plot did not have a legend to distinguish the color of the data points. And it is hard to tell what we are even looking at, the title isn't helping at all.  

In the updated plot, I updated the title so that we know what we are looking at. I also added a plot legend (let matplotlib optimize the location, but made the legend 2 columns to fit better) to distinguish what the colors of the data points meant. Each color represents a data point from a certain light filter that was used when measuring the astrophysical object. I also changed the colors using the seaborn library, so that I could use an equivalent color palette that was color-blind friendly. Since the points are very close together, I lowered the opacity of the points to 50% so that it is easier to see overlap between points, also to help with this I made the plot larger. I also made the font size uniform across the plot, so the labels can be nicely read as to the proportional size of the plot.
