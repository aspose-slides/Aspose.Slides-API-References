---
title: Color class
second_title: Aspose.Slides for Python via .NET API 참조
description: ARGB(alpha, red, green, blue) 색상을 나타냅니다.
type: docs
url: /ko/aspose.slides/color/
net_type: System.Drawing.Color
---
## Color 클래스

ARGB(alpha, red, green, blue) 색상을 나타냅니다. .NET `System.Drawing.Color`와 호환됩니다.

`Color` 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self, r=0, g=0, b=0, a=255)`](/slides/python-net/ko/aspose.slides/color/__init__/#int-int-int-int) | 지정된 빨강, 초록, 파랑 및 알파 구성 요소 값으로 색상을 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`a`](/slides/python-net/ko/aspose.slides/color/a/) | 이 색상의 알파 구성 요소 값을 가져옵니다.<br/>            읽기 전용 **int**. |
| [`r`](/slides/python-net/ko/aspose.slides/color/r/) | 이 색상의 빨강 구성 요소 값을 가져옵니다.<br/>            읽기 전용 **int**. |
| [`g`](/slides/python-net/ko/aspose.slides/color/g/) | 이 색상의 초록 구성 요소 값을 가져옵니다.<br/>            읽기 전용 **int**. |
| [`b`](/slides/python-net/ko/aspose.slides/color/b/) | 이 색상의 파랑 구성 요소 값을 가져옵니다.<br/>            읽기 전용 **int**. |
| [`name`](/slides/python-net/ko/aspose.slides/color/name/) | 이 색상의 이름을 가져옵니다.<br/>            명명된 색상(예: `Color.red`와 같은 명명된 상수 또는 [`from_name`](/slides/python-net/ko/aspose.slides/color/from_name/)으로 생성된 색상)의 경우 .NET 이름이 반환됩니다. 예: `"Red"` 또는 `"LightBlue"`.<br/>            기타 색상의 경우 ARGB 값이 앞쪽 0 없이 소문자 16진수 문자열로 반환됩니다. 예: `"ffff0000"`. `Color.empty.name`은 `"0"`입니다.<br/>            읽기 전용 **str**. |
| [`is_empty`](/slides/python-net/ko/aspose.slides/color/is_empty/) | 이 색상이 `Color.empty`인지 지정합니다.<br/>            [`from_argb`](/slides/python-net/ko/aspose.slides/color/from_argb/)으로 생성된 모든 구성 요소가 0인 색상의 경우 `False`를 반환합니다.<br/>            읽기 전용 **bool**. |
| [`is_known_color`](/slides/python-net/ko/aspose.slides/color/is_known_color/) | 이 색상이 미리 정의된 .NET `KnownColor` 색상(명명된 색상 또는 시스템 색상) 중 하나인지 지정합니다.<br/>            읽기 전용 **bool**. |
| [`is_named_color`](/slides/python-net/ko/aspose.slides/color/is_named_color/) | 이 색상이 이름을 가지고 있는지 지정합니다: `Color.red`와 같은 명명된 상수로 [`from_name`](/slides/python-net/ko/aspose.slides/color/from_name/)를 사용해 생성되었거나, 라이브러리에서 명명된 색상으로 반환된 경우.<br/>            읽기 전용 **bool**. |
| [`is_system_color`](/slides/python-net/ko/aspose.slides/color/is_system_color/) | 이 색상이 시스템 색상인지 지정합니다: `Control`이나 `ActiveBorder`와 같은 Windows 표시 요소에 사용되는 색상입니다.<br/>            시스템 색상은 `Color` 속성으로 노출되지 않으며 [`from_known_color`](/slides/python-net/ko/aspose.slides/color/from_known_color/)를 통해서만 얻을 수 있거나 라이브러리에서 반환됩니다.<br/>            읽기 전용 **bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`from_argb(argb)`](/slides/python-net/ko/aspose.slides/color/from_argb/#int) | 32비트 ARGB 값으로 색상을 생성합니다. |
| [`from_argb(alpha, base_color)`](/slides/python-net/ko/aspose.slides/color/from_argb/#int-color) | 지정된 알파 값과 기본 색상으로 색상을 생성합니다. |
| [`from_argb(red, green, blue)`](/slides/python-net/ko/aspose.slides/color/from_argb/#int-int-int) | 지정된 빨강, 초록, 파랑 값으로 불투명 색상(알파가 255)을 생성합니다. |
| [`from_argb(alpha, red, green, blue)`](/slides/python-net/ko/aspose.slides/color/from_argb/#int-int-int-int) | 네 개의 ARGB 구성 요소(알파, 빨강, 초록, 파랑) 값으로 색상을 생성합니다. |
| [`from_known_color(known_color)`](/slides/python-net/ko/aspose.slides/color/from_known_color/#knowncolor) | 지정된 미리 정의된 색상으로 색상을 생성합니다. |
| [`from_name(name)`](/slides/python-net/ko/aspose.slides/color/from_name/#str) | 지정된 미리 정의된 색상의 이름으로 색상을 생성합니다. |
| [`from_rgb(r, g, b)`](/slides/python-net/ko/aspose.slides/color/from_rgb/#int-int-int) | 지정된 빨강, 초록, 파랑 값으로 불투명 색상(알파가 255)을 생성합니다. |
| [`get_brightness(self)`](/slides/python-net/ko/aspose.slides/color/get_brightness/#) | 이 색상의 색조-채도-명도(HSL) 명도 값을 가져옵니다. |
| [`get_hue(self)`](/slides/python-net/ko/aspose.slides/color/get_hue/#) | 이 색상의 색조-채도-명도(HSL) 색상 값(도)을 가져옵니다. |
| [`get_saturation(self)`](/slides/python-net/ko/aspose.slides/color/get_saturation/#) | 이 색상의 색조-채도-명도(HSL) 채도 값을 가져옵니다. |
| [`to_argb(self)`](/slides/python-net/ko/aspose.slides/color/to_argb/#) | 이 색상의 32비트 ARGB 값을 가져옵니다. |
| [`to_known_color(self)`](/slides/python-net/ko/aspose.slides/color/to_known_color/#) | 이 색상의 `KnownColor` 값을 가져옵니다. |
| [`to_string(self)`](/slides/python-net/ko/aspose.slides/color/to_string/#) | 이 색상을 사람이 읽을 수 있는 문자열로 변환합니다. 동일한 텍스트가 `str()` 및 `repr()`에 의해 반환됩니다. |

### 비고

색상은 `==` 연산자를 사용하여 ARGB 구성 요소로 비교되며 딕셔너리 키 또는 집합 원소로 사용할 수 있습니다.

미리 정의된 색상(141개의 명명된 .NET `KnownColor` 색상, `Color.transparent` 및 `Color.empty`)은 snake_case 형태의 클래스 속성으로 제공됩니다. 예를 들어 `Color.red`, `Color.light_blue` 또는 `Color.dark_slate_gray` (아래 [Named colors](#named-colors) 참조). 또한 메서드처럼 호출할 수도 있으며(`Color.red()`), 동일한 색상을 반환합니다.

### 예제

```python
import aspose.slides as slides

