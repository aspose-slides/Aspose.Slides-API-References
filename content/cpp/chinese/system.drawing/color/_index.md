---
title: Color
second_title: Aspose.Slides for C++ API 参考
description: "表示一种颜色。此类型应在栈上分配，并通过值或引用传递给函数。永远不要使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 53
url: /zh/system.drawing/color/
---
## Color 类

表示一种颜色。此类型应在栈上分配，并通过值或引用传递给函数。永远不要使用 [System::SmartPtr](../../system/smartptr/) 类来管理此类型的对象。

```cpp
class Color
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [Color](./color/)() | 构造一个不表示任何颜色的 [Color](./) 类的 “empty” 实例。 |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | 确定当前对象和指定的 [Color](./) 对象是否表示相同的颜色。 |
| static [Color](./) [FromArgb](./fromargb/)(int) | 构造 [Color](./) 类的实例，表示指定的颜色。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | 构造 [Color](./) 类的实例，表示指定的颜色。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | 构造 [Color](./) 类的实例，表示指定的颜色，alpha 分量设置为 0xFF。 |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | 构造 [Color](./) 类的实例，表示指定的颜色。 |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | 构造 [Color](./) 类的实例，表示指定的已知颜色。 |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | 构造 [Color](./) 类的实例，表示具有指定名称的颜色。 |
| int [get_A](./get_a/)() const | 返回当前对象表示的颜色的 alpha 分量的值。 |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | 返回十六进制表示为 #FFF0F8FF 的颜色。 |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | 返回十六进制表示为 #FFFAEBD7 的颜色。 |
| static [Color](./) [get_Aqua](./get_aqua/)() | 返回十六进制表示为 #FF00FFFF 的颜色。 |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | 返回十六进制表示为 #FF7FFFD4 的颜色。 |
| static [Color](./) [get_Azure](./get_azure/)() | 返回十六进制表示为 #FFF0FFFF 的颜色。 |
| int [get_B](./get_b/)() const | 返回当前对象表示的颜色的蓝色分量的值。 |
| static [Color](./) [get_Beige](./get_beige/)() | 返回十六进制表示为 #FFF5F5DC 的颜色。 |
| static [Color](./) [get_Bisque](./get_bisque/)() | 返回十六进制表示为 #FFFFE4C4 的颜色。 |
| static [Color](./) [get_Black](./get_black/)() | 返回十六进制表示为 #FF000000 的颜色。 |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | 返回十六进制表示为 #FFFFEBCD 的颜色。 |
| static [Color](./) [get_Blue](./get_blue/)() | 返回十六进制表示为 #FF0000FF 的颜色。 |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | 返回十六进制表示为 #FF8A2BE2 的颜色。 |
| static [Color](./) [get_Brown](./get_brown/)() | 返回十六进制表示为 #FFA52A2A 的颜色。 |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | 返回十六进制表示为 #FFDEB887 的颜色。 |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | 返回十六进制表示为 #FF5F9EA0 的颜色。 |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | 返回十六进制表示为 #FF7FFF00 的颜色。 |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | 返回十六进制表示为 #FFD2691E 的颜色。 |
| static [Color](./) [get_Coral](./get_coral/)() | 返回十六进制表示为 #FFFF7F50 的颜色。 |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | 返回十六进制表示为 #FF6495ED 的颜色。 |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | 返回十六进制表示为 #FFFFF8DC 的颜色。 |
| static [Color](./) [get_Crimson](./get_crimson/)() | 返回十六进制表示为 #FFDC143C 的颜色。 |
| static [Color](./) [get_Cyan](./get_cyan/)() | 返回十六进制表示为 #FF00FFFF 的颜色。 |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | 返回十六进制表示为 #FF00008B 的颜色。 |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | 返回十六进制表示为 #FF008B8B 的颜色。 |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | 返回十六进制表示为 #FFB8860B 的颜色。 |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | 返回十六进制表示为 #FFA9A9A9 的颜色。 |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | 返回十六进制表示为 #FF006400 的颜色。 |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | 返回十六进制表示为 #FFBDB76B 的颜色。 |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | 返回十六进制表示为 #FF8B008B 的颜色。 |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | 返回十六进制表示为 #FF556B2F 的颜色。 |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | 返回十六进制表示为 #FFFF8C00 的颜色。 |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | 返回十六进制表示为 #FF9932CC 的颜色。 |
| static [Color](./) [get_DarkRed](./get_darkred/)() | 返回十六进制表示为 #FF8B0000 的颜色。 |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | 返回十六进制表示为 #FFE9967A 的颜色。 |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | 返回十六进制表示为 #FF8FBC8F 的颜色。 |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | 返回十六进制表示为 #FF483D8B 的颜色。 |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | 返回十六进制表示为 #FF2F4F4F 的颜色。 |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | 返回十六进制表示为 #FF00CED1 的颜色。 |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | 返回十六进制表示为 #FF9400D3 的颜色。 |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | 返回十六进制表示为 #FFFF1493 的颜色。 |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | 返回十六进制表示为 #FF00BFFF 的颜色。 |
| static [Color](./) [get_DimGray](./get_dimgray/)() | 返回十六进制表示为 #FF696969 的颜色。 |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | 返回十六进制表示为 #FF1E90FF 的颜色。 |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | 返回十六进制表示为 #FFB22222 的颜色。 |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | 返回十六进制表示为 #FFFFFAF0 的颜色。 |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | 返回十六进制表示为 #FF228B22 的颜色。 |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | 返回十六进制表示为 #FFFF00FF 的颜色。 |
| int [get_G](./get_g/)() const | 返回当前对象表示的颜色的绿色分量的值。 |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | 返回十六进制表示为 #FFDCDCDC 的颜色。 |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | 返回十六进制表示为 #FFF8F8FF 的颜色。 |
| static [Color](./) [get_Gold](./get_gold/)() | 返回十六进制表示为 #FFFFD700 的颜色。 |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | 返回十六进制表示为 #FFDAA520 的颜色。 |
| static [Color](./) [get_Gray](./get_gray/)() | 返回十六进制表示为 #FF808080 的颜色。 |
| static [Color](./) [get_Green](./get_green/)() | 返回十六进制表示为 #FF008000 的颜色。 |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | 返回十六进制表示为 #FFADFF2F 的颜色。 |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | 返回十六进制表示为 #FFF0FFF0 的颜色。 |
| static [Color](./) [get_HotPink](./get_hotpink/)() | 返回十六进制表示为 #FFFF69B4 的颜色。 |
| static [Color](./) [get_IndianRed](./get_indianred/)() | 返回十六进制表示为 #FFCD5C5C 的颜色。 |
| static [Color](./) [get_Indigo](./get_indigo/)() | 返回十六进制表示为 #FF4B0082 的颜色。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 返回一个值，指示当前对象是否为 “empty”，即不表示任何颜色。 |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | 返回一个值，决定 [Color](./) 结构是表示命名颜色还是 KnownColor 枚举的成员。 |
| static [Color](./) [get_Ivory](./get_ivory/)() | 返回十六进制表示为 #FFFFFFF0 的颜色。 |
| static [Color](./) [get_Khaki](./get_khaki/)() | 返回十六进制表示为 #FFF0E68C 的颜色。 |
| static [Color](./) [get_Lavender](./get_lavender/)() | 返回十六进制表示为 #FFE6E6FA 的颜色。 |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | 返回十六进制表示为 #FFFFF0F5 的颜色。 |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | 返回十六进制表示为 #FF7CFC00 的颜色。 |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | 返回十六进制表示为 #FFFFFACD 的颜色。 |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | 返回十六进制表示为 #FFADD8E6 的颜色。 |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | 返回十六进制表示为 #FFF08080 的颜色。 |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | 返回十六进制表示为 #FFE0FFFF 的颜色。 |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | 返回十六进制表示为 #FFFAFAD2 的颜色。 |
| static [Color](./) [get_LightGray](./get_lightgray/)() | 返回十六进制表示为 #FFD3D3D3 的颜色。 |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | 返回十六进制表示为 #FF90EE90 的颜色。 |
| static [Color](./) [get_LightPink](./get_lightpink/)() | 返回十六进制表示为 #FFFFB6C1 的颜色。 |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | 返回十六进制表示为 #FFFFA07A 的颜色。 |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | 返回十六进制表示为 #FF20B2AA 的颜色。 |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | 返回十六进制表示为 #FF87CEFA 的颜色。 |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | 返回十六进制表示为 #FF778899 的颜色。 |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | 返回十六进制表示为 #FFB0C4DE 的颜色。 |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | 返回十六进制表示为 #FFFFFFE0 的颜色。 |
| static [Color](./) [get_Lime](./get_lime/)() | 返回十六进制表示为 #FF00FF00 的颜色。 |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | 返回十六进制表示为 #FF32CD32 的颜色。 |
| static [Color](./) [get_Linen](./get_linen/)() | 返回十六进制表示为 #FFFAF0E6 的颜色。 |
| static [Color](./) [get_Magenta](./get_magenta/)() | 返回十六进制表示为 #FFFF00FF 的颜色。 |
| static [Color](./) [get_Maroon](./get_maroon/)() | 返回十六进制表示为 #FF800000 的颜色。 |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | 返回十六进制表示为 #FF66CDAA 的颜色。 |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | 返回十六进制表示为 #FF0000CD 的颜色。 |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | 返回十六进制表示为 #FFBA55D3 的颜色。 |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | 返回十六进制表示为 #FF9370DB 的颜色。 |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | 返回十六进制表示为 #FF3CB371 的颜色。 |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | 返回十六进制表示为 #FF7B68EE 的颜色。 |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | 返回十六进制表示为 #FF00FA9A 的颜色。 |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | 返回十六进制表示为 #FF48D1CC 的颜色。 |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | 返回十六进制表示为 #FFC71585 的颜色。 |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | 返回十六进制表示为 #FF191970 的颜色。 |
| static [Color](./) [get_MintCream](./get_mintcream/)() | 返回十六进制表示为 #FFF5FFFA 的颜色。 |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | 返回十六进制表示为 #FFFFE4E1 的颜色。 |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | 返回十六进制表示为 #FFFFE4B5 的颜色。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 返回当前对象表示的颜色的名称。 |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | 返回十六进制表示为 #FFFFDEAD 的颜色。 |
| static [Color](./) [get_Navy](./get_navy/)() | 返回十六进制表示为 #FF000080 的颜色。 |
| static [Color](./) [get_OldLace](./get_oldlace/)() | 返回十六进制表示为 #FFFDF5E6 的颜色。 |
| static [Color](./) [get_Olive](./get_olive/)() | 返回十六进制表示为 #FF808000 的颜色。 |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | 返回十六进制表示为 #FF6B8E23 的颜色。 |
| static [Color](./) [get_Orange](./get_orange/)() | 返回十六进制表示为 #FFFFA500 的颜色。 |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | 返回十六进制表示为 #FFFF4500 的颜色。 |
| static [Color](./) [get_Orchid](./get_orchid/)() | 返回十六进制表示为 #FFDA70D6 的颜色。 |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | 返回十六进制表示为 #FFEEE8AA 的颜色。 |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | 返回十六进制表示为 #FF98FB98 的颜色。 |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | 返回十六进制表示为 #FFAFEEEE 的颜色。 |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | 返回十六进制表示为 #FFDB7093 的颜色。 |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | 返回十六进制表示为 #FFFFEFD5 的颜色。 |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | 返回十六进制表示为 #FFFFDAB9 的颜色。 |
| static [Color](./) [get_Peru](./get_peru/)() | 返回十六进制表示为 #FFCD853F 的颜色。 |
| static [Color](./) [get_Pink](./get_pink/)() | 返回十六进制表示为 #FFFFC0CB 的颜色。 |
| static [Color](./) [get_Plum](./get_plum/)() | 返回十六进制表示为 #FFDDA0DD 的颜色。 |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | 返回十六进制表示为 #FFB0E0E6 的颜色。 |
| static [Color](./) [get_Purple](./get_purple/)() | 返回十六进制表示为 #FF800080 的颜色。 |
| int [get_R](./get_r/)() const | 返回当前对象表示的颜色的红色分量的值。 |
| static [Color](./) [get_Red](./get_red/)() | 返回十六进制表示为 #FFFF0000 的颜色。 |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | 返回十六进制表示为 #FFBC8F8F 的颜色。 |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | 返回十六进制表示为 #FF4169E1 的颜色。 |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | 返回十六进制表示为 #FF8B4513 的颜色。 |
| static [Color](./) [get_Salmon](./get_salmon/)() | 返回十六进制表示为 #FFFA8072 的颜色。 |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | 返回十六进制表示为 #FFF4A460 的颜色。 |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | 返回十六进制表示为 #FF2E8B57 的颜色。 |
| static [Color](./) [get_SeaShell](./get_seashell/)() | 返回十六进制表示为 #FFFFF5EE 的颜色。 |
| static [Color](./) [get_Sienna](./get_sienna/)() | 返回十六进制表示为 #FFA0522D 的颜色。 |
| static [Color](./) [get_Silver](./get_silver/)() | 返回十六进制表示为 #FFC0C0C0 的颜色。 |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | 返回十六进制表示为 #FF87CEEB 的颜色。 |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | 返回十六进制表示为 #FF6A5ACD 的颜色。 |
| static [Color](./) [get_SlateGray](./get_slategray/)() | 返回十六进制表示为 #FF708090 的颜色。 |
| static [Color](./) [get_Snow](./get_snow/)() | 返回十六进制表示为 #FFFFFAFA 的颜色。 |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | 返回十六进制表示为 #FF00FF7F 的颜色。 |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | 返回十六进制表示为 #FF4682B4 的颜色。 |
| static [Color](./) [get_Tan](./get_tan/)() | 返回十六进制表示为 #FFD2B48C 的颜色。 |
| static [Color](./) [get_Teal](./get_teal/)() | 返回十六进制表示为 #FF008080 的颜色。 |
| static [Color](./) [get_Thistle](./get_thistle/)() | 返回十六进制表示为 #FFD8BFD8 的颜色。 |
| static [Color](./) [get_Tomato](./get_tomato/)() | 返回十六进制表示为 #FFFF6347 的颜色。 |
| static [Color](./) [get_Transparent](./get_transparent/)() | 返回十六进制表示为 #00FFFFFF 的颜色。 |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | 返回十六进制表示为 #FF40E0D0 的颜色。 |
| static [Color](./) [get_Violet](./get_violet/)() | 返回十六进制表示为 #FFEE82EE 的颜色。 |
| static [Color](./) [get_Wheat](./get_wheat/)() | 返回十六进制表示为 #FFF5DEB3 的颜色。 |
| static [Color](./) [get_White](./get_white/)() | 返回十六进制表示为 #FFFFFFFF 的颜色。 |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | 返回十六进制表示为 #FFF5F5F5 的颜色。 |
| static [Color](./) [get_Yellow](./get_yellow/)() | 返回十六进制表示为 #FFFFFF00 的颜色。 |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | 返回十六进制表示为 #FF9ACD32 的颜色。 |
| **float** [GetBrightness](./getbrightness/)() | 返回当前对象表示的颜色的亮度分量。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| **float** [GetHue](./gethue/)() | 返回当前对象表示的颜色的 HSB 色相值（以度为单位）。 |
| **float** [GetSaturation](./getsaturation/)() | 返回当前对象表示的颜色的 HSB 饱和度。 |
| **bool** [IsNull](./isnull/)() const | 始终返回 false。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 始终返回 true。 |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | 判断当前对象和指定的 [Color](./) 对象是否表示不同的颜色。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 始终返回 false。 |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | 判断当前对象和指定的 [Color](./) 对象是否表示相同的颜色。 |
| int [ToArgb](./toargb/)() const | 返回当前对象表示的颜色的 32 位 ARGB 值。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 返回当前对象的字符串表示。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | “empty” 实例的 [Color](./) 类，即不表示任何颜色的实例。 |

## 另见

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)