---
title: Color
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en färg. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 53
url: /sv/system.drawing/color/
---
## Color-klass

Representerar en färg. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller som referens. Använd aldrig [System::SmartPtr](../../system/smartptr/) klass för att hantera objekt av denna typ.

```cpp
class Color
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [Color](./color/)() | Skapar en "tom" instans av [Color](./) klass som inte representerar någon färg. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Avgör om det nuvarande och det angivna [Color](./) objektet representerar samma färg. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Skapar en instans av [Color](./) klass som representerar den angivna färgen. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Skapar en instans av [Color](./) klass som representerar den angivna färgen. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Skapar en instans av [Color](./) klass som representerar den angivna färgen med alfakomponenten satt till 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Skapar en instans av [Color](./) klass som representerar den angivna färgen. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Skapar en instans av [Color](./) klass som representerar den specificerade kända färgen. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Skapar en instans av [Color](./) klass som representerar en färg med det angivna namnet. |
| int [get_A](./get_a/)() const | Returnerar värdet för alfakomponenten i färgen som det nuvarande objektet representerar. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF0FFFF. |
| int [get_B](./get_b/)() const | Returnerar värdet för den blå komponenten i färgen som det nuvarande objektet representerar. |
| static [Color](./) [get_Beige](./get_beige/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF00FF. |
| int [get_G](./get_g/)() const | Returnerar värdet för den gröna komponenten i färgen som det nuvarande objektet representerar. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Returnerar ett värde som indikerar om det nuvarande objektet är "tomt", d.v.s. inte representerar någon färg. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Returnerar ett värde som avgör om [Color](./)-strukturen representerar en namngiven färg eller en medlem i KnownColor-enumerationen. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Returnerar färgens namn som representeras av det nuvarande objektet. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF800080. |
| int [get_R](./get_r/)() const | Returnerar värdet för den röda komponenten i färgen som det nuvarande objektet representerar. |
| static [Color](./) [get_Red](./get_red/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Returnerar en färg vars ARGB-värde i hexadecimal notation är #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Returnerar ljusstyrkekomponenten i färgen som det nuvarande objektet representerar. |
| int [GetHashCode](./gethashcode/)() const | Returnerar hash-koden för det nuvarande objektet. |
| **float** [GetHue](./gethue/)() | Returnerar Hue-Saturation-Brightness-nyansen (HSB) i grader för färgen som det nuvarande objektet representerar. |
| **float** [GetSaturation](./getsaturation/)() | Returnerar Hue-Saturation-Brightness-mättnaden för färgen som det nuvarande objektet representerar. |
| **bool** [IsNull](./isnull/)() const | Returnerar alltid falskt. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Returnerar alltid sant. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Avgör om det nuvarande och det angivna [Color](./) objektet representerar olika färger. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Returnerar alltid falskt. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Avgör om det nuvarande och det angivna [Color](./) objektet representerar samma färg. |
| int [ToArgb](./toargb/)() const | Returnerar ett 32-bit ARGB-värde för färgen som det nuvarande objektet representerar. |
| [String](../../system/string/) [ToString](./tostring/)() const | Returnerar strängrepresentationen av det nuvarande objektet. |

## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En "tom" instans av [Color](./) klass, d.v.s. en instans som inte representerar någon färg. |

## Se också

* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)