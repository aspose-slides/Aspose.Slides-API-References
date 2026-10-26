---
title: Color
second_title: Referensi API Aspose.Slides untuk C++
description: "Mewakili sebuah warna. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan kelas System::SmartPtr untuk mengelola objek tipe ini."
type: docs
weight: 53
url: /id/system.drawing/color/
---
## Color kelas


Mewakili sebuah warna. Tipe ini harus dialokasikan pada stack dan diteruskan ke fungsi dengan nilai atau referensi. Jangan pernah menggunakan [System::SmartPtr](../../system/smartptr/) kelas untuk mengelola objek tipe ini.

```cpp
class Color
```

## Metode

| Method | Deskripsi |
| --- | --- |
|  [Color](./color/)() | Membuat sebuah instance "kosong" dari [Color](./) kelas yang tidak mewakili warna apa pun. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Menentukan apakah objek [Color](./) saat ini dan yang ditentukan mewakili warna yang sama. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna yang ditentukan. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna yang ditentukan. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna yang ditentukan dengan komponen alfa disetel ke 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna yang ditentukan. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna yang diketahui yang ditentukan. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Membuat sebuah instance dari [Color](./) kelas yang mewakili warna dengan nama yang ditentukan. |
| int [get_A](./get_a/)() const | Mengembalikan nilai komponen alfa dari warna yang diwakili oleh objek saat ini. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF0FFFF. |
| int [get_B](./get_b/)() const | Mengembalikan nilai komponen biru dari warna yang diwakili oleh objek saat ini. |
| static [Color](./) [get_Beige](./get_beige/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF00FF. |
| int [get_G](./get_g/)() const | Mengembalikan nilai komponen hijau dari warna yang diwakili oleh objek saat ini. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Mengembalikan nilai yang menunjukkan apakah objek saat ini "kosong", yaitu tidak mewakili warna apa pun. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Mengembalikan nilai yang menentukan apakah struktur [Color](./) mewakili warna bernama atau anggota enumerasi KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Mengembalikan nama warna yang diwakili oleh objek saat ini. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF800080. |
| int [get_R](./get_r/)() const | Mengembalikan nilai komponen merah dari warna yang diwakili oleh objek saat ini. |
| static [Color](./) [get_Red](./get_red/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Mengembalikan sebuah warna dengan nilai ARGB dalam notasi heksadesimal #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Mengembalikan komponen kecerahan dari warna yang diwakili oleh objek saat ini. |
| int [GetHashCode](./gethashcode/)() const | Mengembalikan kode hash dari objek saat ini. |
| **float** [GetHue](./gethue/)() | Mengembalikan nilai hue Hue-Saturation-Brightness (HSB) dalam derajat untuk warna yang diwakili oleh objek saat ini. |
| **float** [GetSaturation](./getsaturation/)() | Mengembalikan nilai saturasi Hue-Saturation-Brightness (HSB) untuk warna yang diwakili oleh objek saat ini. |
| **bool** [IsNull](./isnull/)() const | Selalu mengembalikan false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Selalu mengembalikan true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Menentukan apakah objek [Color](./) saat ini dan yang ditentukan mewakili warna yang berbeda. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Selalu mengembalikan false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Menentukan apakah objek [Color](./) saat ini dan yang ditentukan mewakili warna yang sama. |
| int [ToArgb](./toargb/)() const | Mengembalikan nilai ARGB 32-bit dari warna yang diwakili oleh objek saat ini. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mengembalikan representasi string dari objek saat ini. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static [Empty](./empty/) | Sebuah instance "kosong" dari [Color](./) kelas, yaitu instance yang tidak mewakili warna apa pun. |
## Lihat Juga

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)