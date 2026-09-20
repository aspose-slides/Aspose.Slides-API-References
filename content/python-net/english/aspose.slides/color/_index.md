---
title: Color class
second_title: Aspose.Slides for Python via .NET API Reference
description: Represents an ARGB (alpha, red, green, blue) color.
type: docs
url: /aspose.slides/color/
net_type: System.Drawing.Color
---


## Color class

Represents an ARGB (alpha, red, green, blue) color. Compatible with .NET `System.Drawing.Color`.

The Color type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, r=0, g=0, b=0, a=255)`](/slides/python-net/aspose.slides/color/__init__/#int-int-int-int) | Creates a color from the specified red, green, blue and alpha component values. |

## Properties

| Property | Description |
| :- | :- |
| [`a`](/slides/python-net/aspose.slides/color/a/) | Gets the alpha component value of this color.<br/>            Read-only **int**. |
| [`r`](/slides/python-net/aspose.slides/color/r/) | Gets the red component value of this color.<br/>            Read-only **int**. |
| [`g`](/slides/python-net/aspose.slides/color/g/) | Gets the green component value of this color.<br/>            Read-only **int**. |
| [`b`](/slides/python-net/aspose.slides/color/b/) | Gets the blue component value of this color.<br/>            Read-only **int**. |
| [`name`](/slides/python-net/aspose.slides/color/name/) | Gets the name of this color.<br/>            For a named color (a named constant such as `Color.red`, or a color created with [`from_name`](/slides/python-net/aspose.slides/color/from_name/)) the .NET name is returned, e.g. `"Red"` or `"LightBlue"`.<br/>            For any other color the ARGB value is returned as lowercase hexadecimal without zero padding, e.g. `"ffff0000"`. `Color.empty.name` is `"0"`.<br/>            Read-only **str**. |
| [`is_empty`](/slides/python-net/aspose.slides/color/is_empty/) | Specifies whether this color is `Color.empty`.<br/>            Returns `False` for a color with all components equal to zero created with [`from_argb`](/slides/python-net/aspose.slides/color/from_argb/).<br/>            Read-only **bool**. |
| [`is_known_color`](/slides/python-net/aspose.slides/color/is_known_color/) | Specifies whether this color is one of the predefined .NET `KnownColor` colors (a named color or a system color).<br/>            Read-only **bool**. |
| [`is_named_color`](/slides/python-net/aspose.slides/color/is_named_color/) | Specifies whether this color carries a name: it was created from a named constant such as `Color.red`, with [`from_name`](/slides/python-net/aspose.slides/color/from_name/), or was returned from the library as a named color.<br/>            Read-only **bool**. |
| [`is_system_color`](/slides/python-net/aspose.slides/color/is_system_color/) | Specifies whether this color is a system color: a color used for a Windows display element, such as `Control` or `ActiveBorder`.<br/>            System colors are not exposed as `Color` attributes and can only be obtained with [`from_known_color`](/slides/python-net/aspose.slides/color/from_known_color/) or returned from the library.<br/>            Read-only **bool**. |

## Methods

| Method | Description |
| :- | :- |
| [`from_argb(argb)`](/slides/python-net/aspose.slides/color/from_argb/#int) | Creates a color from a 32-bit ARGB value. |
| [`from_argb(alpha, base_color)`](/slides/python-net/aspose.slides/color/from_argb/#int-color) | Creates a color from the specified alpha value and base color. |
| [`from_argb(red, green, blue)`](/slides/python-net/aspose.slides/color/from_argb/#int-int-int) | Creates an opaque color (alpha is 255) from the specified red, green and blue values. |
| [`from_argb(alpha, red, green, blue)`](/slides/python-net/aspose.slides/color/from_argb/#int-int-int-int) | Creates a color from the four ARGB component (alpha, red, green, and blue) values. |
| [`from_known_color(known_color)`](/slides/python-net/aspose.slides/color/from_known_color/#knowncolor) | Creates a color from the specified predefined color. |
| [`from_name(name)`](/slides/python-net/aspose.slides/color/from_name/#str) | Creates a color from the specified name of a predefined color. |
| [`from_rgb(r, g, b)`](/slides/python-net/aspose.slides/color/from_rgb/#int-int-int) | Creates an opaque color (alpha is 255) from the specified red, green and blue values. |
| [`get_brightness(self)`](/slides/python-net/aspose.slides/color/get_brightness/#) | Gets the hue-saturation-lightness (HSL) lightness value for this color. |
| [`get_hue(self)`](/slides/python-net/aspose.slides/color/get_hue/#) | Gets the hue-saturation-lightness (HSL) hue value, in degrees, for this color. |
| [`get_saturation(self)`](/slides/python-net/aspose.slides/color/get_saturation/#) | Gets the hue-saturation-lightness (HSL) saturation value for this color. |
| [`to_argb(self)`](/slides/python-net/aspose.slides/color/to_argb/#) | Gets the 32-bit ARGB value of this color. |
| [`to_known_color(self)`](/slides/python-net/aspose.slides/color/to_known_color/#) | Gets the `KnownColor` value of this color. |
| [`to_string(self)`](/slides/python-net/aspose.slides/color/to_string/#) | Converts this color to a human-readable string. The same text is returned by `str()` and `repr()`. |


### Remarks

Colors are compared by their ARGB components with `==` and can be used as dictionary keys or set members.

The predefined colors (the 141 named .NET `KnownColor` colors, `Color.transparent` and `Color.empty`) are available as class attributes spelled in snake_case, for example `Color.red`, `Color.light_blue` or `Color.dark_slate_gray` (see [Named colors](#named-colors) below). They can also be called like methods (`Color.red()`), which returns the same color.

### Examples

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

### Named colors

| Attribute | .NET name | ARGB |
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


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

