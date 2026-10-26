---
title: Color class
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: Reprezentuje kolor ARGB (alpha, red, green, blue).
type: docs
url: /pl/aspose.slides/color/
net_type: System.Drawing.Color
---
## Klasa Color

Reprezentuje kolor ARGB (alpha, red, green, blue). Zgodny z .NET `System.Drawing.Color`.

Typ Color udostępnia następujące elementy:

## Konstruktory

| Konstruktor | Opis |
| :- | :- |
| [`__init__(self, r=0, g=0, b=0, a=255)`](/slides/python-net/pl/aspose.slides/color/__init__/#int-int-int-int) | Tworzy kolor z podanymi wartościami składowych czerwonej, zielonej, niebieskiej i alfa. |

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`a`](/slides/python-net/pl/aspose.slides/color/a/) | Pobiera wartość składowej alfa tego koloru.<br/>            Tylko do odczytu **int**. |
| [`r`](/slides/python-net/pl/aspose.slides/color/r/) | Pobiera wartość składowej czerwonej tego koloru.<br/>            Tylko do odczytu **int**. |
| [`g`](/slides/python-net/pl/aspose.slides/color/g/) | Pobiera wartość składowej zielonej tego koloru.<br/>            Tylko do odczytu **int**. |
| [`b`](/slides/python-net/pl/aspose.slides/color/b/) | Pobiera wartość składowej niebieskiej tego koloru.<br/>            Tylko do odczytu **int**. |
| [`name`](/slides/python-net/pl/aspose.slides/color/name/) | Pobiera nazwę tego koloru.<br/>            Dla nazwanego koloru (nazwanej stałej takiej jak `Color.red` lub koloru utworzonego przy użyciu [`from_name`](/slides/python-net/pl/aspose.slides/color/from_name/)) zwracana jest nazwa .NET, np. `"Red"` lub `"LightBlue"`.<br/>            Dla każdego innego koloru zwracana jest wartość ARGB jako małe cyfry szesnastkowe bez wiodących zer, np. `"ffff0000"`. `Color.empty.name` to `"0"`.<br/>            Tylko do odczytu **str**. |
| [`is_empty`](/slides/python-net/pl/aspose.slides/color/is_empty/) | Określa, czy ten kolor jest `Color.empty`.<br/>            Zwraca `False` dla koloru, którego wszystkie składowe są równe zero i został utworzony przy użyciu [`from_argb`](/slides/python-net/pl/aspose.slides/color/from_argb/).<br/>            Tylko do odczytu **bool**. |
| [`is_known_color`](/slides/python-net/pl/aspose.slides/color/is_known_color/) | Określa, czy ten kolor jest jednym z wbudowanych .NET `KnownColor` (nazwany kolor lub kolor systemowy).<br/>            Tylko do odczytu **bool**. |
| [`is_named_color`](/slides/python-net/pl/aspose.slides/color/is_named_color/) | Określa, czy ten kolor posiada nazwę: został utworzony z nazwaną stałą taką jak `Color.red`, przy użyciu [`from_name`](/slides/python-net/pl/aspose.slides/color/from_name/), lub został zwrócony z biblioteki jako nazwany kolor.<br/>            Tylko do odczytu **bool**. |
| [`is_system_color`](/slides/python-net/pl/aspose.slides/color/is_system_color/) | Określa, czy ten kolor jest kolorem systemowym: kolorem używanym dla elementu wyświetlania w Windows, takim jak `Control` lub `ActiveBorder`.<br/>            Kolory systemowe nie są udostępniane jako atrybuty `Color` i można je uzyskać tylko przy pomocy [`from_known_color`](/slides/python-net/pl/aspose.slides/color/from_known_color/) lub zwrócić z biblioteki.<br/>            Tylko do odczytu **bool**. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`from_argb(argb)`](/slides/python-net/pl/aspose.slides/color/from_argb/#int) | Tworzy kolor z 32-bitowej wartości ARGB. |
| [`from_argb(alpha, base_color)`](/slides/python-net/pl/aspose.slides/color/from_argb/#int-color) | Tworzy kolor z podanej wartości alfa i koloru bazowego. |
| [`from_argb(red, green, blue)`](/slides/python-net/pl/aspose.slides/color/from_argb/#int-int-int) | Tworzy nieprzezroczysty kolor (alfa = 255) z podanymi wartościami czerwonej, zielonej i niebieskiej. |
| [`from_argb(alpha, red, green, blue)`](/slides/python-net/pl/aspose.slides/color/from_argb/#int-int-int-int) | Tworzy kolor z czterech wartości składowych ARGB (alfa, red, green, blue). |
| [`from_known_color(known_color)`](/slides/python-net/pl/aspose.slides/color/from_known_color/#knowncolor) | Tworzy kolor z podanego wbudowanego koloru. |
| [`from_name(name)`](/slides/python-net/pl/aspose.slides/color/from_name/#str) | Tworzy kolor z podanej nazwy wbudowanego koloru. |
| [`from_rgb(r, g, b)`](/slides/python-net/pl/aspose.slides/color/from_rgb/#int-int-int) | Tworzy nieprzezroczysty kolor (alfa = 255) z podanymi wartościami czerwonej, zielonej i niebieskiej. |
| [`get_brightness(self)`](/slides/python-net/pl/aspose.slides/color/get_brightness/#) | Pobiera wartość jasności (lightness) w modelu HSL dla tego koloru. |
| [`get_hue(self)`](/slides/python-net/pl/aspose.slides/color/get_hue/#) | Pobiera wartość odcienia (hue) w modelu HSL, w stopniach, dla tego koloru. |
| [`get_saturation(self)`](/slides/python-net/pl/aspose.slides/color/get_saturation/#) | Pobiera wartość nasycenia (saturation) w modelu HSL dla tego koloru. |
| [`to_argb(self)`](/slides/python-net/pl/aspose.slides/color/to_argb/#) | Pobiera 32-bitową wartość ARGB tego koloru. |
| [`to_known_color(self)`](/slides/python-net/pl/aspose.slides/color/to_known_color/#) | Pobiera wartość `KnownColor` tego koloru. |
| [`to_string(self)`](/slides/python-net/pl/aspose.slides/color/to_string/#) | Konwertuje ten kolor na łańcuch znaków przyjazny człowiekowi. Ten sam tekst zwracają `str()` i `repr()`. |


### Uwagi

Kolory są porównywane przez ich składowe ARGB przy użyciu `==` i mogą być używane jako klucze w słownikach lub elementy zbiorów.

Wbudowane kolory (141 nazwanych .NET `KnownColor` oraz `Color.transparent` i `Color.empty`) są dostępne jako atrybuty klasy zapisane w snake_case, np. `Color.red`, `Color.light_blue` lub `Color.dark_slate_gray` (zobacz [Named colors](#named-colors) poniżej). Mogą być także wywoływane jak metody (`Color.red()`), co zwraca ten sam kolor.

### Przykłady

```python
import aspose.slides as slides

with slides.Presentation() as pres:
    shape = pres.slides[0].shapes.add_auto_shape(slides.ShapeType.RECTANGLE, 50, 50, 200, 100)
    shape.fill_format.fill_type = slides.FillType.SOLID
    shape.fill_format.solid_fill_color.color = slides.Color.from_argb(255, 30, 144, 255)
    shape.line_format.fill_format.solid_fill_color.color = slides.Color.dark_blue

    color = slides.Color.from_name("light_blue")
    print(color.name, color.to_argb(), color.is_named_color)  # LightBlue -5383962 Prawda
    print(slides.Color(255, 0, 0) == slides.Color.red)         # Prawda
```

### Nazwane kolory

| Atrybut | .NET nazwa | ARGB |
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

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)