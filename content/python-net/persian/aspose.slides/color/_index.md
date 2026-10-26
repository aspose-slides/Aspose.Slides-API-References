---
title: Color class
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: یک رنگ ARGB (آلفا، قرمز، سبز، آبی) را نمایش می‌دهد.
type: docs
url: /fa/aspose.slides/color/
net_type: System.Drawing.Color
---
## کلاس Color

نمایانگر یک رنگ ARGB (آلفا، قرمز، سبز، آبی) است. سازگار با .NET `System.Drawing.Color`.

نوع Color اعضای زیر را در اختیار می‌گذارد:

## سازنده‌ها

| Constructor | Description |
| :- | :- |
| [`__init__(self, r=0, g=0, b=0, a=255)`](/slides/python-net/fa/aspose.slides/color/__init__/#int-int-int-int) | رنگی را از مقادیر مؤلفه‌های قرمز، سبز، آبی و آلفای مشخص‌شده می‌سازد. |

## خصوصیات

| Property | Description |
| :- | :- |
| [`a`](/slides/python-net/fa/aspose.slides/color/a/) | مقدار مؤلفه آلفای این رنگ را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`r`](/slides/python-net/fa/aspose.slides/color/r/) | مقدار مؤلفه قرمز این رنگ را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`g`](/slides/python-net/fa/aspose.slides/color/g/) | مقدار مؤلفه سبز این رنگ را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`b`](/slides/python-net/fa/aspose.slides/color/b/) | مقدار مؤلفه آبی این رنگ را باز می‌گرداند.<br/>            فقط‌خواندنی **int**. |
| [`name`](/slides/python-net/fa/aspose.slides/color/name/) | نام این رنگ را باز می‌گرداند.<br/>            برای یک رنگ نام‌دار (یک ثابت نام‌دار مانند `Color.red` یا رنگی که با [`from_name`](/slides/python-net/fa/aspose.slides/color/from_name/) ساخته شده) نام .NET باز می‌گردد، مثلا `"Red"` یا `"LightBlue"`.<br/>            برای هر رنگ دیگر مقدار ARGB به‌صورت رشته هگزادسیمال کوچک بدون پر شدن صفر، مثلا `"ffff0000"` باز می‌گردد. `Color.empty.name` برابر `"0"` است.<br/>            فقط‌خواندنی **str**. |
| [`is_empty`](/slides/python-net/fa/aspose.slides/color/is_empty/) | تعیین می‌کند آیا این رنگ `Color.empty` است.<br/>            وقتی رنگی با تمام مؤلفه‌ها برابر صفر با [`from_argb`](/slides/python-net/fa/aspose.slides/color/from_argb/) ساخته شود، مقدار `False` باز می‌گردد.<br/>            فقط‌خواندنی **bool**. |
| [`is_known_color`](/slides/python-net/fa/aspose.slides/color/is_known_color/) | تعیین می‌کند آیا این رنگ یکی از رنگ‌های پیش‌تعریف‌شده .NET `KnownColor` است (یک رنگ نام‌دار یا یک رنگ سیستمی).<br/>            فقط‌خواندنی **bool**. |
| [`is_named_color`](/slides/python-net/fa/aspose.slides/color/is_named_color/) | تعیین می‌کند آیا این رنگ دارای نامی است: از ثابت نام‌دار مانند `Color.red`، با [`from_name`](/slides/python-net/fa/aspose.slides/color/from_name/) ساخته شده یا از کتابخانه به‌صورت رنگ نام‌دار بازگردانده شده است.<br/>            فقط‌خواندنی **bool**. |
| [`is_system_color`](/slides/python-net/fa/aspose.slides/color/is_system_color/) | تعیین می‌کند آیا این رنگ یک رنگ سیستمی است: رنگی که برای یک عنصر نمایش ویندوز مانند `Control` یا `ActiveBorder` استفاده می‌شود.<br/>            رنگ‌های سیستمی به‌صورت ویژگی‌های `Color` در دسترس نیستند و فقط می‌توانند با [`from_known_color`](/slides/python-net/fa/aspose.slides/color/from_known_color/) دریافت شوند یا از کتابخانه بازگردانده شوند.<br/>            فقط‌خواندنی **bool**. |

## متدها

