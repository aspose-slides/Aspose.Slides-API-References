---
title: IMathMatrix class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix sınıfı

Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşan şeklinde belirtir. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Null argümanlar, matrislerde boşluklar oluşturmak için kullanılabilir.

IMathMatrix türü aşağıdaki üyeleri sunar:

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`row_count`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/row_count/) | Matrisin satır sayısı |
| [`column_count`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/column_count/) | Matrisin sütun sayısı |
| [`hide_placeholders`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/hide_placeholders/) | Boş matris öğeleri için yer tutucuları gizle<br/>            Varsayılan: false |
| [`base_justification`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/base_justification/) | Çevre metne göre dikey hizalamayı belirtir. <br/>            Olası değerler üst, alt ve orta.<br/>            Varsayılan: Center |
| [`min_column_width`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/min_column_width/) | Twip cinsinden minimum sütun genişliği (1/20 nokta)<br/>            Boşluk aralığı (“Column Gap” veya “Gap Width” olarak da adlandırılır) MinColumnWidth değerine eklenir ve toplam Matris Sütun Aralığını belirler<br/>            (farklı sütunların aynı kenarları arasındaki mesafe).<br/>            Varsayılan: 0. |
| [`column_gap_rule`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/column_gap_rule/) | Matrisin sütunları arasındaki yatay boşluk tipi; <br/>            Yatay boşluk birimleri em veya nokta (twip olarak depolanır).<br/>            Varsayılan: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/column_gap/) | Matrisin sütunları arasındaki yatay boşluk değeri;<br/>            ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır<br/>            ColumnGapRule 4 ("Multiple") olarak ayarlanmışsa, birim 0.5 em artışının sayısı olarak yorumlanır.<br/>            Diğer durumlarda yok sayılır.<br/>            Varsayılan: 0 |
| [`row_gap_rule`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/row_gap_rule/) | Matrisin satırları arasındaki dikey boşluk tipi; <br/>            Dikey boşluk birimleri satır veya nokta (twip olarak depolanır).<br/>            Varsayılan: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/row_gap/) | Matrisin satırları arasındaki dikey boşluk değeri;<br/>            RowGapRule 3 ("Exactly") olarak ayarlanmışsa, birim twip (1/20 nokta) olarak yorumlanır<br/>            RowGapRule 4 ("Multiple") olarak ayarlanmışsa, birim yarı satır olarak yorumlanır.<br/>            Varsayılan: 0 |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/join/#imathelement) |  |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/join/#str) |  |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/divide/#imathelement) |  |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/divide/#str) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/divide/#imathelement-mathfractiontypes) |  |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/divide/#str-mathfractiontypes) |  |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/enclose/#) |  |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/enclose/#char-char) |  |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/function/#imathelement) |  |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/function/#str) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#imathelement) |  |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#str) |  |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsofoneargument) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) |  |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_subscript/#imathelement) |  |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_subscript/#str) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_superscript/#imathelement) |  |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_superscript/#str) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_right/#str-str) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) |  |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_sub_superscript_on_the_left/#str-str) |  |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/radical/#imathelement) |  |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/radical/#str) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_upper_limit/#imathelement) |  |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_upper_limit/#str) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_lower_limit/#imathelement) |  |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_lower_limit/#str) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) |  |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/nary/#mathnaryoperatortypes-str-str) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-imathelement-imathelement) |  |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes) |  |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) |  |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/integral/#mathintegraltypes-str-str) |  |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/group/#) |  |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) |  |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/to_border_box/#) |  |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) |  |
| [`get_column_alignment(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/get_column_alignment/#int) | Belirtilen sütunun yatay hizalamasını al |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Belirtilen sütunun yatay hizalamasını ayarla |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Belirtilen sütunların yatay hizalamasını ayarla |
| [`insert_row_before(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/insert_row_before/#int) | Belirtilen satırdan önce yeni bir satır ekle<br/>            Başlangıçta yeni satırdaki tüm öğeler None'dur. |
| [`insert_row_after(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/insert_row_after/#int) | Belirtilen satırdan sonra yeni bir satır ekle<br/>            Başlangıçta yeni satırdaki tüm öğeler None'dur. |
| [`delete_row(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/delete_row/#int) | Belirtilen satırı sil |
| [`insert_column_before(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/insert_column_before/#int) | Belirtilen sütundan önce yeni bir sütun ekle<br/>            Başlangıçta yeni sütundaki tüm öğeler None'dur. |
| [`insert_column_after(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/insert_column_after/#int) | Belirtilen sütundan sonra yeni bir sütun ekle<br/>            Başlangıçta yeni sütundaki tüm öğeler None'dur. |
| [`delete_column(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/delete_column/#int) | Belirtilen sütunu sil |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/get_children/#) |  |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/to_math_array/#) |  |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/accent/#char) |  |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/overbar/#) |  |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/underbar/#) |  |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/imathmatrix/to_box/#) |  |

### Diğer
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)