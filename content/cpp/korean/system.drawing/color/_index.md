---
title: Color
second_title: Aspose.Slides for C++ API 레퍼런스
description: "색을 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. 이 타입의 객체를 관리하기 위해 System::SmartPtr 클래스를 사용하지 마세요."
type: docs
weight: 53
url: /ko/system.drawing/color/
---
## Color 클래스

색을 나타냅니다. 이 타입은 스택에 할당하고 값이나 참조로 함수에 전달해야 합니다. [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 타입의 객체를 관리하지 마세요.

```cpp
class Color
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  [Color](./color/)() | 어떠한 색도 나타내지 않는 [Color](./) 클래스의 “빈” 인스턴스를 생성합니다. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | 현재 객체와 지정된 [Color](./) 객체가 같은 색을 나타내는지 확인합니다. |
| static [Color](./) [FromArgb](./fromargb/)(int) | 지정된 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | 지정된 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | 알파 구성 요소가 0xFF인 지정된 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | 지정된 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | 지정된 알려진 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | 지정된 이름을 가진 색을 나타내는 [Color](./) 클래스의 인스턴스를 생성합니다. |
| int [get_A](./get_a/)() const | 현재 객체가 나타내는 색의 알파 구성 요소 값을 반환합니다. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | ARGB 값이 16진수 표기법으로 #FFF0F8FF인 색을 반환합니다. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | ARGB 값이 16진수 표기법으로 #FFFAEBD7인 색을 반환합니다. |
| static [Color](./) [get_Aqua](./get_aqua/)() | ARGB 값이 16진수 표기법으로 #FF00FFFF인 색을 반환합니다. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | ARGB 값이 16진수 표기법으로 #FF7FFFD4인 색을 반환합니다. |
| static [Color](./) [get_Azure](./get_azure/)() | ARGB 값이 16진수 표기법으로 #FFF0FFFF인 색을 반환합니다. |
| int [get_B](./get_b/)() const | 현재 객체가 나타내는 색의 파란색 구성 요소 값을 반환합니다. |
| static [Color](./) [get_Beige](./get_beige/)() | ARGB 값이 16진수 표기법으로 #FFF5F5DC인 색을 반환합니다. |
| static [Color](./) [get_Bisque](./get_bisque/)() | ARGB 값이 16진수 표기법으로 #FFFFE4C4인 색을 반환합니다. |
| static [Color](./) [get_Black](./get_black/)() | ARGB 값이 16진수 표기법으로 #FF000000인 색을 반환합니다. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | ARGB 값이 16진수 표기법으로 #FFFFEBCD인 색을 반환합니다. |
| static [Color](./) [get_Blue](./get_blue/)() | ARGB 값이 16진수 표기법으로 #FF0000FF인 색을 반환합니다. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | ARGB 값이 16진수 표기법으로 #FF8A2BE2인 색을 반환합니다. |
| static [Color](./) [get_Brown](./get_brown/)() | ARGB 값이 16진수 표기법으로 #FFA52A2A인 색을 반환합니다. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | ARGB 값이 16진수 표기법으로 #FFDEB887인 색을 반환합니다. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | ARGB 값이 16진수 표기법으로 #FF5F9EA0인 색을 반환합니다. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | ARGB 값이 16진수 표기법으로 #FF7FFF00인 색을 반환합니다. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | ARGB 값이 16진수 표기법으로 #FFD2691E인 색을 반환합니다. |
| static [Color](./) [get_Coral](./get_coral/)() | ARGB 값이 16진수 표기법으로 #FFFF7F50인 색을 반환합니다. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | ARGB 값이 16진수 표기법으로 #FF6495ED인 색을 반환합니다. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | ARGB 값이 16진수 표기법으로 #FFFFF8DC인 색을 반환합니다. |
| static [Color](./) [get_Crimson](./get_crimson/)() | ARGB 값이 16진수 표기법으로 #FFDC143C인 색을 반환합니다. |
| static [Color](./) [get_Cyan](./get_cyan/)() | ARGB 값이 16진수 표기법으로 #FF00FFFF인 색을 반환합니다. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | ARGB 값이 16진수 표기법으로 #FF00008B인 색을 반환합니다. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | ARGB 값이 16진수 표기법으로 #FF008B8B인 색을 반환합니다. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | ARGB 값이 16진수 표기법으로 #FFB8860B인 색을 반환합니다. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | ARGB 값이 16진수 표기법으로 #FFA9A9A9인 색을 반환합니다. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | ARGB 값이 16진수 표기법으로 #FF006400인 색을 반환합니다. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | ARGB 값이 16진수 표기법으로 #FFBDB76B인 색을 반환합니다. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | ARGB 값이 16진수 표기법으로 #FF8B008B인 색을 반환합니다. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | ARGB 값이 16진수 표기법으로 #FF556B2F인 색을 반환합니다. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | ARGB 값이 16진수 표기법으로 #FFFF8C00인 색을 반환합니다. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | ARGB 값이 16진수 표기법으로 #FF9932CC인 색을 반환합니다. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | ARGB 값이 16진수 표기법으로 #FF8B0000인 색을 반환합니다. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | ARGB 값이 16진수 표기법으로 #FFE9967A인 색을 반환합니다. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | ARGB 값이 16진수 표기법으로 #FF8FBC8F인 색을 반환합니다. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | ARGB 값이 16진수 표기법으로 #FF483D8B인 색을 반환합니다. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | ARGB 값이 16진수 표기법으로 #FF2F4F4F인 색을 반환합니다. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | ARGB 값이 16진수 표기법으로 #FF00CED1인 색을 반환합니다. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | ARGB 값이 16진수 표기법으로 #FF9400D3인 색을 반환합니다. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | ARGB 값이 16진수 표기법으로 #FFFF1493인 색을 반환합니다. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | ARGB 값이 16진수 표기법으로 #FF00BFFF인 색을 반환합니다. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | ARGB 값이 16진수 표기법으로 #FF696969인 색을 반환합니다. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | ARGB 값이 16진수 표기법으로 #FF1E90FF인 색을 반환합니다. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | ARGB 값이 16진수 표기법으로 #FFB22222인 색을 반환합니다. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | ARGB 값이 16진수 표기법으로 #FFFFFAF0인 색을 반환합니다. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | ARGB 값이 16진수 표기법으로 #FF228B22인 색을 반환합니다. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | ARGB 값이 16진수 표기법으로 #FFFF00FF인 색을 반환합니다. |
| int [get_G](./get_g/)() const | 현재 객체가 나타내는 색의 녹색 구성 요소 값을 반환합니다. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | ARGB 값이 16진수 표기법으로 #FFDCDCDC인 색을 반환합니다. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | ARGB 값이 16진수 표기법으로 #FFF8F8FF인 색을 반환합니다. |
| static [Color](./) [get_Gold](./get_gold/)() | ARGB 값이 16진수 표기법으로 #FFFFD700인 색을 반환합니다. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | ARGB 값이 16진수 표기법으로 #FFDAA520인 색을 반환합니다. |
| static [Color](./) [get_Gray](./get_gray/)() | ARGB 값이 16진수 표기법으로 #FF808080인 색을 반환합니다. |
| static [Color](./) [get_Green](./get_green/)() | ARGB 값이 16진수 표기법으로 #FF008000인 색을 반환합니다. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | ARGB 값이 16진수 표기법으로 #FFADFF2F인 색을 반환합니다. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | ARGB 값이 16진수 표기법으로 #FFF0FFF0인 색을 반환합니다. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | ARGB 값이 16진수 표기법으로 #FFFF69B4인 색을 반환합니다. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | ARGB 값이 16진수 표기법으로 #FFCD5C5C인 색을 반환합니다. |
| static [Color](./) [get_Indigo](./get_indigo/)() | ARGB 값이 16진수 표기법으로 #FF4B0082인 색을 반환합니다. |
| **bool** [get_IsEmpty](./get_isempty/)() const | 현재 객체가 “빈”지, 즉 어떠한 색도 나타내지 않는지 여부를 반환합니다. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | [Color](./) 구조체가 명명된 색인지 KnownColor 열거형 요소인지를 판단합니다. |
| static [Color](./) [get_Ivory](./get_ivory/)() | ARGB 값이 16진수 표기법으로 #FFFFFFF0인 색을 반환합니다. |
| static [Color](./) [get_Khaki](./get_khaki/)() | ARGB 값이 16진수 표기법으로 #FFF0E68C인 색을 반환합니다. |
| static [Color](./) [get_Lavender](./get_lavender/)() | ARGB 값이 16진수 표기법으로 #FFE6E6FA인 색을 반환합니다. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | ARGB 값이 16진수 표기법으로 #FFFFF0F5인 색을 반환합니다. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | ARGB 값이 16진수 표기법으로 #FF7CFC00인 색을 반환합니다. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | ARGB 값이 16진수 표기법으로 #FFFFFACD인 색을 반환합니다. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | ARGB 값이 16진수 표기법으로 #FFADD8E6인 색을 반환합니다. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | ARGB 값이 16진수 표기법으로 #FFF08080인 색을 반환합니다. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | ARGB 값이 16진수 표기법으로 #FFE0FFFF인 색을 반환합니다. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | ARGB 값이 16진수 표기법으로 #FFFAFAD2인 색을 반환합니다. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | ARGB 값이 16진수 표기법으로 #FFD3D3D3인 색을 반환합니다. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | ARGB 값이 16진수 표기법으로 #FF90EE90인 색을 반환합니다. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | ARGB 값이 16진수 표기법으로 #FFFFB6C1인 색을 반환합니다. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | ARGB 값이 16진수 표기법으로 #FFFFA07A인 색을 반환합니다. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | ARGB 값이 16진수 표기법으로 #FF20B2AA인 색을 반환합니다. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | ARGB 값이 16진수 표기법으로 #FF87CEFA인 색을 반환합니다. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | ARGB 값이 16진수 표기법으로 #FF778899인 색을 반환합니다. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | ARGB 값이 16진수 표기법으로 #FFB0C4DE인 색을 반환합니다. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | ARGB 값이 16진수 표기법으로 #FFFFFFE0인 색을 반환합니다. |
| static [Color](./) [get_Lime](./get_lime/)() | ARGB 값이 16진수 표기법으로 #FF00FF00인 색을 반환합니다. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | ARGB 값이 16진수 표기법으로 #FF32CD32인 색을 반환합니다. |
| static [Color](./) [get_Linen](./get_linen/)() | ARGB 값이 16진수 표기법으로 #FFFAF0E6인 색을 반환합니다. |
| static [Color](./) [get_Magenta](./get_magenta/)() | ARGB 값이 16진수 표기법으로 #FFFF00FF인 색을 반환합니다. |
| static [Color](./) [get_Maroon](./get_maroon/)() | ARGB 값이 16진수 표기법으로 #FF800000인 색을 반환합니다. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | ARGB 값이 16진수 표기법으로 #FF66CDAA인 색을 반환합니다. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | ARGB 값이 16진수 표기법으로 #FF0000CD인 색을 반환합니다. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | ARGB 값이 16진수 표기법으로 #FFBA55D3인 색을 반환합니다. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | ARGB 값이 16진수 표기법으로 #FF9370DB인 색을 반환합니다. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | ARGB 값이 16진수 표기법으로 #FF3CB371인 색을 반환합니다. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | ARGB 값이 16진수 표기법으로 #FF7B68EE인 색을 반환합니다. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | ARGB 값이 16진수 표기법으로 #FF00FA9A인 색을 반환합니다. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | ARGB 값이 16진수 표기법으로 #FF48D1CC인 색을 반환합니다. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | ARGB 값이 16진수 표기법으로 #FFC71585인 색을 반환합니다. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | ARGB 값이 16진수 표기법으로 #FF191970인 색을 반환합니다. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | ARGB 값이 16진수 표기법으로 #FFF5FFFA인 색을 반환합니다. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | ARGB 값이 16진수 표기법으로 #FFFFE4E1인 색을 반환합니다. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | ARGB 값이 16진수 표기법으로 #FFFFE4B5인 색을 반환합니다. |
| [String](../../system/string/) [get_Name](./get_name/)() const | 현재 객체가 나타내는 색의 이름을 반환합니다. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | ARGB 값이 16진수 표기법으로 #FFFFDEAD인 색을 반환합니다. |
| static [Color](./) [get_Navy](./get_navy/)() | ARGB 값이 16진수 표기법으로 #FF000080인 색을 반환합니다. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | ARGB 값이 16진수 표기법으로 #FFFDF5E6인 색을 반환합니다. |
| static [Color](./) [get_Olive](./get_olive/)() | ARGB 값이 16진수 표기법으로 #FF808000인 색을 반환합니다. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | ARGB 값이 16진수 표기법으로 #FF6B8E23인 색을 반환합니다. |
| static [Color](./) [get_Orange](./get_orange/)() | ARGB 값이 16진수 표기법으로 #FFFFA500인 색을 반환합니다. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | ARGB 값이 16진수 표기법으로 #FFFF4500인 색을 반환합니다. |
| static [Color](./) [get_Orchid](./get_orchid/)() | ARGB 값이 16진수 표기법으로 #FFDA70D6인 색을 반환합니다. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | ARGB 값이 16진수 표기법으로 #FFEEE8AA인 색을 반환합니다. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | ARGB 값이 16진수 표기법으로 #FF98FB98인 색을 반환합니다. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | ARGB 값이 16진수 표기법으로 #FFAFEEEE인 색을 반환합니다. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | ARGB 값이 16진수 표기법으로 #FFDB7093인 색을 반환합니다. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | ARGB 값이 16진수 표기법으로 #FFFFEFD5인 색을 반환합니다. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | ARGB 값이 16진수 표기법으로 #FFFFDAB9인 색을 반환합니다. |
| static [Color](./) [get_Peru](./get_peru/)() | ARGB 값이 16진수 표기법으로 #FFCD853F인 색을 반환합니다. |
| static [Color](./) [get_Pink](./get_pink/)() | ARGB 값이 16진수 표기법으로 #FFFFC0CB인 색을 반환합니다. |
| static [Color](./) [get_Plum](./get_plum/)() | ARGB 값이 16진수 표기법으로 #FFDDA0DD인 색을 반환합니다. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | ARGB 값이 16진수 표기법으로 #FFB0E0E6인 색을 반환합니다. |
| static [Color](./) [get_Purple](./get_purple/)() | ARGB 값이 16진수 표기법으로 #FF800080인 색을 반환합니다. |
| int [get_R](./get_r/)() const | 현재 객체가 나타내는 색의 빨간색 구성 요소 값을 반환합니다. |
| static [Color](./) [get_Red](./get_red/)() | ARGB 값이 16진수 표기법으로 #FFFF0000인 색을 반환합니다. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | ARGB 값이 16진수 표기법으로 #FFBC8F8F인 색을 반환합니다. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | ARGB 값이 16진수 표기법으로 #FF4169E1인 색을 반환합니다. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | ARGB 값이 16진수 표기법으로 #FF8B4513인 색을 반환합니다. |
| static [Color](./) [get_Salmon](./get_salmon/)() | ARGB 값이 16진수 표기법으로 #FFFA8072인 색을 반환합니다. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | ARGB 값이 16진수 표기법으로 #FFF4A460인 색을 반환합니다. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | ARGB 값이 16진수 표기법으로 #FF2E8B57인 색을 반환합니다. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | ARGB 값이 16진수 표기법으로 #FFFFF5EE인 색을 반환합니다. |
| static [Color](./) [get_Sienna](./get_sienna/)() | ARGB 값이 16진수 표기법으로 #FFA0522D인 색을 반환합니다. |
| static [Color](./) [get_Silver](./get_silver/)() | ARGB 값이 16진수 표기법으로 #FFC0C0C0인 색을 반환합니다. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | ARGB 값이 16진수 표기법으로 #FF87CEEB인 색을 반환합니다. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | ARGB 값이 16진수 표기법으로 #FF6A5ACD인 색을 반환합니다. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | ARGB 값이 16진수 표기법으로 #FF708090인 색을 반환합니다. |
| static [Color](./) [get_Snow](./get_snow/)() | ARGB 값이 16진수 표기법으로 #FFFFFAFA인 색을 반환합니다. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | ARGB 값이 16진수 표기법으로 #FF00FF7F인 색을 반환합니다. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | ARGB 값이 16진수 표기법으로 #FF4682B4인 색을 반환합니다. |
| static [Color](./) [get_Tan](./get_tan/)() | ARGB 값이 16진수 표기법으로 #FFD2B48C인 색을 반환합니다. |
| static [Color](./) [get_Teal](./get_teal/)() | ARGB 값이 16진수 표기법으로 #FF008080인 색을 반환합니다. |
| static [Color](./) [get_Thistle](./get_thistle/)() | ARGB 값이 16진수 표기법으로 #FFD8BFD8인 색을 반환합니다. |
| static [Color](./) [get_Tomato](./get_tomato/)() | ARGB 값이 16진수 표기법으로 #FFFF6347인 색을 반환합니다. |
| static [Color](./) [get_Transparent](./get_transparent/)() | ARGB 값이 16진수 표기법으로 #00FFFFFF인 색을 반환합니다. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | ARGB 값이 16진수 표기법으로 #FF40E0D0인 색을 반환합니다. |
| static [Color](./) [get_Violet](./get_violet/)() | ARGB 값이 16진수 표기법으로 #FFEE82EE인 색을 반환합니다. |
| static [Color](./) [get_Wheat](./get_wheat/)() | ARGB 값이 16진수 표기법으로 #FFF5DEB3인 색을 반환합니다. |
| static [Color](./) [get_White](./get_white/)() | ARGB 값이 16진수 표기법으로 #FFFFFFFF인 색을 반환합니다. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | ARGB 값이 16진수 표기법으로 #FFF5F5F5인 색을 반환합니다. |
| static [Color](./) [get_Yellow](./get_yellow/)() | ARGB 값이 16진수 표기법으로 #FFFFFF00인 색을 반환합니다. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | ARGB 값이 16진수 표기법으로 #FF9ACD32인 색을 반환합니다. |
| **float** [GetBrightness](./getbrightness/)() | 현재 객체가 나타내는 색의 밝기 구성 요소를 반환합니다. |
| int [GetHashCode](./gethashcode/)() const | 현재 객체의 해시 코드를 반환합니다. |
| **float** [GetHue](./gethue/)() | 현재 객체가 나타내는 색의 색상-채도-명도(HSB) 색상 값을 도 단위로 반환합니다. |
| **float** [GetSaturation](./getsaturation/)() | 현재 객체가 나타내는 색의 색상-채도-명도(HSB) 채도를 반환합니다. |
| **bool** [IsNull](./isnull/)() const | 항상 false를 반환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | 항상 true를 반환합니다. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | 현재 객체와 지정된 [Color](./) 객체가 다른 색을 나타내는지 확인합니다. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | 항상 false를 반환합니다. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | 현재 객체와 지정된 [Color](./) 객체가 같은 색을 나타내는지 확인합니다. |
| int [ToArgb](./toargb/)() const | 현재 객체가 나타내는 색의 32비트 ARGB 값을 반환합니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 현재 객체의 문자열 표현을 반환합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| static [Empty](./empty/) | [Color](./) 클래스의 “빈” 인스턴스, 즉 어떠한 색도 나타내지 않는 인스턴스입니다. |
## 참고

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)