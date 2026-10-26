---
title: Color
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: "เป็นตัวแทนของสี. ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง. อย่าใช้คลาส System::SmartPtr เพื่อจัดการวัตถุของประเภทนี้."
type: docs
weight: 53
url: /th/system.drawing/color/
---
## คลาส Color

เป็นตัวแทนของสี. ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง. อย่าใช้คลาส [System::SmartPtr](../../system/smartptr/) เพื่อจัดการวัตถุของประเภทนี้.

```cpp
class Color
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [Color](./color/)() | สร้างอินสแตนซ์ \"ว่าง\" ของคลาส [Color](./) ที่ไม่เป็นตัวแทนของสีใด |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | ตรวจสอบว่าวัตถุปัจจุบันและวัตถุ [Color](./) ที่ระบุเป็นตัวแทนของสีเดียวกันหรือไม่ |
| static [Color](./) [FromArgb](./fromargb/)(int) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีตามที่ระบุ |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีตามที่ระบุ |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีตามที่ระบุ โดยตั้งค่าอัลฟาเป็น 0xFF |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีตามที่ระบุ |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีที่รู้จักตามที่ระบุ |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | สร้างอินสแตนซ์ของคลาส [Color](./) ที่เป็นสีตามชื่อที่ระบุ |
| int [get_A](./get_a/)() const | คืนค่าคอมโพเนนต์อัลฟาของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF0F8FF |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFAEBD7 |
| static [Color](./) [get_Aqua](./get_aqua/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00FFFF |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF7FFFD4 |
| static [Color](./) [get_Azure](./get_azure/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF0FFFF |
| int [get_B](./get_b/)() const | คืนค่าคอมโพเนนต์สีน้ำเงินของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| static [Color](./) [get_Beige](./get_beige/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF5F5DC |
| static [Color](./) [get_Bisque](./get_bisque/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFE4C4 |
| static [Color](./) [get_Black](./get_black/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF000000 |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFEBCD |
| static [Color](./) [get_Blue](./get_blue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF0000FF |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF8A2BE2 |
| static [Color](./) [get_Brown](./get_brown/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFA52A2A |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDEB887 |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF5F9EA0 |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF7FFF00 |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFD2691E |
| static [Color](./) [get_Coral](./get_coral/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF7F50 |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF6495ED |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFF8DC |
| static [Color](./) [get_Crimson](./get_crimson/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDC143C |
| static [Color](./) [get_Cyan](./get_cyan/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00FFFF |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00008B |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF008B8B |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFB8860B |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFA9A9A9 |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF006400 |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFBDB76B |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF8B008B |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF556B2F |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF8C00 |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF9932CC |
| static [Color](./) [get_DarkRed](./get_darkred/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF8B0000 |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFE9967A |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF8FBC8F |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF483D8B |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF2F4F4F |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00CED1 |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF9400D3 |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF1493 |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00BFFF |
| static [Color](./) [get_DimGray](./get_dimgray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF696969 |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF1E90FF |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFB22222 |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFAF0 |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF228B22 |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF00FF |
| int [get_G](./get_g/)() const | คืนค่าคอมโพเนนต์สีเขียวของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDCDCDC |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF8F8FF |
| static [Color](./) [get_Gold](./get_gold/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFD700 |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDAA520 |
| static [Color](./) [get_Gray](./get_gray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF808080 |
| static [Color](./) [get_Green](./get_green/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF008000 |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFADFF2F |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF0FFF0 |
| static [Color](./) [get_HotPink](./get_hotpink/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF69B4 |
| static [Color](./) [get_IndianRed](./get_indianred/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFCD5C5C |
| static [Color](./) [get_Indigo](./get_indigo/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF4B0082 |
| **bool** [get_IsEmpty](./get_isempty/)() const | คืนค่าที่บ่งบอกว่าวัตถุปัจจุบันเป็น \"ว่าง\" หรือไม่ คือไม่เป็นตัวแทนของสีใด |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | คืนค่าที่ระบุว่ารูปแบบ [Color](./) เป็นสีที่ตั้งชื่อหรือเป็นสมาชิกของการนับจำนวน KnownColor |
| static [Color](./) [get_Ivory](./get_ivory/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFFF0 |
| static [Color](./) [get_Khaki](./get_khaki/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF0E68C |
| static [Color](./) [get_Lavender](./get_lavender/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFE6E6FA |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFF0F5 |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF7CFC00 |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFACD |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFADD8E6 |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF08080 |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFE0FFFF |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFAFAD2 |
| static [Color](./) [get_LightGray](./get_lightgray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFD3D3D3 |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF90EE90 |
| static [Color](./) [get_LightPink](./get_lightpink/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFB6C1 |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFA07A |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF20B2AA |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF87CEFA |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF778899 |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFB0C4DE |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFFE0 |
| static [Color](./) [get_Lime](./get_lime/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00FF00 |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF32CD32 |
| static [Color](./) [get_Linen](./get_linen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFAF0E6 |
| static [Color](./) [get_Magenta](./get_magenta/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF00FF |
| static [Color](./) [get_Maroon](./get_maroon/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF800000 |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF66CDAA |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF0000CD |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFBA55D3 |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF9370DB |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF3CB371 |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF7B68EE |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00FA9A |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF48D1CC |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFC71585 |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF191970 |
| static [Color](./) [get_MintCream](./get_mintcream/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF5FFFA |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFE4E1 |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFE4B5 |
| [String](../../system/string/) [get_Name](./get_name/)() const | คืนชื่อของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFDEAD |
| static [Color](./) [get_Navy](./get_navy/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF000080 |
| static [Color](./) [get_OldLace](./get_oldlace/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFDF5E6 |
| static [Color](./) [get_Olive](./get_olive/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF808000 |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF6B8E23 |
| static [Color](./) [get_Orange](./get_orange/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFA500 |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF4500 |
| static [Color](./) [get_Orchid](./get_orchid/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDA70D6 |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFEEE8AA |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF98FB98 |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFAFEEEE |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDB7093 |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFEFD5 |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFDAB9 |
| static [Color](./) [get_Peru](./get_peru/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFCD853F |
| static [Color](./) [get_Pink](./get_pink/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFC0CB |
| static [Color](./) [get_Plum](./get_plum/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFDDA0DD |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFB0E0E6 |
| static [Color](./) [get_Purple](./get_purple/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF800080 |
| int [get_R](./get_r/)() const | คืนค่าคอมโพเนนต์สีแดงของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| static [Color](./) [get_Red](./get_red/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF0000 |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFBC8F8F |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF4169E1 |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF8B4513 |
| static [Color](./) [get_Salmon](./get_salmon/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFA8072 |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF4A460 |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF2E8B57 |
| static [Color](./) [get_SeaShell](./get_seashell/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFF5EE |
| static [Color](./) [get_Sienna](./get_sienna/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFA0522D |
| static [Color](./) [get_Silver](./get_silver/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFC0C0C0 |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF87CEEB |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF6A5ACD |
| static [Color](./) [get_SlateGray](./get_slategray/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF708090 |
| static [Color](./) [get_Snow](./get_snow/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFAFA |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF00FF7F |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF4682B4 |
| static [Color](./) [get_Tan](./get_tan/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFD2B48C |
| static [Color](./) [get_Teal](./get_teal/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF008080 |
| static [Color](./) [get_Thistle](./get_thistle/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFD8BFD8 |
| static [Color](./) [get_Tomato](./get_tomato/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFF6347 |
| static [Color](./) [get_Transparent](./get_transparent/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #00FFFFFF |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF40E0D0 |
| static [Color](./) [get_Violet](./get_violet/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFEE82EE |
| static [Color](./) [get_Wheat](./get_wheat/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF5DEB3 |
| static [Color](./) [get_White](./get_white/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFFFF |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFF5F5F5 |
| static [Color](./) [get_Yellow](./get_yellow/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FFFFFF00 |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | ส่งคืนสีที่ค่า ARGB ในรูปแบบเลขฐานสิบหกเป็น #FF9ACD32 |
| **float** [GetBrightness](./getbrightness/)() | คืนค่าคอมโพเนนต์ความสว่างของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| int [GetHashCode](./gethashcode/)() const | คืนค่า hash code ของวัตถุปัจจุบัน |
| **float** [GetHue](./gethue/)() | คืนค่ามุม Hue (สี) ของ HSB ในหน่วยองศา สำหรับสีที่วัตถุปัจจุบันเป็นตัวแทน |
| **float** [GetSaturation](./getsaturation/)() | คืนค่า saturation ของ HSB สำหรับสีที่วัตถุปัจจุบันเป็นตัวแทน |
| **bool** [IsNull](./isnull/)() const | คืนค่า false เสมอ |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | คืนค่า true เสมอ |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | ตรวจสอบว่าวัตถุปัจจุบันและวัตถุ [Color](./) ที่ระบุเป็นสีที่แตกต่างกันหรือไม่ |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | คืนค่า false เสมอ |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | ตรวจสอบว่าวัตถุปัจจุบันและวัตถุ [Color](./) ที่ระบุเป็นสีเดียวกันหรือไม่ |
| int [ToArgb](./toargb/)() const | คืนค่า ARGB 32-บิตของสีที่วัตถุปัจจุบันเป็นตัวแทน |
| [String](../../system/string/) [ToString](./tostring/)() const | คืนค่าการแสดงผลเป็นสตริงของวัตถุปัจจุบัน |
## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | อินสแตนซ์ \"ว่าง\" ของคลาส [Color](./) ซึ่งเป็นอินสแตนซ์ที่ไม่เป็นตัวแทนของสีใด |
## ดูเพิ่มเติม

* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)