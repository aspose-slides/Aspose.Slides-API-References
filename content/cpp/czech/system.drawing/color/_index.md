---
title: Color
second_title: Aspose.Slides pro C++ – reference API
description: "Reprezentuje barvu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr k řízení objektů tohoto typu."
type: docs
weight: 53
url: /cs/system.drawing/color/
---
## Třída Color


Reprezentuje barvu. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../../system/smartptr/) k řízení objektů tohoto typu.

```cpp
class Color
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [Color](./color/)() | Vytvoří „prázdnou“ instanci třídy [Color](./), která nereprezentuje žádnou barvu. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Určuje, zda aktuální a zadané objekty [Color](./) představují stejnou barvu. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Vytvoří instanci třídy [Color](./) představující určenou barvu. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Vytvoří instanci třídy [Color](./) představující určenou barvu. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Vytvoří instanci třídy [Color](./) představující určenou barvu s alfa komponentou nastavenou na 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Vytvoří instanci třídy [Color](./) představující určenou barvu. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Vytvoří instanci třídy [Color](./) představující zadanou známou barvu. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Vytvoří instanci třídy [Color](./) představující barvu se zadaným názvem. |
| int [get_A](./get_a/)() const | Vrátí hodnotu alfa komponenty barvy reprezentované aktuálním objektem. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF0FFFF. |
| int [get_B](./get_b/)() const | Vrátí hodnotu modré komponenty barvy reprezentované aktuálním objektem. |
| static [Color](./) [get_Beige](./get_beige/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF00FF. |
| int [get_G](./get_g/)() const | Vrátí hodnotu zelené komponenty barvy reprezentované aktuálním objektem. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Vrátí hodnotu, která udává, zda je aktuální objekt „prázdný“, tj. nereprezentuje žádnou barvu. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Vrátí hodnotu, která určuje, zda struktura [Color](./) představuje pojmenovanou barvu nebo člen výčtu KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Vrátí název barvy reprezentované aktuálním objektem. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF800080. |
| int [get_R](./get_r/)() const | Vrátí hodnotu červené komponenty barvy reprezentované aktuálním objektem. |
| static [Color](./) [get_Red](./get_red/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Vrátí barvu, jejíž hodnota ARGB v hexadecimálním zápisu je #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Vrátí složku jasnosti barvy reprezentované aktuálním objektem. |
| int [GetHashCode](./gethashcode/)() const | Vrátí hash kód aktuálního objektu. |
| **float** [GetHue](./gethue/)() | Vrátí hodnotu odstínu (Hue) v systému HSB, ve stupních, pro barvu reprezentovanou aktuálním objektem. |
| **float** [GetSaturation](./getsaturation/)() | Vrátí saturaci v systému HSB pro barvu reprezentovanou aktuálním objektem. |
| **bool** [IsNull](./isnull/)() const | Vždy vrací false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Vždy vrací true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Určuje, zda aktuální a zadané objekty [Color](./) představují odlišné barvy. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Vždy vrací false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Určuje, zda aktuální a zadané objekty [Color](./) představují stejnou barvu. |
| int [ToArgb](./toargb/)() const | Vrátí 32-bitovou hodnotu ARGB barvy reprezentované aktuálním objektem. |
| [String](../../system/string/) [ToString](./tostring/)() const | Vrátí řetězcovou reprezentaci aktuálního objektu. |
## Pole

| Pole | Popis |
| --- | --- |
| static [Empty](./empty/) | „Prázdná“ instance třídy [Color](./), tj. instance, která nereprezentuje žádnou barvu. |
## Viz také

* Jmenný prostor [System::Drawing](../)
* Knihovna [Aspose.Slides](../../)