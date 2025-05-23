---
title: Color
second_title: Aspose.Slides for C++ API Reference
description: "Represents a color. This type should be allocated on stack and passed to functions by value or by reference. Never use System::SmartPtr class to manage objects of this type."
type: docs
weight: 53
url: /system.drawing/color/
---
## Color class


Represents a color. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Color
```

## Methods

| Method | Description |
| --- | --- |
|  [Color](./color/)() | Constructs an \"empty\" instance of [Color](./) class that does not represent any color. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Determines if the current and the specified [Color](./) objects represent the same color. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Constructs an instance of [Color](./) class that reprsents the specfied color. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Constructs an instance of [Color](./) class that reprsents the specfied color. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Constructs an instance of [Color](./) class that reprsents the specfied color with alpha component set to 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Constructs an instance of [Color](./) class that reprsents the specfied color. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Constructs an instance of [Color](./) class that represents the specified known color. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Constructs an instance of [Color](./) class that represents a color with the specified name. |
| int [get_A](./get_a/)() const | Returns the value of the alpha component of the color represented by the current object. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Returns a color whose ARGB value in hexadecimal notation is #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF0FFFF. |
| int [get_B](./get_b/)() const | Returns the value of the blue component of the color represented by the current object. |
| static [Color](./) [get_Beige](./get_beige/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Returns a color whose ARGB value in hexadecimal notation is #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Returns a color whose ARGB value in hexadecimal notation is #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Returns a color whose ARGB value in hexadecimal notation is #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Returns a color whose ARGB value in hexadecimal notation is #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Returns a color whose ARGB value in hexadecimal notation is #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Returns a color whose ARGB value in hexadecimal notation is #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Returns a color whose ARGB value in hexadecimal notation is #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Returns a color whose ARGB value in hexadecimal notation is #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Returns a color whose ARGB value in hexadecimal notation is #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Returns a color whose ARGB value in hexadecimal notation is #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Returns a color whose ARGB value in hexadecimal notation is #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Returns a color whose ARGB value in hexadecimal notation is #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Returns a color whose ARGB value in hexadecimal notation is #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Returns a color whose ARGB value in hexadecimal notation is #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Returns a color whose ARGB value in hexadecimal notation is #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Returns a color whose ARGB value in hexadecimal notation is #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Returns a color whose ARGB value in hexadecimal notation is #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF00FF. |
| int [get_G](./get_g/)() const | Returns the value of the green component of the color represented by the current object. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Returns a color whose ARGB value in hexadecimal notation is #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Returns a color whose ARGB value in hexadecimal notation is #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Returns a color whose ARGB value in hexadecimal notation is #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Returns a color whose ARGB value in hexadecimal notation is #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Returns a color whose ARGB value in hexadecimal notation is #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Returns a value that indicate if the current object is \"empty\" i.e. does not represent any color. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Returns a value that determines whether the [Color](./) structure represents a named color or a member of the KnownColor enumeration. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Returns a color whose ARGB value in hexadecimal notation is #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Returns a color whose ARGB value in hexadecimal notation is #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Returns a color whose ARGB value in hexadecimal notation is #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Returns a color whose ARGB value in hexadecimal notation is #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Returns a color whose ARGB value in hexadecimal notation is #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Returns a color whose ARGB value in hexadecimal notation is #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Returns a color whose ARGB value in hexadecimal notation is #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Returns a color whose ARGB value in hexadecimal notation is #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Returns a color whose ARGB value in hexadecimal notation is #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Returns a color whose ARGB value in hexadecimal notation is #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Returns the name of the color represented by the current object. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Returns a color whose ARGB value in hexadecimal notation is #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Returns a color whose ARGB value in hexadecimal notation is #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Returns a color whose ARGB value in hexadecimal notation is #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Returns a color whose ARGB value in hexadecimal notation is #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Returns a color whose ARGB value in hexadecimal notation is #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Returns a color whose ARGB value in hexadecimal notation is #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Returns a color whose ARGB value in hexadecimal notation is #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Returns a color whose ARGB value in hexadecimal notation is #FF800080. |
| int [get_R](./get_r/)() const | Returns the value of the red component of the color represented by the current object. |
| static [Color](./) [get_Red](./get_red/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Returns a color whose ARGB value in hexadecimal notation is #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Returns a color whose ARGB value in hexadecimal notation is #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Returns a color whose ARGB value in hexadecimal notation is #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Returns a color whose ARGB value in hexadecimal notation is #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Returns a color whose ARGB value in hexadecimal notation is #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Returns a color whose ARGB value in hexadecimal notation is #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Returns a color whose ARGB value in hexadecimal notation is #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Returns a color whose ARGB value in hexadecimal notation is #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Returns a color whose ARGB value in hexadecimal notation is #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Returns a color whose ARGB value in hexadecimal notation is #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Returns a color whose ARGB value in hexadecimal notation is #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Returns a color whose ARGB value in hexadecimal notation is #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Returns a color whose ARGB value in hexadecimal notation is #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Returns a color whose ARGB value in hexadecimal notation is #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Returns a color whose ARGB value in hexadecimal notation is #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Returns the brightness component of the color reprsented by the current object. |
| int [GetHashCode](./gethashcode/)() const | Returns the hash code of the current object. |
| **float** [GetHue](./gethue/)() | Returns the Hue-Saturation-Brightness (HSB) hue value, in degrees, for the color reprsented by the current object. |
| **float** [GetSaturation](./getsaturation/)() | Returns the Hue-Saturation-Brightness (HSB) saturation for the color reprsented by the current object. |
| **bool** [IsNull](./isnull/)() const | Always returns false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Always returns true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Determines if the current and the specified [Color](./) objects represent distinct colors. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Always returns false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Determines if the current and the specified [Color](./) objects represent the same color. |
| int [ToArgb](./toargb/)() const | Returns a 32-bit ARGB value of the color represented by the current object. |
| [String](../../system/string/) [ToString](./tostring/)() const | Returns the string representation of the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | An \"empty\" instance of [Color](./) class i.e. an instance that does not represent any color. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)