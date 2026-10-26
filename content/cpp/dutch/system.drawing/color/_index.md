---
title: Color
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een kleur voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 53
url: /nl/system.drawing/color/
---
## Color klasse

Stelt een kleur voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Color
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [Color](./color/)() | Construeert een \"lege\" instantie van [Color](./) klasse die geen kleur vertegenwoordigt. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Bepaalt of het huidige en het opgegeven [Color](./) objecten dezelfde kleur vertegenwoordigen. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Construeert een instantie van [Color](./) klasse die de opgegeven kleur vertegenwoordigt. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Construeert een instantie van [Color](./) klasse die de opgegeven kleur vertegenwoordigt. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Construeert een instantie van [Color](./) klasse die de opgegeven kleur met alfa-component 0xFF vertegenwoordigt. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Construeert een instantie van [Color](./) klasse die de opgegeven kleur vertegenwoordigt. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Construeert een instantie van [Color](./) klasse die de opgegeven bekende kleur vertegenwoordigt. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Construeert een instantie van [Color](./) klasse die een kleur met de opgegeven naam vertegenwoordigt. |
| int [get_A](./get_a/)() const | Retourneert de waarde van de alfa-component van de kleur die wordt weergegeven door het huidige object. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF0F8FF is. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFAEBD7 is. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00FFFF is. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF7FFFD4 is. |
| static [Color](./) [get_Azure](./get_azure/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF0FFFF is. |
| int [get_B](./get_b/)() const | Retourneert de waarde van de blauwe component van de kleur die wordt weergegeven door het huidige object. |
| static [Color](./) [get_Beige](./get_beige/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF5F5DC is. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFE4C4 is. |
| static [Color](./) [get_Black](./get_black/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF000000 is. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFEBCD is. |
| static [Color](./) [get_Blue](./get_blue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF0000FF is. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF8A2BE2 is. |
| static [Color](./) [get_Brown](./get_brown/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFA52A2A is. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDEB887 is. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF5F9EA0 is. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF7FFF00 is. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFD2691E is. |
| static [Color](./) [get_Coral](./get_coral/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF7F50 is. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF6495ED is. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFF8DC is. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDC143C is. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00FFFF is. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00008B is. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF008B8B is. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFB8860B is. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFA9A9A9 is. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF006400 is. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFBDB76B is. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF8B008B is. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF556B2F is. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF8C00 is. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF9932CC is. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF8B0000 is. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFE9967A is. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF8FBC8F is. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF483D8B is. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF2F4F4F is. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00CED1 is. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF9400D3 is. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF1493 is. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00BFFF is. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF696969 is. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF1E90FF is. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFB22222 is. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFAF0 is. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF228B22 is. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF00FF is. |
| int [get_G](./get_g/)() const | Retourneert de waarde van de groene component van de kleur die wordt weergegeven door het huidige object. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDCDCDC is. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF8F8FF is. |
| static [Color](./) [get_Gold](./get_gold/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFD700 is. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDAA520 is. |
| static [Color](./) [get_Gray](./get_gray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF808080 is. |
| static [Color](./) [get_Green](./get_green/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF008000 is. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFADFF2F is. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF0FFF0 is. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF69B4 is. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFCD5C5C is. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF4B0082 is. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Retourneert een waarde die aangeeft of het huidige object \"leeg\" is, d.w.z. geen kleur vertegenwoordigt. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Retourneert een waarde die bepaalt of de [Color](./) structuur een benoemde kleur vertegenwoordigt of een lid van de KnownColor-enumeratie. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFFF0 is. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF0E68C is. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFE6E6FA is. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFF0F5 is. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF7CFC00 is. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFACD is. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFADD8E6 is. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF08080 is. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFE0FFFF is. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFAFAD2 is. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFD3D3D3 is. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF90EE90 is. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFB6C1 is. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFA07A is. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF20B2AA is. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF87CEFA is. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF778899 is. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFB0C4DE is. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFFE0 is. |
| static [Color](./) [get_Lime](./get_lime/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00FF00 is. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF32CD32 is. |
| static [Color](./) [get_Linen](./get_linen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFAF0E6 is. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF00FF is. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF800000 is. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF66CDAA is. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF0000CD is. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFBA55D3 is. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF9370DB is. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF3CB371 is. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF7B68EE is. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00FA9A is. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF48D1CC is. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFC71585 is. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF191970 is. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF5FFFA is. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFE4E1 is. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFE4B5 is. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Retourneert de naam van de kleur die wordt weergegeven door het huidige object. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFDEAD is. |
| static [Color](./) [get_Navy](./get_navy/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF000080 is. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFDF5E6 is. |
| static [Color](./) [get_Olive](./get_olive/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF808000 is. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF6B8E23 is. |
| static [Color](./) [get_Orange](./get_orange/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFA500 is. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF4500 is. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDA70D6 is. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFEEE8AA is. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF98FB98 is. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFAFEEEE is. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDB7093 is. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFEFD5 is. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFDAB9 is. |
| static [Color](./) [get_Peru](./get_peru/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFCD853F is. |
| static [Color](./) [get_Pink](./get_pink/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFC0CB is. |
| static [Color](./) [get_Plum](./get_plum/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFDDA0DD is. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFB0E0E6 is. |
| static [Color](./) [get_Purple](./get_purple/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF800080 is. |
| int [get_R](./get_r/)() const | Retourneert de waarde van de rode component van de kleur die wordt weergegeven door het huidige object. |
| static [Color](./) [get_Red](./get_red/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF0000 is. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFBC8F8F is. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF4169E1 is. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF8B4513 is. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFA8072 is. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF4A460 is. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF2E8B57 is. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFF5EE is. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFA0522D is. |
| static [Color](./) [get_Silver](./get_silver/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFC0C0C0 is. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF87CEEB is. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF6A5ACD is. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF708090 is. |
| static [Color](./) [get_Snow](./get_snow/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFAFA is. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF00FF7F is. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF4682B4 is. |
| static [Color](./) [get_Tan](./get_tan/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFD2B48C is. |
| static [Color](./) [get_Teal](./get_teal/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF008080 is. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFD8BFD8 is. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFF6347 is. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #00FFFFFF is. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF40E0D0 is. |
| static [Color](./) [get_Violet](./get_violet/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFEE82EE is. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF5DEB3 is. |
| static [Color](./) [get_White](./get_white/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFFFF is. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFF5F5F5 is. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FFFFFF00 is. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Retourneert een kleur waarvan de ARGB-waarde in hexadecimale notatie #FF9ACD32 is. |
| **float** [GetBrightness](./getbrightness/)() | Retourneert de helderheidscomponent van de kleur die wordt weergegeven door het huidige object. |
| int [GetHashCode](./gethashcode/)() const | Retourneert de hashcode van het huidige object. |
| **float** [GetHue](./gethue/)() | Retourneert de Hue-Saturation-Brightness (HSB) tintwaarde, in graden, voor de kleur die wordt weergegeven door het huidige object. |
| **float** [GetSaturation](./getsaturation/)() | Retourneert de Hue-Saturation-Brightness (HSB) verzadiging voor de kleur die wordt weergegeven door het huidige object. |
| **bool** [IsNull](./isnull/)() const | Retourneert altijd false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Retourneert altijd true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Bepaalt of het huidige en het opgegeven [Color](./) objecten verschillende kleuren vertegenwoordigen. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Retourneert altijd false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Bepaalt of het huidige en het opgegeven [Color](./) objecten dezelfde kleur vertegenwoordigen. |
| int [ToArgb](./toargb/)() const | Retourneert een 32-bit ARGB-waarde van de kleur die wordt weergegeven door het huidige object. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het huidige object. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een \"lege\" instantie van [Color](./) klasse, d.w.z. een instantie die geen kleur vertegenwoordigt. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)