| Method | Description |
| :- | :- |
| [`from_argb(argb)`](/slides/python-net/fa/aspose.slides/color/from_argb/#int) | رنگی را از یک مقدار ۳۲ بیتی ARGB می‌سازد. |
| [`from_argb(alpha, base_color)`](/slides/python-net/fa/aspose.slides/color/from_argb/#int-color) | رنگی را از مقدار آلفای مشخص‌شده و رنگ پایه می‌سازد. |
| [`from_argb(red, green, blue)`](/slides/python-net/fa/aspose.slides/color/from_argb/#int-int-int) | رنگی کدر (آلفا برابر ۲۵۵) را از مقادیر قرمز، سبز و آبی مشخص‌شده می‌سازد. |
| [`from_argb(alpha, red, green, blue)`](/slides/python-net/fa/aspose.slides/color/from_argb/#int-int-int-int) | رنگی را از چهار مقدار مؤلفه ARGB (آلفا، قرمز، سبز و آبی) می‌سازد. |
| [`from_known_color(known_color)`](/slides/python-net/fa/aspose.slides/color/from_known_color/#knowncolor) | رنگی را از رنگ پیش‌تعریف‌شدهٔ مشخص شده می‌سازد. |
| [`from_name(name)`](/slides/python-net/fa/aspose.slides/color/from_name/#str) | رنگی را از نام رنگ پیش‌تعریف‌شدهٔ مشخص شده می‌سازد. |
| [`from_rgb(r, g, b)`](/slides/python-net/fa/aspose.slides/color/from_rgb/#int-int-int) | رنگی کدر (آلفا برابر ۲۵۵) را از مقادیر قرمز، سبز و آبی مشخص‌شده می‌سازد. |
| [`get_brightness(self)`](/slides/python-net/fa/aspose.slides/color/get_brightness/#) | مقدار روشنایی (Lightness) در سیستم HSL برای این رنگ را باز می‌گرداند. |
| [`get_hue(self)`](/slides/python-net/fa/aspose.slides/color/get_hue/#) | مقدار رنگ (Hue) در سیستم HSL برحسب درجه برای این رنگ را باز می‌گرداند. |
| [`get_saturation(self)`](/slides/python-net/fa/aspose.slides/color/get_saturation/#) | مقدار اشباع (Saturation) در سیستم HSL برای این رنگ را باز می‌گرداند. |
| [`to_argb(self)`](/slides/python-net/fa/aspose.slides/color/to_argb/#) | مقدار ۳۲ بیتی ARGB این رنگ را باز می‌گرداند. |
| [`to_known_color(self)`](/slides/python-net/fa/aspose.slides/color/to_known_color/#) | مقدار `KnownColor` این رنگ را باز می‌گرداند. |
| [`to_string(self)`](/slides/python-net/fa/aspose.slides/color/to_string/#) | این رنگ را به یک رشتهٔ قابل‌خواندن برای انسان تبدیل می‌کند. همان متن توسط `str()` و `repr()` بازگردانده می‌شود. |

### ملاحظات

رنگ‌ها با مؤلفه‌های ARGB خود با عملگر `==` مقایسه می‌شوند و می‌توانند به‌عنوان کلیدهای دیکشنری یا عضوهای مجموعه استفاده شوند.

رنگ‌های پیش‌تعریف‌شده (141 رنگ نام‌دار .NET `KnownColor`، `Color.transparent` و `Color.empty`) به‌صورت ویژگی‌های کلاس به فرم snake_case در دسترس‌اند، برای مثال `Color.red`، `Color.light_blue` یا `Color.dark_slate_gray` (به [Named colors](#named-colors) زیر نگاه کنید). همچنین می‌توان آن‌ها را مانند متد فراخوانی کرد (`Color.red()`)، که همان رنگ را باز می‌گرداند.

### مثال‌ها

```python
import aspose.slides as slides

with slides.Presentation() as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 50, 50, 200, 100)
    shape.fill_format.fill_type = slides.FillType.SOLID
    shape.fill_format.solid_fill_color.color = slides.Color.from_argb(255, 30, 144, 255)
    shape.line_format.fill_format.solid_fill_color.color = slides.Color.dark_blue

    color = slides.Color.from_name("light_blue")
    print(color.name, color.to_argb(), color.is_named_color)  # LightBlue -5383962 درست
    print(slides.Color(255, 0, 0) == slides.Color.red)         # درست
```

### رنگ‌های نام‌دار

| ویژگی | نام .NET | ARGB |
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

### همچنین ببینید
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)