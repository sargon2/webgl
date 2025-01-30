Tiles (to be renamed) is a simple game that shows you a grid of colored tiles.  In designing it, we want to maintain two design principles:

1. The user should have direct, immediate, implicit access to change the difficulty level.  This should happen almost without their knowledge.
2. The user's power should grow over time.

The color scheme should be customizable to handle colorblind users.

For 1, perhaps the difficulty could be linked to how high the user clicks in the grid?
It's also important that if the user takes the easy route, it takes longer to finish the level.

So, maybe if the user clicks at the top, it's easier, but slower.  Then if the user clicks at the bottom, it's more difficult, but if you do it right, it's faster.

But what makes it more difficult?  The set of tiles the user can click is smaller in size?
So, if the user clicks anywhere in the top row, it works.  If the user wants to click the bottom row, they must click the 1 correct tile.

Then, it takes multiple clicks to beat a level.

Clicks should be "juicy".  They should provide lots of visual feedback, and audio feedback if sound is turned on.  If the user clicks between tiles, the click should visually ripple, but have no effect.
