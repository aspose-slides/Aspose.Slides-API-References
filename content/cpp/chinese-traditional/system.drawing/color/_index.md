---
title: Color
second_title: Aspose.Slides for C++ API 參考
description: "代表一種顏色。此類型應在堆疊上分配，並以值或參考傳遞給函式。絕不要使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 53
url: /zh-hant/system.drawing/color/
---
## Color 類別

表示一種顏色。此型別應在堆疊上分配，並以值或參考傳遞給函式。絕不要使用 [System::SmartPtr](../../system/smartptr/) 類別來管理此型別的物件。

```cpp
class Color
```

## 方法

| 方法 | 說明 |
| --- | --- |
|  [Color](./color/)() | 建構一個「空」的 [Color](./) 類別實例，該實例不代表任何顏色。 |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | 判斷目前的物件與指定的 [Color](./) 物件是否表示相同的顏色。 |
| static [Color](./) [FromArgb](./fromargb/)(int) | 建構一個 [Color](./) 類別實例，該實例表示指定的顏色。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | 建構一個 [Color](./) 類別實例，該實例表示指定的顏色。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | 建構一個 [Color](./) 類別實例，該實例表示指定的顏色，且 Alpha 成分設定為 0xFF。 |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | 建構一個 [Color](./) 類別實例，該實例表示指定的顏色。 |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | 建構一個 [Color](./) 類別實例，該實例表示指定的已知顏色。 |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | 建構一個 [Color](./) 類別實例，該實例表示具有指定名稱的顏色。 |
| int [get_A](./get_a/)() const | 傳回目前物件所代表顏色之 Alpha 成分的值。 |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF0F8FF。 |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFAEBD7。 |
| static [Color](./) [get_Aqua](./get_aqua/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00FFFF。 |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF7FFFD4。 |
| static [Color](./) [get_Azure](./get_azure/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF0FFFF。 |
| int [get_B](./get_b/)() const | 傳回目前物件所代表顏色之藍色成分的值。 |
| static [Color](./) [get_Beige](./get_beige/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF5F5DC。 |
| static [Color](./) [get_Bisque](./get_bisque/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFE4C4。 |
| static [Color](./) [get_Black](./get_black/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF000000。 |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFEBCD。 |
| static [Color](./) [get_Blue](./get_blue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF0000FF。 |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF8A2BE2。 |
| static [Color](./) [get_Brown](./get_brown/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFA52A2A。 |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDEB887。 |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF5F9EA0。 |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF7FFF00。 |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFD2691E。 |
| static [Color](./) [get_Coral](./get_coral/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF7F50。 |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF6495ED。 |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFF8DC。 |
| static [Color](./) [get_Crimson](./get_crimson/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDC143C。 |
| static [Color](./) [get_Cyan](./get_cyan/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00FFFF。 |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00008B。 |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF008B8B。 |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFB8860B。 |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFA9A9A9。 |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF006400。 |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFBDB76B。 |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF8B008B。 |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF556B2F。 |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF8C00。 |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF9932CC。 |
| static [Color](./) [get_DarkRed](./get_darkred/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF8B0000。 |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFE9967A。 |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF8FBC8F。 |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF483D8B。 |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF2F4F4F。 |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00CED1。 |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF9400D3。 |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF1493。 |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00BFFF。 |
| static [Color](./) [get_DimGray](./get_dimgray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF696969。 |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF1E90FF。 |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFB22222。 |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFAF0。 |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF228B22。 |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF00FF。 |
| int [get_G](./get_g/)() const | 傳回目前物件所代表顏色之綠色成分的值。 |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDCDCDC。 |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF8F8FF。 |
| static [Color](./) [get_Gold](./get_gold/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFD700。 |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDAA520。 |
| static [Color](./) [get_Gray](./get_gray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF808080。 |
| static [Color](./) [get_Green](./get_green/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF008000。 |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFADFF2F。 |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF0FFF0。 |
| static [Color](./) [get_HotPink](./get_hotpink/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF69B4。 |
| static [Color](./) [get_IndianRed](./get_indianred/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFCD5C5C。 |
| static [Color](./) [get_Indigo](./get_indigo/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF4B0082。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 傳回一個值，指示目前的物件是否為「空」──即不代表任何顏色。 |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | 傳回一個值，用以判斷 [Color](./) 結構是否代表具名顏色或 KnownColor 列舉的成員。 |
| static [Color](./) [get_Ivory](./get_ivory/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFFF0。 |
| static [Color](./) [get_Khaki](./get_khaki/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF0E68C。 |
| static [Color](./) [get_Lavender](./get_lavender/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFE6E6FA。 |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFF0F5。 |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF7CFC00。 |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFACD。 |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFADD8E6。 |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF08080。 |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFE0FFFF。 |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFAFAD2。 |
| static [Color](./) [get_LightGray](./get_lightgray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFD3D3D3。 |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF90EE90。 |
| static [Color](./) [get_LightPink](./get_lightpink/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFB6C1。 |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFA07A。 |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF20B2AA。 |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF87CEFA。 |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF778899。 |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFB0C4DE。 |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFFE0。 |
| static [Color](./) [get_Lime](./get_lime/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00FF00。 |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF32CD32。 |
| static [Color](./) [get_Linen](./get_linen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFAF0E6。 |
| static [Color](./) [get_Magenta](./get_magenta/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF00FF。 |
| static [Color](./) [get_Maroon](./get_maroon/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF800000。 |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF66CDAA。 |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF0000CD。 |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFBA55D3。 |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF9370DB。 |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF3CB371。 |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF7B68EE。 |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00FA9A。 |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF48D1CC。 |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFC71585。 |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF191970。 |
| static [Color](./) [get_MintCream](./get_mintcream/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF5FFFA。 |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFE4E1。 |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFE4B5。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 傳回目前物件所代表顏色的名稱。 |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFDEAD。 |
| static [Color](./) [get_Navy](./get_navy/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF000080。 |
| static [Color](./) [get_OldLace](./get_oldlace/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFDF5E6。 |
| static [Color](./) [get_Olive](./get_olive/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF808000。 |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF6B8E23。 |
| static [Color](./) [get_Orange](./get_orange/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFA500。 |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF4500。 |
| static [Color](./) [get_Orchid](./get_orchid/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDA70D6。 |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFEEE8AA。 |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF98FB98。 |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFAFEEEE。 |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDB7093。 |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFEFD5。 |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFDAB9。 |
| static [Color](./) [get_Peru](./get_peru/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFCD853F。 |
| static [Color](./) [get_Pink](./get_pink/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFC0CB。 |
| static [Color](./) [get_Plum](./get_plum/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFDDA0DD。 |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFB0E0E6。 |
| static [Color](./) [get_Purple](./get_purple/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF800080。 |
| int [get_R](./get_r/)() const | 傳回目前物件所代表顏色之紅色成分的值。 |
| static [Color](./) [get_Red](./get_red/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF0000。 |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFBC8F8F。 |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF4169E1。 |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF8B4513。 |
| static [Color](./) [get_Salmon](./get_salmon/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFA8072。 |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF4A460。 |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF2E8B57。 |
| static [Color](./) [get_SeaShell](./get_seashell/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFF5EE。 |
| static [Color](./) [get_Sienna](./get_sienna/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFA0522D。 |
| static [Color](./) [get_Silver](./get_silver/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFC0C0C0。 |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF87CEEB。 |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF6A5ACD。 |
| static [Color](./) [get_SlateGray](./get_slategray/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF708090。 |
| static [Color](./) [get_Snow](./get_snow/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFAFA。 |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF00FF7F。 |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF4682B4。 |
| static [Color](./) [get_Tan](./get_tan/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFD2B48C。 |
| static [Color](./) [get_Teal](./get_teal/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF008080。 |
| static [Color](./) [get_Thistle](./get_thistle/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFD8BFD8。 |
| static [Color](./) [get_Tomato](./get_tomato/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFF6347。 |
| static [Color](./) [get_Transparent](./get_transparent/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #00FFFFFF。 |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF40E0D0。 |
| static [Color](./) [get_Violet](./get_violet/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFEE82EE。 |
| static [Color](./) [get_Wheat](./get_wheat/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF5DEB3。 |
| static [Color](./) [get_White](./get_white/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFFFF。 |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFF5F5F5。 |
| static [Color](./) [get_Yellow](./get_yellow/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FFFFFF00。 |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | 傳回一個顏色，其 ARGB 值（十六進位表示）為 #FF9ACD32。 |
| **float** [GetBrightness](./getbrightness/)() | 傳回目前物件所代表顏色的亮度成分。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| **float** [GetHue](./gethue/)() | 傳回目前物件所代表顏色的 HSB 色相（以度為單位）。 |
| **float** [GetSaturation](./getsaturation/)() | 傳回目前物件所代表顏色的 HSB 飽和度。 |
| **bool** [IsNull](./isnull/)() const | 永遠傳回 false。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 永遠傳回 true。 |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | 判斷目前的物件與指定的 [Color](./) 物件是否為不同的顏色。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 永遠傳回 false。 |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | 判斷目前的物件與指定的 [Color](./) 物件是否為相同的顏色。 |
| int [ToArgb](./toargb/)() const | 傳回目前物件所代表顏色的 32 位元 ARGB 值。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 傳回目前物件的字串表示形式。 |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | 靜態 [Color](./) 類別的「空」實例，即不代表任何顏色的實例。 |

## 另請參閱

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)