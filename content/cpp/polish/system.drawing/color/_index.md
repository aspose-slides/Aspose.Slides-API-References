---
title: Color
second_title: Referencja API Aspose.Slides dla C++
description: "Reprezentuje kolor. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 53
url: /pl/system.drawing/color/
---
## Klasa Color

Reprezentuje kolor. Ten typ powinien być alokowany na stosie i przekazywany do funkcji przez wartość lub referencję. Nigdy nie używaj klasy [System::SmartPtr](../../system/smartptr/) do zarządzania obiektami tego typu.

```cpp
class Color
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [Color](./color/)() | Tworzy „pustą” instancję klasy [Color](./), która nie reprezentuje żadnego koloru. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Określa, czy bieżący i podany obiekt [Color](./) reprezentują ten sam kolor. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Tworzy instancję klasy [Color](./), która reprezentuje podany kolor. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Tworzy instancję klasy [Color](./), która reprezentuje podany kolor. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Tworzy instancję klasy [Color](./), która reprezentuje podany kolor z komponentem alfa ustawionym na 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Tworzy instancję klasy [Color](./), która reprezentuje podany kolor. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Tworzy instancję klasy [Color](./), która reprezentuje określony znany kolor. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Tworzy instancję klasy [Color](./), która reprezentuje kolor o podanej nazwie. |
| int [get_A](./get_a/)() const | Zwraca wartość komponentu alfa koloru reprezentowanego przez bieżący obiekt. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF0FFFF. |
| int [get_B](./get_b/)() const | Zwraca wartość komponentu niebieskiego koloru reprezentowanego przez bieżący obiekt. |
| static [Color](./) [get_Beige](./get_beige/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF00FF. |
| int [get_G](./get_g/)() const | Zwraca wartość komponentu zielonego koloru reprezentowanego przez bieżący obiekt. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Zwraca wartość wskazującą, czy bieżący obiekt jest „pusty”, czyli nie reprezentuje żadnego koloru. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Zwraca wartość określającą, czy struktura [Color](./) reprezentuje nazwany kolor lub członek wyliczenia KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Zwraca nazwę koloru reprezentowanego przez bieżący obiekt. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF800080. |
| int [get_R](./get_r/)() const | Zwraca wartość komponentu czerwonego koloru reprezentowanego przez bieżący obiekt. |
| static [Color](./) [get_Red](./get_red/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Zwraca kolor, którego wartość ARGB w notacji szesnastkowej to #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Zwraca komponentę jasności koloru reprezentowanego przez bieżący obiekt. |
| int [GetHashCode](./gethashcode/)() const | Zwraca kod skrótu (hash) bieżącego obiektu. |
| **float** [GetHue](./gethue/)() | Zwraca wartość odcienia (Hue) w modelu HSB, w stopniach, dla koloru reprezentowanego przez bieżący obiekt. |
| **float** [GetSaturation](./getsaturation/)() | Zwraca nasycenie (Saturation) w modelu HSB dla koloru reprezentowanego przez bieżący obiekt. |
| **bool** [IsNull](./isnull/)() const | Zawsze zwraca fałsz. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Zawsze zwraca prawdę. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Określa, czy bieżący i podany obiekt [Color](./) reprezentują różne kolory. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Zawsze zwraca fałsz. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Określa, czy bieżący i podany obiekt [Color](./) reprezentują ten sam kolor. |
| int [ToArgb](./toargb/)() const | Zwraca 32-bitową wartość ARGB koloru reprezentowanego przez bieżący obiekt. |
| [String](../../system/string/) [ToString](./tostring/)() const | Zwraca tekstową reprezentację bieżącego obiektu. |

## Pola

| Pole | Opis |
| --- | --- |
| static [Empty](./empty/) | „pusta” instancja klasy [Color](./), czyli instancja, która nie reprezentuje żadnego koloru. |

## Zobacz także

* Przestrzeń nazw [System::Drawing](../)
* Biblioteka [Aspose.Slides](../../)