with slides.Presentation() as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 50, 50, 200, 100)
    shape.fill_format.fill_type = slides.FillType.SOLID
    shape.fill_format.solid_fill_color.color = slides.Color.from_argb(255, 30, 144, 255)
    shape.line_format.fill_format.solid_fill_color.color = slides.Color.dark_blue

    color = slides.Color.from_name("light_blue")
    print(color.name, color.to_argb(), color.is_named_color)  # LightBlue -5383962 True
    print(slides.Color(255, 0, 0) == slides.Color.red)         # True
```

### 명명된 색상

| 속성 | .NET 이름 | ARGB |
| :- | :- | :- |
| `Color.empty` | Empty | `00000000` |
| `Color.alice_blue` | AliceBlue | `FFF0F8FF` |
| `Color.antique_white` | AntiqueWhite | `FFFAEBD7` |
| `Color.aqua` | Aqua | `FF00FFFF` |
| `Color.aquamarine` | Aquamarine | `FF7FFFD4` |
| `Color.azure` | Azure | `FFF0FFFF` |
| `Color.beige` | Beige | `FFF5F5DC` |
| `Color.bisque` | Bisque | `FFFFE4C4` |
| `Color.black` | Black | `FF000000` |
| `Color.blanched_almond` | BlanchedAlmond | `FFFFEBCD` |
| `Color.blue` | Blue | `FF0000FF` |
| `Color.blue_violet` | BlueViolet | `FF8A2BE2` |
| `Color.brown` | Brown | `FFA52A2A` |
| `Color.burly_wood` | BurlyWood | `FFDEB887` |
| `Color.cadet_blue` | CadetBlue | `FF5F9EA0` |
| `Color.chartreuse` | Chartreuse | `FF7FFF00` |
| `Color.chocolate` | Chocolate | `FFD2691E` |
| `Color.coral` | Coral | `FFFF7F50` |
| `Color.cornflower_blue` | CornflowerBlue | `FF6495ED` |
| `Color.cornsilk` | Cornsilk | `FFFFF8DC` |
| `Color.crimson` | Crimson | `FFDC143C` |
| `Color.cyan` | Cyan | `FF00FFFF` |
| `Color.dark_blue` | DarkBlue | `FF00008B` |
| `Color.dark_cyan` | DarkCyan | `FF008B8B` |
| `Color.dark_goldenrod` | DarkGoldenrod | `FFB8860B` |
| `Color.dark_gray` | DarkGray | `FFA9A9A9` |
| `Color.dark_green` | DarkGreen | `FF006400` |
| `Color.dark_khaki` | DarkKhaki | `FFBDB76B` |
| `Color.dark_magenta` | DarkMagenta | `FF8B008B` |
| `Color.dark_olive_green` | DarkOliveGreen | `FF556B2F` |
| `Color.dark_orange` | DarkOrange | `FFFF8C00` |
| `Color.dark_orchid` | DarkOrchid | `FF9932CC` |
| `Color.dark_red` | DarkRed | `FF8B0000` |
| `Color.dark_salmon` | DarkSalmon | `FFE9967A` |
| `Color.dark_sea_green` | DarkSeaGreen | `FF8FBC8F` |
| `Color.dark_slate_blue` | DarkSlateBlue | `FF483D8B` |
| `Color.dark_slate_gray` | DarkSlateGray | `FF2F4F4F` |
| `Color.dark_turquoise` | DarkTurquoise | `FF00CED1` |
| `Color.dark_violet` | DarkViolet | `FF9400D3` |
| `Color.deep_pink` | DeepPink | `FFFF1493` |
| `Color.deep_sky_blue` | DeepSkyBlue | `FF00BFFF` |
| `Color.dim_gray` | DimGray | `FF696969` |
| `Color.dodger_blue` | DodgerBlue | `FF1E90FF` |
| `Color.firebrick` | Firebrick | `FFB22222` |
| `Color.floral_white` | FloralWhite | `FFFFFAF0` |
| `Color.forest_green` | ForestGreen | `FF228B22` |
| `Color.fuchsia` | Fuchsia | `FFFF00FF` |
| `Color.gainsboro` | Gainsboro | `FFDCDCDC` |
| `Color.ghost_white` | GhostWhite | `FFF8F8FF` |
| `Color.gold` | Gold | `FFFFD700` |
| `Color.goldenrod` | Goldenrod | `FFDAA520` |
| `Color.gray` | Gray | `FF808080` |
| `Color.green` | Green | `FF008000` |
| `Color.green_yellow` | GreenYellow | `FFADFF2F` |
| `Color.honeydew` | Honeydew | `FFF0FFF0` |
| `Color.hot_pink` | HotPink | `FFFF69B4` |
| `Color.indian_red` | IndianRed | `FFCD5C5C` |
| `Color.indigo` | Indigo | `FF4B0082` |
| `Color.ivory` | Ivory | `FFFFFFF0` |
| `Color.khaki` | Khaki | `FFF0E68C` |
| `Color.lavender` | Lavender | `FFE6E6FA` |
| `Color.lavender_blush` | LavenderBlush | `FFFFF0F5` |
| `Color.lawn_green` | LawnGreen | `FF7CFC00` |
| `Color.lemon_chiffon` | LemonChiffon | `FFFFFACD` |
| `Color.light_blue` | LightBlue | `FFADD8E6` |
| `Color.light_coral` | LightCoral | `FFF08080` |
| `Color.light_cyan` | LightCyan | `FFE0FFFF` |
| `Color.light_goldenrod_yellow` | LightGoldenrodYellow | `FFFAFAD2` |
| `Color.light_gray` | LightGray | `FFD3D3D3` |
| `Color.light_green` | LightGreen | `FF90EE90` |
| `Color.light_pink` | LightPink | `FFFFB6C1` |
| `Color.light_salmon` | LightSalmon | `FFFFA07A` |
| `Color.light_sea_green` | LightSeaGreen | `FF20B2AA` |
| `Color.light_sky_blue` | LightSkyBlue | `FF87CEFA` |
| `Color.light_slate_gray` | LightSlateGray | `FF778899` |
| `Color.light_steel_blue` | LightSteelBlue | `FFB0C4DE` |
| `Color.light_yellow` | LightYellow | `FFFFFFE0` |
| `Color.lime` | Lime | `FF00FF00` |
| `Color.lime_green` | LimeGreen | `FF32CD32` |
| `Color.linen` | Linen | `FFFAF0E6` |
| `Color.magenta` | Magenta | `FFFF00FF` |
| `Color.maroon` | Maroon | `FF800000` |
| `Color.medium_aquamarine` | MediumAquamarine | `FF66CDAA` |
| `Color.medium_blue` | MediumBlue | `FF0000CD` |
| `Color.medium_orchid` | MediumOrchid | `FFBA55D3` |
| `Color.medium_purple` | MediumPurple | `FF9370DB` |
| `Color.medium_sea_green` | MediumSeaGreen | `FF3CB371` |
| `Color.medium_slate_blue` | MediumSlateBlue | `FF7B68EE` |
| `Color.medium_spring_green` | MediumSpringGreen | `FF00FA9A` |
| `Color.medium_turquoise` | MediumTurquoise | `FF48D1CC` |
| `Color.medium_violet_red` | MediumVioletRed | `FFC71585` |
| `Color.midnight_blue` | MidnightBlue | `FF191970` |
| `Color.mint_cream` | MintCream | `FFF5FFFA` |
| `Color.misty_rose` | MistyRose | `FFFFE4E1` |
| `Color.moccasin` | Moccasin | `FFFFE4B5` |
| `Color.navajo_white` | NavajoWhite | `FFFFDEAD` |
| `Color.navy` | Navy | `FF000080` |
| `Color.old_lace` | OldLace | `FFFDF5E6` |
| `Color.olive` | Olive | `FF808000` |
| `Color.olive_drab` | OliveDrab | `FF6B8E23` |
| `Color.orange` | Orange | `FFFFA500` |
| `Color.orange_red` | OrangeRed | `FFFF4500` |
| `Color.orchid` | Orchid | `FFDA70D6` |
| `Color.pale_goldenrod` | PaleGoldenrod | `FFEEE8AA` |
| `Color.pale_green` | PaleGreen | `FF98FB98` |
| `Color.pale_turquoise` | PaleTurquoise | `FFAFEEEE` |
| `Color.pale_violet_red` | PaleVioletRed | `FFDB7093` |
| `Color.papaya_whip` | PapayaWhip | `FFFFEFD5` |
| `Color.peach_puff` | PeachPuff | `FFFFDAB9` |
| `Color.peru` | Peru | `FFCD853F` |
| `Color.pink` | Pink | `FFFFC0CB` |
| `Color.plum` | Plum | `FFDDA0DD` |
| `Color.powder_blue` | PowderBlue | `FFB0E0E6` |
| `Color.purple` | Purple | `FF800080` |
| `Color.rebecca_purple` | RebeccaPurple | `FF663399` |
| `Color.red` | Red | `FFFF0000` |
| `Color.rosy_brown` | RosyBrown | `FFBC8F8F` |
| `Color.royal_blue` | RoyalBlue | `FF4169E1` |
| `Color.saddle_brown` | SaddleBrown | `FF8B4513` |
| `Color.salmon` | Salmon | `FFFA8072` |
| `Color.sandy_brown` | SandyBrown | `FFF4A460` |
| `Color.sea_green` | SeaGreen | `FF2E8B57` |
| `Color.sea_shell` | SeaShell | `FFFFF5EE` |
| `Color.sienna` | Sienna | `FFA0522D` |
| `Color.silver` | Silver | `FFC0C0C0` |
| `Color.sky_blue` | SkyBlue | `FF87CEEB` |
| `Color.slate_blue` | SlateBlue | `FF6A5ACD` |
| `Color.slate_gray` | SlateGray | `FF708090` |
| `Color.snow` | Snow | `FFFFFAFA` |
| `Color.spring_green` | SpringGreen | `FF00FF7F` |
| `Color.steel_blue` | SteelBlue | `FF4682B4` |
| `Color.tan` | Tan | `FFD2B48C` |
| `Color.teal` | Teal | `FF008080` |
| `Color.thistle` | Thistle | `FFD8BFD8` |
| `Color.tomato` | Tomato | `FFFF6347` |
| `Color.transparent` | Transparent | `00FFFFFF` |
| `Color.turquoise` | Turquoise | `FF40E0D0` |
| `Color.violet` | Violet | `FFEE82EE` |
| `Color.wheat` | Wheat | `FFF5DEB3` |
| `Color.white` | White | `FFFFFFFF` |
| `Color.white_smoke` | WhiteSmoke | `FFF5F5F5` |
| `Color.yellow` | Yellow | `FFFFFF00` |
| `Color.yellow_green` | YellowGreen | `FF9ACD32` |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)