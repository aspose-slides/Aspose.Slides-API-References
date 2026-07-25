---
title: Color
second_title: Aspose.Slides for C++ API リファレンス
description: "色を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。System::SmartPtr クラスを使用してこの型のオブジェクトを管理しないでください。"
type: docs
weight: 53
url: /ja/system.drawing/color/
---
## Color クラス


任意の色を表します。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。[System::SmartPtr](../../system/smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class Color
```

## メソッド

| Method | Description |
| --- | --- |
|  [Color](./color/)() | [Color](./) クラスの「空」インスタンスを構築し、色を表しません。 |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | 現在のオブジェクトと指定された [Color](./) オブジェクトが同じ色を表すかどうかを判定します。 |
| static [Color](./) [FromArgb](./fromargb/)(int) | 指定された色を表す [Color](./) クラスのインスタンスを構築します。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | 指定された色を表す [Color](./) クラスのインスタンスを構築します。 |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | アルファ成分が 0xFF に設定された指定された色を表す [Color](./) クラスのインスタンスを構築します。 |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | 指定された色を表す [Color](./) クラスのインスタンスを構築します。 |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | 指定された既知の色を表す [Color](./) クラスのインスタンスを構築します。 |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | 指定された名前の色を表す [Color](./) クラスのインスタンスを構築します。 |
| int [get_A](./get_a/)() const | 現在のオブジェクトが表す色のアルファ成分の値を返します。 |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | ARGB 値が十六進表記で #FFF0F8FF の色を返します。 |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | ARGB 値が十六進表記で #FFFAEBD7 の色を返します。 |
| static [Color](./) [get_Aqua](./get_aqua/)() | ARGB 値が十六進表記で #FF00FFFF の色を返します。 |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | ARGB 値が十六進表記で #FF7FFFD4 の色を返します。 |
| static [Color](./) [get_Azure](./get_azure/)() | ARGB 値が十六進表記で #FFF0FFFF の色を返します。 |
| int [get_B](./get_b/)() const | 現在のオブジェクトが表す色の青成分の値を返します。 |
| static [Color](./) [get_Beige](./get_beige/)() | ARGB 値が十六進表記で #FFF5F5DC の色を返します。 |
| static [Color](./) [get_Bisque](./get_bisque/)() | ARGB 値が十六進表記で #FFFFE4C4 の色を返します。 |
| static [Color](./) [get_Black](./get_black/)() | ARGB 値が十六進表記で #FF000000 の色を返します。 |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | ARGB 値が十六進表記で #FFFFEBCD の色を返します。 |
| static [Color](./) [get_Blue](./get_blue/)() | ARGB 値が十六進表記で #FF0000FF の色を返します。 |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | ARGB 値が十六進表記で #FF8A2BE2 の色を返します。 |
| static [Color](./) [get_Brown](./get_brown/)() | ARGB 値が十六進表記で #FFA52A2A の色を返します。 |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | ARGB 値が十六進表記で #FFDEB887 の色を返します。 |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | ARGB 値が十六進表記で #FF5F9EA0 の色を返します。 |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | ARGB 値が十六進表記で #FF7FFF00 の色を返します。 |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | ARGB 値が十六進表記で #FFD2691E の色を返します。 |
| static [Color](./) [get_Coral](./get_coral/)() | ARGB 値が十六進表記で #FFFF7F50 の色を返します。 |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | ARGB 値が十六進表記で #FF6495ED の色を返します。 |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | ARGB 値が十六進表記で #FFFFF8DC の色を返します。 |
| static [Color](./) [get_Crimson](./get_crimson/)() | ARGB 値が十六進表記で #FFDC143C の色を返します。 |
| static [Color](./) [get_Cyan](./get_cyan/)() | ARGB 値が十六進表記で #FF00FFFF の色を返します。 |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | ARGB 値が十六進表記で #FF00008B の色を返します。 |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | ARGB 値が十六進表記で #FF008B8B の色を返します。 |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | ARGB 値が十六進表記で #FFB8860B の色を返します。 |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | ARGB 値が十六進表記で #FFA9A9A9 の色を返します。 |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | ARGB 値が十六進表記で #FF006400 の色を返します。 |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | ARGB 値が十六進表記で #FFBDB76B の色を返します。 |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | ARGB 値が十六進表記で #FF8B008B の色を返します。 |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | ARGB 値が十六進表記で #FF556B2F の色を返します。 |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | ARGB 値が十六進表記で #FFFF8C00 の色を返します。 |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | ARGB 値が十六進表記で #FF9932CC の色を返します。 |
| static [Color](./) [get_DarkRed](./get_darkred/)() | ARGB 値が十六進表記で #FF8B0000 の色を返します。 |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | ARGB 値が十六進表記で #FFE9967A の色を返します。 |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | ARGB 値が十六進表記で #FF8FBC8F の色を返します。 |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | ARGB 値が十六進表記で #FF483D8B の色を返します。 |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | ARGB 値が十六進表記で #FF2F4F4F の色を返します。 |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | ARGB 値が十六進表記で #FF00CED1 の色を返します。 |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | ARGB 値が十六進表記で #FF9400D3 の色を返します。 |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | ARGB 値が十六進表記で #FFFF1493 の色を返します。 |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | ARGB 値が十六進表記で #FF00BFFF の色を返します。 |
| static [Color](./) [get_DimGray](./get_dimgray/)() | ARGB 値が十六進表記で #FF696969 の色を返します。 |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | ARGB 値が十六進表記で #FF1E90FF の色を返します。 |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | ARGB 値が十六進表記で #FFB22222 の色を返します。 |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | ARGB 値が十六進表記で #FFFFFAF0 の色を返します。 |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | ARGB 値が十六進表記で #FF228B22 の色を返します。 |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | ARGB 値が十六進表記で #FFFF00FF の色を返します。 |
| int [get_G](./get_g/)() const | 現在のオブジェクトが表す色の緑成分の値を返します。 |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | ARGB 値が十六進表記で #FFDCDCDC の色を返します。 |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | ARGB 値が十六進表記で #FFF8F8FF の色を返します。 |
| static [Color](./) [get_Gold](./get_gold/)() | ARGB 値が十六進表記で #FFFFD700 の色を返します。 |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | ARGB 値が十六進表記で #FFDAA520 の色を返します。 |
| static [Color](./) [get_Gray](./get_gray/)() | ARGB 値が十六進表記で #FF808080 の色を返します。 |
| static [Color](./) [get_Green](./get_green/)() | ARGB 値が十六進表記で #FF008000 の色を返します。 |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | ARGB 値が十六進表記で #FFADFF2F の色を返します。 |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | ARGB 値が十六進表記で #FFF0FFF0 の色を返します。 |
| static [Color](./) [get_HotPink](./get_hotpink/)() | ARGB 値が十六進表記で #FFFF69B4 の色を返します。 |
| static [Color](./) [get_IndianRed](./get_indianred/)() | ARGB 値が十六進表記で #FFCD5C5C の色を返します。 |
| static [Color](./) [get_Indigo](./get_indigo/)() | ARGB 値が十六進表記で #FF4B0082 の色を返します。 |
| **bool** [get_IsEmpty](./get_isempty/)() const | 現在のオブジェクトが「空」かどうか（色を表さないか）を示す値を返します。 |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | [Color](./) 構造体が名前付きの色を表すか、KnownColor 列挙型のメンバーかを判定する値を返します。 |
| static [Color](./) [get_Ivory](./get_ivory/)() | ARGB 値が十六進表記で #FFFFFFF0 の色を返します。 |
| static [Color](./) [get_Khaki](./get_khaki/)() | ARGB 値が十六進表記で #FFF0E68C の色を返します。 |
| static [Color](./) [get_Lavender](./get_lavender/)() | ARGB 値が十六進表記で #FFE6E6FA の色を返します。 |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | ARGB 値が十六進表記で #FFFFF0F5 の色を返します。 |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | ARGB 値が十六進表記で #FF7CFC00 の色を返します。 |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | ARGB 値が十六進表記で #FFFFFACD の色を返します。 |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | ARGB 値が十六進表記で #FFADD8E6 の色を返します。 |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | ARGB 値が十六進表記で #FFF08080 の色を返します。 |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | ARGB 値が十六進表記で #FFE0FFFF の色を返します。 |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | ARGB 値が十六進表記で #FFFAFAD2 の色を返します。 |
| static [Color](./) [get_LightGray](./get_lightgray/)() | ARGB 値が十六進表記で #FFD3D3D3 の色を返します。 |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | ARGB 値が十六進表記で #FF90EE90 の色を返します。 |
| static [Color](./) [get_LightPink](./get_lightpink/)() | ARGB 値が十六進表記で #FFFFB6C1 の色を返します。 |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | ARGB 値が十六進表記で #FFFFA07A の色を返します。 |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | ARGB 値が十六進表記で #FF20B2AA の色を返します。 |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | ARGB 値が十六進表記で #FF87CEFA の色を返します。 |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | ARGB 値が十六進表記で #FF778899 の色を返します。 |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | ARGB 値が十六進表記で #FFB0C4DE の色を返します。 |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | ARGB 値が十六進表記で #FFFFFFE0 の色を返します。 |
| static [Color](./) [get_Lime](./get_lime/)() | ARGB 値が十六進表記で #FF00FF00 の色を返します。 |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | ARGB 値が十六進表記で #FF32CD32 の色を返します。 |
| static [Color](./) [get_Linen](./get_linen/)() | ARGB 値が十六進表記で #FFFAF0E6 の色を返します。 |
| static [Color](./) [get_Magenta](./get_magenta/)() | ARGB 値が十六進表記で #FFFF00FF の色を返します。 |
| static [Color](./) [get_Maroon](./get_maroon/)() | ARGB 値が十六進表記で #FF800000 の色を返します。 |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | ARGB 値が十六進表記で #FF66CDAA の色を返します。 |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | ARGB 値が十六進表記で #FF0000CD の色を返します。 |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | ARGB 値が十六進表記で #FFBA55D3 の色を返します。 |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | ARGB 値が十六進表記で #FF9370DB の色を返します。 |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | ARGB 値が十六進表記で #FF3CB371 の色を返します。 |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | ARGB 値が十六進表記で #FF7B68EE の色を返します。 |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | ARGB 値が十六進表記で #FF00FA9A の色を返します。 |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | ARGB 値が十六進表記で #FF48D1CC の色を返します。 |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | ARGB 値が十六進表記で #FFC71585 の色を返します。 |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | ARGB 値が十六進表記で #FF191970 の色を返します。 |
| static [Color](./) [get_MintCream](./get_mintcream/)() | ARGB 値が十六進表記で #FFF5FFFA の色を返します。 |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | ARGB 値が十六進表記で #FFFFE4E1 の色を返します。 |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | ARGB 値が十六進表記で #FFFFE4B5 の色を返します。 |
| [String](../../system/string/) [get_Name](./get_name/)() const | 現在のオブジェクトが表す色の名前を返します。 |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | ARGB 値が十六進表記で #FFFFDEAD の色を返します。 |
| static [Color](./) [get_Navy](./get_navy/)() | ARGB 値が十六進表記で #FF000080 の色を返します。 |
| static [Color](./) [get_OldLace](./get_oldlace/)() | ARGB 値が十六進表記で #FFFDF5E6 の色を返します。 |
| static [Color](./) [get_Olive](./get_olive/)() | ARGB 値が十六進表記で #FF808000 の色を返します。 |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | ARGB 値が十六進表記で #FF6B8E23 の色を返します。 |
| static [Color](./) [get_Orange](./get_orange/)() | ARGB 値が十六進表記で #FFFFA500 の色を返します。 |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | ARGB 値が十六進表記で #FFFF4500 の色を返します。 |
| static [Color](./) [get_Orchid](./get_orchid/)() | ARGB 値が十六進表記で #FFDA70D6 の色を返します。 |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | ARGB 値が十六進表記で #FFEEE8AA の色を返します。 |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | ARGB 値が十六進表記で #FF98FB98 の色を返します。 |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | ARGB 値が十六進表記で #FFAFEEEE の色を返します。 |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | ARGB 値が十六進表記で #FFDB7093 の色を返します。 |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | ARGB 値が十六進表記で #FFFFEFD5 の色を返します。 |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | ARGB 値が十六進表記で #FFFFDAB9 の色を返します。 |
| static [Color](./) [get_Peru](./get_peru/)() | ARGB 値が十六進表記で #FFCD853F の色を返します。 |
| static [Color](./) [get_Pink](./get_pink/)() | ARGB 値が十六進表記で #FFFFC0CB の色を返します。 |
| static [Color](./) [get_Plum](./get_plum/)() | ARGB 値が十六進表記で #FFDDA0DD の色を返します。 |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | ARGB 値が十六進表記で #FFB0E0E6 の色を返します。 |
| static [Color](./) [get_Purple](./get_purple/)() | ARGB 値が十六進表記で #FF800080 の色を返します。 |
| int [get_R](./get_r/)() const | 現在のオブジェクトが表す色の赤成分の値を返します。 |
| static [Color](./) [get_Red](./get_red/)() | ARGB 値が十六進表記で #FFFF0000 の色を返します。 |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | ARGB 値が十六進表記で #FFBC8F8F の色を返します。 |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | ARGB 値が十六進表記で #FF4169E1 の色を返します。 |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | ARGB 値が十六進表記で #FF8B4513 の色を返します。 |
| static [Color](./) [get_Salmon](./get_salmon/)() | ARGB 値が十六進表記で #FFFA8072 の色を返します。 |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | ARGB 値が十六進表記で #FFF4A460 の色を返します。 |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | ARGB 値が十六進表記で #FF2E8B57 の色を返します。 |
| static [Color](./) [get_SeaShell](./get_seashell/)() | ARGB 値が十六進表記で #FFFFF5EE の色を返します。 |
| static [Color](./) [get_Sienna](./get_sienna/)() | ARGB 値が十六進表記で #FFA0522D の色を返します。 |
| static [Color](./) [get_Silver](./get_silver/)() | ARGB 値が十六進表記で #FFC0C0C0 の色を返します。 |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | ARGB 値が十六進表記で #FF87CEEB の色を返します。 |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | ARGB 値が十六進表記で #FF6A5ACD の色を返します。 |
| static [Color](./) [get_SlateGray](./get_slategray/)() | ARGB 値が十六進表記で #FF708090 の色を返します。 |
| static [Color](./) [get_Snow](./get_snow/)() | ARGB 値が十六進表記で #FFFFFAFA の色を返します。 |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | ARGB 値が十六進表記で #FF00FF7F の色を返します。 |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | ARGB 値が十六進表記で #FF4682B4 の色を返します。 |
| static [Color](./) [get_Tan](./get_tan/)() | ARGB 値が十六進表記で #FFD2B48C の色を返します。 |
| static [Color](./) [get_Teal](./get_teal/)() | ARGB 値が十六進表記で #FF008080 の色を返します。 |
| static [Color](./) [get_Thistle](./get_thistle/)() | ARGB 値が十六進表記で #FFD8BFD8 の色を返します。 |
| static [Color](./) [get_Tomato](./get_tomato/)() | ARGB 値が十六進表記で #FFFF6347 の色を返します。 |
| static [Color](./) [get_Transparent](./get_transparent/)() | ARGB 値が十六進表記で #00FFFFFF の色を返します。 |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | ARGB 値が十六進表記で #FF40E0D0 の色を返します。 |
| static [Color](./) [get_Violet](./get_violet/)() | ARGB 値が十六進表記で #FFEE82EE の色を返します。 |
| static [Color](./) [get_Wheat](./get_wheat/)() | ARGB 値が十六進表記で #FFF5DEB3 の色を返します。 |
| static [Color](./) [get_White](./get_white/)() | ARGB 値が十六進表記で #FFFFFFFF の色を返します。 |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | ARGB 値が十六進表記で #FFF5F5F5 の色を返します。 |
| static [Color](./) [get_Yellow](./get_yellow/)() | ARGB 値が十六進表記で #FFFFFF00 の色を返します。 |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | ARGB 値が十六進表記で #FF9ACD32 の色を返します。 |
| **float** [GetBrightness](./getbrightness/)() | 現在のオブジェクトが表す色の明度成分を返します。 |
| int [GetHashCode](./gethashcode/)() const | 現在のオブジェクトのハッシュコードを返します。 |
| **float** [GetHue](./gethue/)() | 現在のオブジェクトが表す色の Hue-Saturation-Brightness (HSB) の Hue 値（度）を返します。 |
| **float** [GetSaturation](./getsaturation/)() | 現在のオブジェクトが表す色の Hue-Saturation\-Brightness (HSB) の Saturation を返します。 |
| **bool** [IsNull](./isnull/)() const | 常に false を返します。 |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 常に true を返します。 |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | 現在のオブジェクトと指定された [Color](./) オブジェクトが異なる色を表すかどうかを判定します。 |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 常に false を返します。 |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | 現在のオブジェクトと指定された [Color](./) オブジェクトが同じ色を表すかどうかを判定します。 |
| int [ToArgb](./toargb/)() const | 現在のオブジェクトが表す色の 32 ビット ARGB 値を返します。 |
| [String](../../system/string/) [ToString](./tostring/)() const | 現在のオブジェクトの文字列表現を返します。 |
## フィールド

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | [Color](./) クラスの「空」インスタンス、すなわち色を表さないインスタンスです。 |
## 参照

* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)