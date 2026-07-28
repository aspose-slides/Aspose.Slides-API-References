---
title: Color
second_title: Aspose.Slides C++ API hivatkozás
description: "Egy színt ábrázol. Ennek a típusnak a stacken kell tárolni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 53
url: /hu/system.drawing/color/
---
## Szín osztály


Színt képvisel. Ennek a típusnak a stacken kell kerülni és értékkel vagy referenciával átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Color
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [Color](./color/)() | Létrehoz egy \"üres\" példányt a [Color](./) osztályból, amely nem képvisel semmilyen színt. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Megállapítja, hogy az aktuális és a megadott [Color](./) objektumok ugyanazt a színt képviselik-e. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott színt képviseli. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott színt képviseli. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott színt ábrázolja, az alfa komponens 0xFF értékkel. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott színt képviseli. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott ismert színt ábrázolja. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Létrehoz egy példányt a [Color](./) osztályból, amely a megadott névvel rendelkező színt ábrázolja. |
| int [get_A](./get_a/)() const | Visszaadja az alfa komponens értékét annak a színnek, amelyet az aktuális objektum képvisel. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF0FFFF. |
| int [get_B](./get_b/)() const | Visszaadja a kék komponens értékét annak a színnek, amelyet az aktuális objektum képvisel. |
| static [Color](./) [get_Beige](./get_beige/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF00FF. |
| int [get_G](./get_g/)() const | Visszaadja a zöld komponens értékét annak a színnek, amelyet az aktuális objektum képvisel. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Visszaad egy értéket, amely jelzi, hogy az aktuális objektum \"üres\"-e, azaz nem képvisel semmilyen színt. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Visszaad egy értéket, amely meghatározza, hogy a [Color](./) struktúra egy névvel ellátott színt vagy a KnownColor felsorolás egy elemét ábrázolja-e. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Visszaadja a szín nevét, amelyet az aktuális objektum képvisel. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF800080. |
| int [get_R](./get_r/)() const | Visszaadja a piros komponens értékét annak a színnek, amelyet az aktuális objektum képvisel. |
| static [Color](./) [get_Red](./get_red/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Visszaad egy színt, amelynek az ARGB értéke hexadecimális formátumban #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Visszaadja a fényerő komponensét a színnek, amelyet az aktuális objektum képvisel. |
| int [GetHashCode](./gethashcode/)() const | Visszaadja az aktuális objektum hash kódját. |
| **float** [GetHue](./gethue/)() | Visszaadja a Hue-Saturation-Brightness (HSB) árnyalat értékét fokban a színnek, amelyet az aktuális objektum képvisel. |
| **float** [GetSaturation](./getsaturation/)() | Visszaadja a Hue-Saturation-Brightness (HSB) telítettséget a színnek, amelyet az aktuális objektum képvisel. |
| **bool** [IsNull](./isnull/)() const | Mindig hamis értéket ad vissza. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Mindig igaz értéket ad vissza. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Megállapítja, hogy az aktuális és a megadott [Color](./) objektumok különböző színeket képviselnek-e. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Mindig hamis értéket ad vissza. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Megállapítja, hogy az aktuális és a megadott [Color](./) objektumok ugyanazt a színt képviselik-e. |
| int [ToArgb](./toargb/)() const | Visszaad egy 32 bites ARGB értéket a színnek, amelyet az aktuális objektum képvisel. |
| [String](../../system/string/) [ToString](./tostring/)() const | Visszaadja az aktuális objektum karakterlánc reprezentációját. |
## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Egy \"üres\" példány a [Color](./) osztályból, azaz egy példány, amely nem képvisel semmilyen színt. |
## Lásd még

* Névterület [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)