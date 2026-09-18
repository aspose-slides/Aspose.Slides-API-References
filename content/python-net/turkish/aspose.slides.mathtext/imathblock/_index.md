---
title: IMathBlock class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/imathblock/
---
## IMathBlock sınıfı

MathParagraph içinde bulunan ve kendi satırında başlayan bir matematiksel metin örneğini belirtir.  
Tüm matematik bölgeleri, denklemler, ifadeler, denklemler ya da ifadeler dizileri ve formüller dahil olmak üzere bir math block tarafından temsil edilir.

IMathBlock türü aşağıdaki üyeleri ortaya çıkar.

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`count`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/count/) |  |

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/__getitem__/) |  |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/enclose/#char-char-char) | Bu bloğun alt elemanlarını parantez gibi belirtilen karakterlerle veya başka bir çerçeveleyiciyle sarar<br/>            ve bir ayırıcı karakter ile sınırlar |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/enclose/#char-char) |  |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/divide/#str-mathfractiontypes) |  |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`delimit(self, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/delimit/#char) | Tüm alt elemanları ayırıcı karakterle (köşeli parantezler olmadan) sınırlar |
| [`join_block(self, other)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/join_block/#imathblock) | Başka bir matematik blokunu bu blokla birleştirir |
| [`write_as_math_ml(self, stream)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/write_as_math_ml/#iorawiobase) | Bu [`IMathBlock`](/slides/python-net/tr/aspose.slides.mathtext/imathblock) içeriğini MathML olarak kaydeder |
| [`add(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/add/#imathelement) |  |
| [`index_of(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/index_of/#imathelement) |  |
| [`insert(self, index, item)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/insert/#int-imathelement) |  |
| [`clear(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/clear/#) |  |
| [`contains(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/contains/#imathelement) |  |
| [`remove(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/remove/#imathelement) |  |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/remove_at/#int) |  |
| [`copy_to(self, array, array_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/copy_to/#listimathelement-int) |  |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathblock/to_box/#) |  |

### Diğer Bilgiler
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)