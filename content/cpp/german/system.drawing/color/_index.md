---
title: Color
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine Farbe dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr-Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 53
url: /de/system.drawing/color/
---
## Color Klasse

Stellt eine Farbe dar. Dieser Typ sollte auf dem Stack allokiert und an Funktionen per Wert oder per Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../../system/smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class Color
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  [Color](./color/)() | Konstruiert eine \"leere\" Instanz der [Color](./) Klasse, die keine Farbe darstellt. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Bestimmt, ob das aktuelle und das angegebene [Color](./) Objekt dieselbe Farbe darstellen. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Konstruiert eine Instanz der [Color](./) Klasse, die die angegebene Farbe darstellt. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Konstruiert eine Instanz der [Color](./) Klasse, die die angegebene Farbe darstellt. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Konstruiert eine Instanz der [Color](./) Klasse, die die angegebene Farbe mit Alpha-Komponente 0xFF darstellt. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Konstruiert eine Instanz der [Color](./) Klasse, die die angegebene Farbe darstellt. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Konstruiert eine Instanz der [Color](./) Klasse, die die angegebene bekannte Farbe darstellt. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Konstruiert eine Instanz der [Color](./) Klasse, die eine Farbe mit dem angegebenen Namen darstellt. |
| int [get_A](./get_a/)() const | Gibt den Wert der Alpha-Komponente der vom aktuellen Objekt dargestellten Farbe zurück. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFF0F8FF ist. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFAEBD7 ist. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF00FFFF ist. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF7FFFD4 ist. |
| static [Color](./) [get_Azure](./get_azure/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFF0FFFF ist. |
| int [get_B](./get_b/)() const | Gibt den Wert der blauen Komponente der vom aktuellen Objekt dargestellten Farbe zurück. |
| static [Color](./) [get_Beige](./get_beige/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFF5F5DC ist. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFFE4C4 ist. |
| static [Color](./) [get_Black](./get_black/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF000000 ist. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFFEBCD ist. |
| static [Color](./) [get_Blue](./get_blue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF0000FF ist. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF8A2BE2 ist. |
| static [Color](./) [get_Brown](./get_brown/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFA52A2A ist. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFDEB887 ist. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF5F9EA0 ist. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF7FFF00 ist. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFD2691E ist. |
| static [Color](./) [get_Coral](./get_coral/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFF7F50 ist. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF6495ED ist. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFFF8DC ist. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFDC143C ist. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF00FFFF ist. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF00008B ist. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF008B8B ist. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFB8860B ist. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFA9A9A9 ist. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF006400 ist. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFBDB76B ist. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF8B008B ist. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF556B2F ist. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFF8C00 ist. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF9932CC ist. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF8B0000 ist. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFE9967A ist. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF8FBC8F ist. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF483D8B ist. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF2F4F4F ist. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF00CED1 ist. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF9400D3 ist. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFF1493 ist. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF00BFFF ist. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF696969 ist. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF1E90FF ist. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFB22222 ist. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFFFAF0 ist. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FF228B22 ist. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFF00FF ist. |
| int [get_G](./get_g/)() const | Gibt den Wert der grünen Komponente der vom aktuellen Objekt dargestellten Farbe zurück. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFDCDCDC ist. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFF8F8FF ist. |
| static [Color](./) [get_Gold](./get_gold/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezimaler Notation #FFFFD700 ist. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFDAA520 ist. |
| static [Color](./) [get_Gray](./get_gray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF808080 ist. |
| static [Color](./) [get_Green](./get_green/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF008000 ist. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFADFF2F ist. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF0FFF0 ist. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFF69B4 ist. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFCD5C5C ist. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF4B0082 ist. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Gibt einen Wert zurück, der anzeigt, ob das aktuelle Objekt „leer“ ist, d.h. keine Farbe darstellt. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Gibt einen Wert zurück, der bestimmt, ob die [Color](./) Struktur eine benannte Farbe oder ein Mitglied der KnownColor-Aufzählung darstellt. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFFF0 ist. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF0E68C ist. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFE6E6FA ist. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFF0F5 ist. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF7CFC00 ist. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFACD ist. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFADD8E6 ist. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF08080 ist. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFE0FFFF ist. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFAFAD2 ist. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFD3D3D3 ist. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF90EE90 ist. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFB6C1 ist. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFA07A ist. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF20B2AA ist. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF87CEFA ist. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF778899 ist. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFB0C4DE ist. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFFE0 ist. |
| static [Color](./) [get_Lime](./get_lime/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF00FF00 ist. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF32CD32 ist. |
| static [Color](./) [get_Linen](./get_linen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFAF0E6 ist. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFF00FF ist. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF800000 ist. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF66CDAA ist. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF0000CD ist. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFBA55D3 ist. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF9370DB ist. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF3CB371 ist. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF7B68EE ist. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF00FA9A ist. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF48D1CC ist. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFC71585 ist. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF191970 ist. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF5FFFA ist. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFE4E1 ist. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFE4B5 ist. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Gibt den Namen der vom aktuellen Objekt dargestellten Farbe zurück. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFDEAD ist. |
| static [Color](./) [get_Navy](./get_navy/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF000080 ist. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFDF5E6 ist. |
| static [Color](./) [get_Olive](./get_olive/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF808000 ist. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF6B8E23 ist. |
| static [Color](./) [get_Orange](./get_orange/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFA500 ist. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFF4500 ist. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFDA70D6 ist. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFEEE8AA ist. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF98FB98 ist. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFAFEEEE ist. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFDB7093 ist. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFEFD5 ist. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFDAB9 ist. |
| static [Color](./) [get_Peru](./get_peru/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFCD853F ist. |
| static [Color](./) [get_Pink](./get_pink/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFC0CB ist. |
| static [Color](./) [get_Plum](./get_plum/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFDDA0DD ist. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFB0E0E6 ist. |
| static [Color](./) [get_Purple](./get_purple/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF800080 ist. |
| int [get_R](./get_r/)() const | Gibt den Wert der roten Komponente der vom aktuellen Objekt dargestellten Farbe zurück. |
| static [Color](./) [get_Red](./get_red/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFF0000 ist. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFBC8F8F ist. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF4169E1 ist. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF8B4513 ist. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFA8072 ist. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF4A460 ist. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF2E8B57 ist. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFF5EE ist. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFA0522D ist. |
| static [Color](./) [get_Silver](./get_silver/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFC0C0C0 ist. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF87CEEB ist. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF6A5ACD ist. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF708090 ist. |
| static [Color](./) [get_Snow](./get_snow/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFAFA ist. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF00FF7F ist. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF4682B4 ist. |
| static [Color](./) [get_Tan](./get_tan/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFD2B48C ist. |
| static [Color](./) [get_Teal](./get_teal/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF008080 ist. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFD8BFD8 ist. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFF6347 ist. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #00FFFFFF ist. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF40E0D0 ist. |
| static [Color](./) [get_Violet](./get_violet/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFEE82EE ist. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF5DEB3 ist. |
| static [Color](./) [get_White](./get_white/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFFFF ist. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFF5F5F5 ist. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FFFFFF00 ist. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Gibt eine Farbe zurück, deren ARGB-Wert in hexadezitaler Notation #FF9ACD32 ist. |
| **float** [GetBrightness](./getbrightness/)() | Gibt die Helligkeitskomponente der vom aktuellen Objekt dargestellten Farbe zurück. |
| int [GetHashCode](./gethashcode/)() const | Gibt den Hash-Code des aktuellen Objekts zurück. |
| **float** [GetHue](./gethue/)() | Gibt den Hue-Wert (Hue-Saturation-Brightness) in Grad für die vom aktuellen Objekt dargestellte Farbe zurück. |
| **float** [GetSaturation](./getsaturation/)() | Gibt die Saturation (Hue-Saturation-Brightness) für die vom aktuellen Objekt dargestellte Farbe zurück. |
| **bool** [IsNull](./isnull/)() const | Gibt immer false zurück. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Gibt immer true zurück. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Bestimmt, ob das aktuelle und das angegebene [Color](./) Objekt unterschiedliche Farben darstellen. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Gibt immer false zurück. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Bestimmt, ob das aktuelle und das angegebene [Color](./) Objekt dieselbe Farbe darstellen. |
| int [ToArgb](./toargb/)() const | Gibt einen 32-Bit-ARGB-Wert der vom aktuellen Objekt dargestellten Farbe zurück. |
| [String](../../system/string/) [ToString](./tostring/)() const | Gibt die String-Darstellung des aktuellen Objekts zurück. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| static [Empty](./empty/) | Eine \"leere\" Instanz der [Color](./) Klasse, d.h. eine Instanz, die keine Farbe darstellt. |
## Siehe auch

* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)