# test
arrangingNodesOnOrientation

I am trying to amend the GameViewController for a SpriteKit game so that when the device is rotated the nodes on the scene move into a different position.

I have been looking at a coupole of guides online:

∙ An old one from c2013~2014 focusing on viewWillLayoutSubviews to return the bound correct values on rotation, apparently.

ref: https://web.archive.org/web/20160925093923/http://www.ymc.ch/en/ios-7-sprite-kit-setting-up-correct-scene-dimensions

∙ A useful link from Paul Hudson on the matter on willTransition(to:) (which I have made the most progress with):

ref: https://www.hackingwithswift.com/example-code/uikit/how-to-read-the-interface-orientation-portrait-or-landscape

∙ A post on Notification Center on StackOverflow could be the answer: 

https://stackoverflow.com/questions/36285822/redraw-subviews-programmatically-on-orientation-change

∙ Finally, there is an old project from 2015 by mgrebenets that offer Auto Layout like functionality for SpriteKit:

ref: https://github.com/mgrebenets/SpriteKitAutoLayout


I don't know if it can be done, but this code is basically to show what I have and as it's pretty basic should be useful to all.
