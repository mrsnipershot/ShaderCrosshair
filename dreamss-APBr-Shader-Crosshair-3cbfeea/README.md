APBr-Shader-Crosshair
=====================

Customizable crosshair for the game APB Reloaded

Installation:

1. Copy all the Crosshair*.usf files to Engine\Shaders (Crosshair.usf, CrosshairSettings.usf, CrosshairDot1.usf, CrosshairDot2.usf, ...)
2. Overwrite *APBUberPostProcessBlendPixelShader.usf* with the included file, or if you're not using the default shaders, add *#include "Crosshair.usf"* before the closing bracket in your shaders.
3. Edit CrosshairSettings.usf and set your screen resolution.
4. Enable/disable crosshairs of your choice in CrosshairSettings.usf, tweak color options to your liking.


Notes:

* This is a work in progress.
* SCREEN_SIZE_X SCREEN_SIZE_Y must match your monitor resolution for aspect ratio correction.
* Crosshair won't work if bloom is off.
* Included APBUberPostProcessBlendPixelShader.usf is from 1.9.1 live, rename and use noblue/rtw shaders if you prefer them.
* Make Sure your resolution is correct in APBr. Going from full screen to windowed and back sets a smaller resolution than it indicates, and it will throw off apsect ratio correction.
* Feel free to bundle it with your own shader pack, just leave the notes area alone and please credit us.