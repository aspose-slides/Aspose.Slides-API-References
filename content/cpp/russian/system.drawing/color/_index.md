---
title: Color
second_title: Справочник API Aspose.Slides для C++
description: "Представляет цвет. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 53
url: /ru/system.drawing/color/
---
## Color класс

Представляет цвет. Этот тип должен быть выделен в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте [System::SmartPtr](../../system/smartptr/) класс для управления объектами этого типа.

```cpp
class Color
```

## Методы

| Method | Description |
| --- | --- |
|  [Color](./color/)() | Создаёт «пустой» экземпляр класса [Color](./), который не представляет никакого цвета. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) один и тот же цвет. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет с альфа-компонентом, установленным в 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Создаёт экземпляр класса [Color](./), представляющий указанный цвет. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Создаёт экземпляр класса [Color](./), представляющий указанный известный цвет. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Создаёт экземпляр класса [Color](./), представляющий цвет с указанным именем. |
| int [get_A](./get_a/)() const | Возвращает значение альфа-компоненты цвета, представленного текущим объектом. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF0FFFF. |
| int [get_B](./get_b/)() const | Возвращает значение синей компоненты цвета, представленного текущим объектом. |
| static [Color](./) [get_Beige](./get_beige/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF00FF. |
| int [get_G](./get_g/)() const | Возвращает значение зеленой компоненты цвета, представленного текущим объектом. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Возвращает значение, указывающее, что текущий объект «пустой», т.е. не представляет никакого цвета. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Возвращает значение, определяющее, представляет ли структура [Color](./) именованный цвет или элемент перечисления KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Возвращает цвет, значение ARBG которого в шестнадцатеричной записи #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Возвращает имя цвета, представленного текущим объектом. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF800080. |
| int [get_R](./get_r/)() const | Возвращает значение красной компоненты цвета, представленного текущим объектом. |
| static [Color](./) [get_Red](./get_red/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Возвращает цвет, значение ARGB которого в шестнадцатеричной записи #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Возвращает компонент яркости цвета, представленного текущим объектом. |
| int [GetHashCode](./gethashcode/)() const | Возвращает код хэша текущего объекта. |
| **float** [GetHue](./gethue/)() | Возвращает значение оттенка (Hue) в системе HSB, в градусах, для цвета, представленного текущим объектом. |
| **float** [GetSaturation](./getsaturation/)() | Возвращает значение насыщенности (Saturation) в системе HSB для цвета, представленного текущим объектом. |
| **bool** [IsNull](./isnull/)() const | Всегда возвращает false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Всегда возвращает true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) разные цвета. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Всегда возвращает false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Определяет, представляют ли текущий и указанный объекты [Color](./) один и тот же цвет. |
| int [ToArgb](./toargb/)() const | Возвращает 32-битное значение ARGB цвета, представленного текущим объектом. |
| [String](../../system/string/) [ToString](./tostring/)() const | Возвращает строковое представление текущего объекта. |
## Поля

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | «Пустой» экземпляр класса [Color](./), т.е. экземпляр, который не представляет никакого цвета. |
## См. также

* Простой имён [System::Drawing](../)
* Библиотека [Aspose.Slides](../../)