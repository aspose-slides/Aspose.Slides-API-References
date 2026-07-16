---
title: Color
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une couleur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 53
url: /fr/system.drawing/color/
---
## Classe Color

Représente une couleur. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../../system/smartptr/) pour gérer des objets de ce type.

```cpp
class Color
```

## Méthodes

| Method | Description |
| --- | --- |
|  [Color](./color/)() | Construit une instance \"vide\" de la classe [Color](./) qui ne représente aucune couleur. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Détermine si l'objet actuel et l'objet [Color](./) spécifié représentent la même couleur. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Construit une instance de la classe [Color](./) qui représente la couleur spécifiée. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Construit une instance de la classe [Color](./) qui représente la couleur spécifiée. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Construit une instance de la classe [Color](./) qui représente la couleur spécifiée avec le composant alpha fixé à 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Construit une instance de la classe [Color](./) qui représente la couleur spécifiée. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Construit une instance de la classe [Color](./) qui représente la couleur connue spécifiée. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Construit une instance de la classe [Color](./) qui représente une couleur avec le nom spécifié. |
| int [get_A](./get_a/)() const | Renvoie la valeur du composant alpha de la couleur représentée par l'objet actuel. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF0FFFF. |
| int [get_B](./get_b/)() const | Renvoie la valeur du composant bleu de la couleur représentée par l'objet actuel. |
| static [Color](./) [get_Beige](./get_beige/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF00FF. |
| int [get_G](./get_g/)() const | Renvoie la valeur du composant vert de la couleur représentée par l'objet actuel. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Renvoie une valeur qui indique si l'objet actuel est \"vide\", c’est-à-dire ne représente aucune couleur. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Renvoie une valeur qui détermine si la structure [Color](./) représente une couleur nommée ou un membre de l'énumération KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Renvoie le nom de la couleur représentée par l'objet actuel. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF800080. |
| int [get_R](./get_r/)() const | Renvoie la valeur du composant rouge de la couleur représentée par l'objet actuel. |
| static [Color](./) [get_Red](./get_red/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Renvoie une couleur dont la valeur ARGB en notation hexadécimale est #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Renvoie le composant de luminosité de la couleur représentée par l'objet actuel. |
| int [GetHashCode](./gethashcode/)() const | Renvoie le code de hachage de l'objet actuel. |
| **float** [GetHue](./gethue/)() | Renvoie la teinte (Hue) du modèle Teinte-Saturation-Luminosité (HSB), en degrés, pour la couleur représentée par l'objet actuel. |
| **float** [GetSaturation](./getsaturation/)() | Renvoie la saturation (Saturation) du modèle HSB pour la couleur représentée par l'objet actuel. |
| **bool** [IsNull](./isnull/)() const | Renvoie toujours false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Renvoie toujours true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Détermine si l'objet actuel et les objets [Color](./) spécifiés représentent des couleurs distinctes. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Renvoie toujours false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Détermine si l'objet actuel et les objets [Color](./) spécifiés représentent la même couleur. |
| int [ToArgb](./toargb/)() const | Renvoie une valeur ARGB 32 bits de la couleur représentée par l'objet actuel. |
| [String](../../system/string/) [ToString](./tostring/)() const | Renvoie la représentation sous forme de chaîne de caractères de l'objet actuel. |
## Champs

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Une instance \"vide\" de la classe [Color](./), c’est-à-dire une instance qui ne représente aucune couleur. |
## Voir aussi

* Espace de noms [System::Drawing](../)
* Bibliothèque [Aspose.Slides](../../)