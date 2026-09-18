---
title: IMathBox class
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozásával
description: 
type: docs
url: /hu/aspose.slides.mathtext/imathbox/
---
## IMathBox osztály

Meghatározza a matematikai elem logikai dobozolását (csomagolását).
            Például egy dobozolt objektum szolgálhat operátor emulátorként igazítási ponttal vagy anélkül, 
            szolgálhat sorvágási pontként, vagy csoportosítható úgy, hogy ne engedje meg a sorok törését belül.
            Például a "==" operátort dobozni kell, hogy megakadályozzuk a sorok törését.

The IMathBox type exposes the following members:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`base`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/base/) | Alap argumentum |
| [`operator_emulator`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/operator_emulator/) | Operátor emulátor.<br/>            Ha igaz, a doboz és tartalma egyetlen operátorként viselkedik, és örökli egy operátor tulajdonságait. <br/>            Ez azt jelenti, például, hogy a karakter szolgálhat sorvágási pontként, és igazítható más operátorokhoz.<br/>            Az operátor emulátorokat gyakran használják, amikor egy vagy több glif kombinálódik egy operátor létrehozásához, például a '==' esetén.<br/>            Alapértelmezett érték: false |
| [`no_break`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/no_break/) | Nincs törés.<br/>            Ez a tulajdonság meghatározza a "unbreakable" (törhetetlen) tulajdonságot az objektumdobozon. Ha igaz, a dobozon belül nem fordulhat elő sorvágás.<br/>            Ez fontos lehet operátor emulátoroknál, amelyek több bináris operátorból állnak. <br/>            Ha ezt az elemet nem adják meg, a dobozon belül előfordulhatnak törések.<br/>            Alapértelmezett: true |
| [`differential`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/differential/) | Differenciál.<br/>            Ha igaz, a doboz differenciálként működik (pl. 𝑑𝑥 egy integrandusban), és megkapja a megfelelő <br/>            vízszintes távolságot a matematikai differenciál számára.<br/>            Alapértelmezett: false |
| [`alignment_point`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/alignment_point/) | Ha igaz, ez az operátor emulátor igazítási pontként szolgál; vagyis a <br/>            más egyenletekben megadott igazítási pontok ehhez igazíthatók.<br/>            Alapértelmezett: false |
| [`explicit_break`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/explicit_break/) | Kifejezett törés meghatározza, hogy van-e sorvágás a Box objektum elején, <br/>            úgy, hogy a sor a doboz objektum elején töri meg magát.<br/>            Meghatározza a matematikai szöveg előző sorában lévő operátor számát, amelyet<br/>            az aktuális sor matematikai szövegének igazítási pontjaként kell használni<br/>            lehetséges értékek: 1..255<br/>            Alapértelmezett: 0 (nincs kifejezett törés) |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_children(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/hu/aspose.slides.mathtext/imathbox/to_box/#) |  |

### Lásd még
* modul [`aspose.slides.mathtext`](/slides/python-net/hu/aspose.slides.mathtext)
* könyvtár [`Aspose.Slides`](/slides/python-net)