---
title: Color
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma cor. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 53
url: /pt/system.drawing/color/
---
## Color classe

Representa uma cor. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../../system/smartptr/) para gerenciar objetos desse tipo.

```cpp
class Color
```

## Métodos

| Método | Descrição |
| --- | --- |
|  [Color](./color/)() | Constrói uma instância \"vazia\" da classe [Color](./) que não representa nenhuma cor. |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | Determina se o objeto atual e os objetos [Color](./) especificados representam a mesma cor. |
| static [Color](./) [FromArgb](./fromargb/)(int) | Constrói uma instância da classe [Color](./) que representa a cor especificada. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | Constrói uma instância da classe [Color](./) que representa a cor especificada. |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | Constrói uma instância da classe [Color](./) que representa a cor especificada com o componente alfa definido como 0xFF. |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | Constrói uma instância da classe [Color](./) que representa a cor especificada. |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | Constrói uma instância da classe [Color](./) que representa a cor conhecida especificada. |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | Constrói uma instância da classe [Color](./) que representa uma cor com o nome especificado. |
| int [get_A](./get_a/)() const | Retorna o valor do componente alfa da cor representada pelo objeto atual. |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF0F8FF. |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFAEBD7. |
| static [Color](./) [get_Aqua](./get_aqua/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00FFFF. |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF7FFFD4. |
| static [Color](./) [get_Azure](./get_azure/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF0FFFF. |
| int [get_B](./get_b/)() const | Retorna o valor do componente azul da cor representada pelo objeto atual. |
| static [Color](./) [get_Beige](./get_beige/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF5F5DC. |
| static [Color](./) [get_Bisque](./get_bisque/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFE4C4. |
| static [Color](./) [get_Black](./get_black/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF000000. |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFEBCD. |
| static [Color](./) [get_Blue](./get_blue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF0000FF. |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF8A2BE2. |
| static [Color](./) [get_Brown](./get_brown/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFA52A2A. |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDEB887. |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF5F9EA0. |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF7FFF00. |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFD2691E. |
| static [Color](./) [get_Coral](./get_coral/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF7F50. |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF6495ED. |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFF8DC. |
| static [Color](./) [get_Crimson](./get_crimson/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDC143C. |
| static [Color](./) [get_Cyan](./get_cyan/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00FFFF. |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00008B. |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF008B8B. |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFB8860B. |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFA9A9A9. |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF006400. |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFBDB76B. |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF8B008B. |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF556B2F. |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF8C00. |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF9932CC. |
| static [Color](./) [get_DarkRed](./get_darkred/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF8B0000. |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFE9967A. |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF8FBC8F. |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF483D8B. |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF2F4F4F. |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00CED1. |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF9400D3. |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF1493. |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00BFFF. |
| static [Color](./) [get_DimGray](./get_dimgray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF696969. |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF1E90FF. |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFB22222. |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFAF0. |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF228B22. |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF00FF. |
| int [get_G](./get_g/)() const | Retorna o valor do componente verde da cor representada pelo objeto atual. |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDCDCDC. |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF8F8FF. |
| static [Color](./) [get_Gold](./get_gold/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFD700. |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDAA520. |
| static [Color](./) [get_Gray](./get_gray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF808080. |
| static [Color](./) [get_Green](./get_green/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF008000. |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFADFF2F. |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF0FFF0. |
| static [Color](./) [get_HotPink](./get_hotpink/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF69B4. |
| static [Color](./) [get_IndianRed](./get_indianred/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFCD5C5C. |
| static [Color](./) [get_Indigo](./get_indigo/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF4B0082. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Retorna um valor que indica se o objeto atual está \"vazio\", ou seja, não representa nenhuma cor. |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | Retorna um valor que determina se a estrutura [Color](./) representa uma cor nomeada ou um membro da enumeração KnownColor. |
| static [Color](./) [get_Ivory](./get_ivory/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFFF0. |
| static [Color](./) [get_Khaki](./get_khaki/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF0E68C. |
| static [Color](./) [get_Lavender](./get_lavender/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFE6E6FA. |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFF0F5. |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF7CFC00. |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFACD. |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFADD8E6. |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF08080. |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFE0FFFF. |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFAFAD2. |
| static [Color](./) [get_LightGray](./get_lightgray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFD3D3D3. |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF90EE90. |
| static [Color](./) [get_LightPink](./get_lightpink/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFB6C1. |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFA07A. |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF20B2AA. |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF87CEFA. |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF778899. |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFB0C4DE. |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFFE0. |
| static [Color](./) [get_Lime](./get_lime/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00FF00. |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF32CD32. |
| static [Color](./) [get_Linen](./get_linen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFAF0E6. |
| static [Color](./) [get_Magenta](./get_magenta/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF00FF. |
| static [Color](./) [get_Maroon](./get_maroon/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF800000. |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF66CDAA. |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF0000CD. |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFBA55D3. |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF9370DB. |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF3CB371. |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF7B68EE. |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00FA9A. |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF48D1CC. |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFC71585. |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF191970. |
| static [Color](./) [get_MintCream](./get_mintcream/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF5FFFA. |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFE4E1. |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFE4B5. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Retorna o nome da cor representada pelo objeto atual. |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFDEAD. |
| static [Color](./) [get_Navy](./get_navy/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF000080. |
| static [Color](./) [get_OldLace](./get_oldlace/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFDF5E6. |
| static [Color](./) [get_Olive](./get_olive/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF808000. |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF6B8E23. |
| static [Color](./) [get_Orange](./get_orange/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFA500. |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF4500. |
| static [Color](./) [get_Orchid](./get_orchid/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDA70D6. |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFEEE8AA. |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF98FB98. |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFAFEEEE. |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDB7093. |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFEFD5. |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFDAB9. |
| static [Color](./) [get_Peru](./get_peru/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFCD853F. |
| static [Color](./) [get_Pink](./get_pink/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFC0CB. |
| static [Color](./) [get_Plum](./get_plum/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFDDA0DD. |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFB0E0E6. |
| static [Color](./) [get_Purple](./get_purple/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF800080. |
| int [get_R](./get_r/)() const | Retorna o valor do componente vermelho da cor representada pelo objeto atual. |
| static [Color](./) [get_Red](./get_red/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF0000. |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFBC8F8F. |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF4169E1. |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF8B4513. |
| static [Color](./) [get_Salmon](./get_salmon/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFA8072. |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF4A460. |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF2E8B57. |
| static [Color](./) [get_SeaShell](./get_seashell/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFF5EE. |
| static [Color](./) [get_Sienna](./get_sienna/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFA0522D. |
| static [Color](./) [get_Silver](./get_silver/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFC0C0C0. |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF87CEEB. |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF6A5ACD. |
| static [Color](./) [get_SlateGray](./get_slategray/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF708090. |
| static [Color](./) [get_Snow](./get_snow/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFAFA. |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF00FF7F. |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF4682B4. |
| static [Color](./) [get_Tan](./get_tan/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFD2B48C. |
| static [Color](./) [get_Teal](./get_teal/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF008080. |
| static [Color](./) [get_Thistle](./get_thistle/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFD8BFD8. |
| static [Color](./) [get_Tomato](./get_tomato/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFF6347. |
| static [Color](./) [get_Transparent](./get_transparent/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #00FFFFFF. |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF40E0D0. |
| static [Color](./) [get_Violet](./get_violet/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFEE82EE. |
| static [Color](./) [get_Wheat](./get_wheat/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF5DEB3. |
| static [Color](./) [get_White](./get_white/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFFFF. |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFF5F5F5. |
| static [Color](./) [get_Yellow](./get_yellow/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FFFFFF00. |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | Retorna uma cor cujo valor ARGB em notação hexadecimal é #FF9ACD32. |
| **float** [GetBrightness](./getbrightness/)() | Retorna o componente de brilho da cor representada pelo objeto atual. |
| int [GetHashCode](./gethashcode/)() const | Retorna o código hash do objeto atual. |
| **float** [GetHue](./gethue/)() | Retorna o valor de matiz (Hue) do modelo Hue-Saturation-Brightness (HSB), em graus, para a cor representada pelo objeto atual. |
| **float** [GetSaturation](./getsaturation/)() | Retorna a saturação do modelo Hue-Saturation-Brightness (HSB) para a cor representada pelo objeto atual. |
| **bool** [IsNull](./isnull/)() const | Sempre retorna false. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Sempre retorna true. |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | Determina se o objeto atual e os objetos [Color](./) especificados representam cores distintas. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Sempre retorna false. |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | Determina se o objeto atual e os objetos [Color](./) especificados representam a mesma cor. |
| int [ToArgb](./toargb/)() const | Retorna um valor ARGB de 32 bits da cor representada pelo objeto atual. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retorna a representação em string do objeto atual. |
## Campos

| Campo | Descrição |
| --- | --- |
| static [Empty](./empty/) | Uma instância \"vazia\" da classe [Color](./), ou seja, uma instância que não representa nenhuma cor. |
## Veja Também

* Namespace [System::Drawing](../)
* Biblioteca [Aspose.Slides](../../)