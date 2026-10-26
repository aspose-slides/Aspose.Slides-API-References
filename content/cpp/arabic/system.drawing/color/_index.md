---
title: Color
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: "يمثل لونًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 53
url: /ar/system.drawing/color/
---
## فئة Color

يمثل لونًا. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم فئة [System::SmartPtr](../../system/smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Color
```

## الطرق

| Method | Description |
| --- | --- |
|  [Color](./color/)() | ينشئ نسخة "فارغة" من فئة [Color](./) لا تمثل أي لون. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | يحدد ما إذا كان الكائنان الحاليان والـ[Color](./) المحددان يمثلان نفس اللون. |
| static [Color](./) [FromArgb](./fromargb/)(int) | ينشئ نسخة من فئة [Color](./) تمثل اللون المحدد. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | ينشئ نسخة من فئة [Color](./) تمثل اللون المحدد. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | ينشئ نسخة من فئة [Color](./) تمثل اللون المحدد مع تعيين مكون ألفا إلى 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | ينشئ نسخة من فئة [Color](./) تمثل اللون المحدد. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | ينشئ نسخة من فئة [Color](./) تمثل اللون المعروف المحدد. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | ينشئ نسخة من فئة [Color](./) تمثل لونًا بالاسم المحدد. |
| int [get_A](./get_a/)() const | يعيد قيمة مكون ألفا للون الممثل بواسطة الكائن الحالي. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF0FFFF. |
| int [get_B](./get_b/)() const | يعيد قيمة مكون الأزرق للون الممثل بواسطة الكائن الحالي. |
| static [Color](./) [get_Beige](./get_beige/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF00FF. |
| int [get_G](./get_g/)() const | يعيد قيمة مكون الأخضر للون الممثل بواسطة الكائن الحالي. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | يعيد قيمة تشير إلى ما إذا كان الكائن الحالي "فارغًا" أي لا يمثل أي لون. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | يعيد قيمة تحدد ما إذا كانت بنية [Color](./) تمثل لونًا مسمىً أو عضوًا من تعداد KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | يعيد اسم اللون الممثل بواسطة الكائن الحالي. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF800080. |
| int [get_R](./get_r/)() const | يعيد قيمة مكون الأحمر للون الممثل بواسطة الكائن الحالي. |
| static [Color](./) [get_Red](./get_red/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | يعيد لونًا قيمته ARGB بنظام سداسي عشري هي #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | يعيد مكون السطوع للون الممثل بالكائن الحالي. |
| int [GetHashCode](./gethashcode/)() const | يعيد رمز التجزئة (hash) للكائن الحالي. |
| **float** [GetHue](./gethue/)() | يعيد قيمة تدرج اللون (Hue) في نظام HSB بالدرجات للون الممثل بالكائن الحالي. |
| **float** [GetSaturation](./getsaturation/)() | يعيد قيمة التشبع (Saturation) في نظام HSB للون الممثل بالكائن الحالي. |
| **bool** [IsNull](./isnull/)() const | دائمًا ما يعيد false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | دائمًا ما يعيد true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | يحدد ما إذا كان الكائنان الحاليان والـ[Color](./) المحددان يمثلان ألوانًا مختلفة. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | دائمًا ما يعيد false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | يحدد ما إذا كان الكائنان الحاليان والـ[Color](./) المحددان يمثلان نفس اللون. |
| int [ToArgb](./toargb/)() const | يعيد قيمة ARGB 32-بت للون الممثل بالكائن الحالي. |
| [String](../../system/string/) [ToString](./tostring/)() const | يعيد التمثيل النصي للكائن الحالي. |
## الحقول

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | نسخة "فارغة" من فئة [Color](./) أي نسخة لا تمثل أي لون. |
## انظر أيضًا

* المجال [System::Drawing](../)
* المكتبة [Aspose.Slides](../../)