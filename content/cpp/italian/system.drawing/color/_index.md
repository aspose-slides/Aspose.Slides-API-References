---
title: Color
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un colore. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 53
url: /it/system.drawing/color/
---
## Color classe

Rappresenta un colore. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare la [System::SmartPtr](../../system/smartptr/) classe per gestire oggetti di questo tipo.

```cpp
class Color
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [Color](./color/)() | Crea un'istanza "vuota" della classe [Color](./) che non rappresenta alcun colore. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Determina se l'oggetto corrente e quello specificato [Color](./) rappresentano lo stesso colore. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Crea un'istanza della classe [Color](./) che rappresenta il colore specificato. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Crea un'istanza della classe [Color](./) che rappresenta il colore specificato. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Crea un'istanza della classe [Color](./) che rappresenta il colore specificato con il componente alfa impostato a 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Crea un'istanza della classe [Color](./) che rappresenta il colore specificato. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Crea un'istanza della classe [Color](./) che rappresenta il colore noto specificato. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Crea un'istanza della classe [Color](./) che rappresenta un colore con il nome specificato. |
| int [get_A](./get_a/)() const | Restituisce il valore del componente alfa del colore rappresentato dall'oggetto corrente. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF0FFFF. |
| int [get_B](./get_b/)() const | Restituisce il valore del componente blu del colore rappresentato dall'oggetto corrente. |
| static [Color](./) [get_Beige](./get_beige/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF00FF. |
| int [get_G](./get_g/)() const | Restituisce il valore del componente verde del colore rappresentato dall'oggetto corrente. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Restituisce un valore che indica se l'oggetto corrente è "vuoto", cioè non rappresenta alcun colore. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Restituisce un valore che determina se la struttura [Color](./) rappresenta un colore denominato o un membro dell'enumerazione KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Restituisce il nome del colore rappresentato dall'oggetto corrente. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF800080. |
| int [get_R](./get_r/)() const | Restituisce il valore del componente rosso del colore rappresentato dall'oggetto corrente. |
| static [Color](./) [get_Red](./get_red/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Restituisce un colore il cui valore ARGB in notazione esadecimale è #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Restituisce il componente di luminosità del colore rappresentato dall'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce il codice hash dell'oggetto corrente. |
| **float** [GetHue](./gethue/)() | Restituisce il valore di tonalità (Hue) dell'Hue-Saturation-Brightness (HSB) in gradi per il colore rappresentato dall'oggetto corrente. |
| **float** [GetSaturation](./getsaturation/)() | Restituisce la saturazione dell'Hue-Saturation-Brightness (HSB) per il colore rappresentato dall'oggetto corrente. |
| **bool** [IsNull](./isnull/)() const | Restituisce sempre false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Restituisce sempre true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Determina se l'oggetto corrente e quello specificato [Color](./) rappresentano colori distinti. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Restituisce sempre false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Determina se l'oggetto corrente e quello specificato [Color](./) rappresentano lo stesso colore. |
| int [ToArgb](./toargb/)() const | Restituisce un valore ARGB a 32 bit del colore rappresentato dall'oggetto corrente. |
| [String](../../system/string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa dell'oggetto corrente. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [Empty](./empty/) | Un'istanza "vuota" della classe [Color](./), cioè un'istanza che non rappresenta alcun colore. |

## Vedi anche

* Namespace [System::Drawing](../)
* Libreria [Aspose.Slides](../../)