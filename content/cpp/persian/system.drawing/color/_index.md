---
title: Color
second_title: Aspose.Slides برای مرجع API C++
description: "نمایانگر یک رنگ است. این نوع باید در پشته تخصیص یابد و به توابع به صورت مقدار یا ارجاع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 53
url: /fa/system.drawing/color/
---
## کلاس Color

نمایش یک رنگ. این نوع باید روی پشته تخصیص یابد و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس [System::SmartPtr](../../system/smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Color
```

## متدها

| Method | Description |
| --- | --- |
|  [Color](./color/)() | یک نمونه «خالی» از کلاس [Color](./) می‌سازد که هیچ رنگی را نشان نمی‌دهد. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | تعیین می‌کند آیا اشیاء [Color](./) جاری و مشخص‌شده همان رنگ را نشان می‌دهند. |
| static [Color](./) [FromArgb](./fromargb/)(int) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ مشخص‌شده را نشان می‌دهد. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ مشخص‌شده را نشان می‌دهد. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ دارای مؤلفه آلفا 0xFF است. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ مشخص‌شده را نشان می‌دهد. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ شناخته‌شدهٔ مشخص‌شده را نشان می‌دهد. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | یک نمونه از کلاس [Color](./) می‌سازد که رنگ با نام مشخص‌شده را نشان می‌دهد. |
| int [get_A](./get_a/)() const | مقدار مؤلفهٔ آلفای رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF0F8FF است. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFAEBD7 است. |
| static [Color](./) [get_Aqua](./get_aqua/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00FFFF است. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF7FFFD4 است. |
| static [Color](./) [get_Azure](./get_azure/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF0FFFF است. |
| int [get_B](./get_b/)() const | مقدار مؤلفهٔ آبی رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| static [Color](./) [get_Beige](./get_beige/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF5F5DC است. |
| static [Color](./) [get_Bisque](./get_bisque/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFE4C4 است. |
| static [Color](./) [get_Black](./get_black/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF000000 است. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFEBCD است. |
| static [Color](./) [get_Blue](./get_blue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF0000FF است. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF8A2BE2 است. |
| static [Color](./) [get_Brown](./get_brown/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFA52A2A است. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDEB887 است. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF5F9EA0 است. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF7FFF00 است. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFD2691E است. |
| static [Color](./) [get_Coral](./get_coral/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF7F50 است. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF6495ED است. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFF8DC است. |
| static [Color](./) [get_Crimson](./get_crimson/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDC143C است. |
| static [Color](./) [get_Cyan](./get_cyan/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00FFFF است. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00008B است. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF008B8B است. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFB8860B است. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFA9A9A9 است. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF006400 است. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFBDB76B است. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF8B008B است. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF556B2F است. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF8C00 است. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF9932CC است. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF8B0000 است. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFE9967A است. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF8FBC8F است. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF483D8B است. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF2F4F4F است. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00CED1 است. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF9400D3 است. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF1493 است. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00BFFF است. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF696969 است. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF1E90FF است. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFB22222 است. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFAF0 است. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF228B22 است. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF00FF است. |
| int [get_G](./get_g/)() const | مقدار مؤلفهٔ سبز رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDCDCDC است. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF8F8FF است. |
| static [Color](./) [get_Gold](./get_gold/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFD700 است. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDAA520 است. |
| static [Color](./) [get_Gray](./get_gray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF808080 است. |
| static [Color](./) [get_Green](./get_green/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF008000 است. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFADFF2F است. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF0FFF0 است. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF69B4 است. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFCD5C5C است. |
| static [Color](./) [get_Indigo](./get_indigo/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF4B0082 است. |
| **bool** [get_IsEmpty](./get_isempty/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا شیء جاری «خالی» است، یعنی هیچ رنگی را نشان نمی‌دهد. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا ساختار [Color](./) نشانگر رنگ نام‌گذاری‌شده یا عضو شناسه KnownColor است. |
| static [Color](./) [get_Ivory](./get_ivory/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFFF0 است. |
| static [Color](./) [get_Khaki](./get_khaki/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF0E68C است. |
| static [Color](./) [get_Lavender](./get_lavender/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFE6E6FA است. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFF0F5 است. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF7CFC00 است. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFACD است. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFADD8E6 است. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF08080 است. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFE0FFFF است. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFAFAD2 است. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFD3D3D3 است. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF90EE90 است. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFB6C1 است. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFA07A است. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF20B2AA است. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF87CEFA است. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF778899 است. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFB0C4DE است. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFFE0 است. |
| static [Color](./) [get_Lime](./get_lime/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00FF00 است. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF32CD32 است. |
| static [Color](./) [get_Linen](./get_linen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFAF0E6 است. |
| static [Color](./) [get_Magenta](./get_magenta/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF00FF است. |
| static [Color](./) [get_Maroon](./get_maroon/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF800000 است. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF66CDAA است. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF0000CD است. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFBA55D3 است. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF9370DB است. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF3CB371 است. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF7B68EE است. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00FA9A است. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF48D1CC است. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFC71585 است. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF191970 است. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF5FFFA است. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFE4E1 است. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFE4B5 است. |
| [String](../../system/string/) [get_Name](./get_name/)() const | نام رنگی که توسط شیء جاری نشان داده می‌شود را برمی‌گرداند. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFDEAD است. |
| static [Color](./) [get_Navy](./get_navy/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF000080 است. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFDF5E6 است. |
| static [Color](./) [get_Olive](./get_olive/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF808000 است. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF6B8E23 است. |
| static [Color](./) [get_Orange](./get_orange/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFA500 است. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF4500 است. |
| static [Color](./) [get_Orchid](./get_orchid/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDA70D6 است. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFEEE8AA است. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF98FB98 است. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFAFEEEE است. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDB7093 است. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFEFD5 است. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFDAB9 است. |
| static [Color](./) [get_Peru](./get_peru/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFCD853F است. |
| static [Color](./) [get_Pink](./get_pink/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFC0CB است. |
| static [Color](./) [get_Plum](./get_plum/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFDDA0DD است. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFB0E0E6 است. |
| static [Color](./) [get_Purple](./get_purple/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF800080 است. |
| int [get_R](./get_r/)() const | مقدار مؤلفهٔ قرمز رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| static [Color](./) [get_Red](./get_red/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF0000 است. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFBC8F8F است. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF4169E1 است. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF8B4513 است. |
| static [Color](./) [get_Salmon](./get_salmon/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFA8072 است. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF4A460 است. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF2E8B57 است. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFF5EE است. |
| static [Color](./) [get_Sienna](./get_sienna/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFA0522D است. |
| static [Color](./) [get_Silver](./get_silver/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFC0C0C0 است. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF87CEEB است. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF6A5ACD است. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF708090 است. |
| static [Color](./) [get_Snow](./get_snow/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFAFA است. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF00FF7F است. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF4682B4 است. |
| static [Color](./) [get_Tan](./get_tan/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFD2B48C است. |
| static [Color](./) [get_Teal](./get_teal/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF008080 است. |
| static [Color](./) [get_Thistle](./get_thistle/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFD8BFD8 است. |
| static [Color](./) [get_Tomato](./get_tomato/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFF6347 است. |
| static [Color](./) [get_Transparent](./get_transparent/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #00FFFFFF است. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF40E0D0 است. |
| static [Color](./) [get_Violet](./get_violet/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFEE82EE است. |
| static [Color](./) [get_Wheat](./get_wheat/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF5DEB3 است. |
| static [Color](./) [get_White](./get_white/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFFFF است. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFF5F5F5 است. |
| static [Color](./) [get_Yellow](./get_yellow/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FFFFFF00 است. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | رنگی را برمی‌گرداند که مقدار ARGB آن در نمای هگزادسیمال #FF9ACD32 است. |
| **float** [GetBrightness](./getbrightness/)() | مؤلفهٔ روشنایی رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | کد هش شیء جاری را برمی‌گرداند. |
| **float** [GetHue](./gethue/)() | مقدار هیو (Hue) در سیستم HSB به درجه برای رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| **float** [GetSaturation](./getsaturation/)() | مقدار اشباع (Saturation) در سیستم HSB برای رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| **bool** [IsNull](./isnull/)() const | همیشه false برمی‌گرداند. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | همیشه true برمی‌گرداند. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | تشخیص می‌دهد آیا اشیاء [Color](./) جاری و مشخص‌شده رنگ‌های متفاوتی را نشان می‌دهند. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | همیشه false برمی‌گرداند. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | تشخیص می‌دهد آیا اشیاء [Color](./) جاری و مشخص‌شده همان رنگ را نشان می‌دهند. |
| int [ToArgb](./toargb/)() const | مقدار ۳۲-بیتی ARGB رنگ نمایش داده شده توسط شیء جاری را برمی‌گرداند. |
| [String](../../system/string/) [ToString](./tostring/)() const | نمایش رشته‌ای شیء جاری را برمی‌گرداند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | یک نمونه «خالی» از کلاس [Color](./) یعنی نمونه‌ای که هیچ رنگی را نشان نمی‌دهد. |

## همچنین ببینید

* فضای نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)