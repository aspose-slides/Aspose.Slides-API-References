---
title: MathMatrix class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix sınıf

Matris nesnesini belirtir; alt öğeler bir veya daha fazla satır ve sütun içinde düzenlenir. 
            Matrislerin yerleşik ayırıcıları olmadığını not etmek önemlidir. 
            Matrisin köşeli parantez içinde yer alması için ayırıcı nesnesi (IMathDelimiter) kullanılmalıdır. 
            Matrislerde boşluk oluşturmak için null argümanlar kullanılabilir.

**Kalıtım:**[`MathMatrix`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathMatrix türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, row_count, column_count)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/__init__/#int-int) | MathMatrix sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`row_count`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/row_count/) | Matrisin satır sayısı |
| [`column_count`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/column_count/) | Matrisin sütun sayısı |
| [`hide_placeholders`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/hide_placeholders/) | Boş matris öğeleri için yer tutucuları gizler<br/>            Varsayılan: false |
| [`base_justification`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/base_justification/) | Çevre metne göre dikey hizalamayı belirtir. <br/>            Olası değerler: top, bottom, ve center.<br/>            Varsayılan: Center |
| [`min_column_width`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/min_column_width/) | Twip cinsinden minimum sütun genişliği (1/20 nokta)<br/>            Boşluk aralığı (“Column Gap” veya “Gap Width” olarak da adlandırılır) MinColumnWidth'e eklenerek toplam Matris Sütun Aralığını belirler<br/>            (farklı sütunların aynı kenarları arasındaki mesafe).<br/>            Varsayılan: 0. |
| [`column_gap_rule`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/column_gap_rule/) | Bir matrisin sütunları arasındaki yatay boşluk türü; <br/>            Yatay boşluk birimleri ems ya da nokta (twip olarak depolanır).<br/>            Varsayılan: SingleSpacingGap (0) |
| [`column_gap`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/column_gap/) | Bir matrisin sütunları arasındaki yatay boşluk değeri;<br/>            ColumnGapRule 3 ("Exactly") olarak ayarlanırsa birim twip (1/20 nokta) olarak yorumlanır<br/>            ColumnGapRule 4 ("Multiple") olarak ayarlanırsa birim 0.5 em artışının sayısı olarak yorumlanır.<br/>            Diğer durumlarda yok sayılır.<br/>            Varsayılan: 0 |
| [`row_gap_rule`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/row_gap_rule/) | Bir matrisin satırları arasındaki dikey boşluk türü; <br/>            Dikey boşluk birimleri satır veya nokta (twip olarak depolanır).<br/>            Varsayılan: SingleSpacingGap (0) |
| [`row_gap`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/row_gap/) | Bir matrisin satırları arasındaki dikey boşluk değeri;<br/>            RowGapRule 3 ("Exactly") olarak ayarlanırsa birim twip (1/20 nokta) olarak yorumlanır<br/>            RowGapRule 4 ("Multiple") olarak ayarlanırsa birim yarım satır olarak yorumlanır.<br/>            Varsayılan: 0 |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/divide/#imathelement-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu pay ve belirtilen payda ile |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/divide/#str-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu pay ve belirtilen payda ile |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematik kökünü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/radical/#str) | Belirtilen argümandan verilen dereceli matematik kökünü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_upper_limit/#imathelement) | Üst limit alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_upper_limit/#str) | Üst limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_lower_limit/#imathelement) | Alt limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_lower_limit/#str) | Alt limit alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes) | Sınırsız integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/group/#) | Bu öğeyi alt kıvırcık parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvırcık parantez gibi bir grup karakteri kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/accent/#char) | Bu öğenin üstüne bir aksan işareti (karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/overbar/#) | Bu öğenin üstüne bir çubuk yerleştirir |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/underbar/#) | Bu öğenin altına bir çubuk yerleştirir |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bu, bir denklem ya da başka bir matematik metni bileşenlerini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktası ile ya da olmadan bir operatör taklitçisi olarak işlev görebilir, <br/>            bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_column_alignment(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/get_column_alignment/#int) | Belirtilen sütunun yatay hizalamasını alır |
| [`set_column_alignment(self, column_index, val)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_column_alignment/#int-mathhorizontalalignment) | Belirtilen sütunun yatay hizalamasını ayarlar |
| [`set_columns_alignment(self, column_index, columns_count, val)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/set_columns_alignment/#int-int-mathhorizontalalignment) | Belirtilen sütunların yatay hizalamasını ayarlar |
| [`insert_row_before(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/insert_row_before/#int) | Belirtilen satırın önüne yeni bir satır ekler<br/>            Yeni satırdaki tüm öğeler başlangıçta None'dur. |
| [`insert_row_after(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/insert_row_after/#int) | Belirtilen satırın sonrasına yeni bir satır ekler<br/>            Yeni satırdaki tüm öğeler başlangıçta None'dur. |
| [`delete_row(self, row_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/delete_row/#int) | Belirtilen satırı siler |
| [`insert_column_before(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/insert_column_before/#int) | Belirtilen sütunun önüne yeni bir sütun ekler<br/>            Yeni sütundaki tüm öğeler başlangıçta None'dur. |
| [`insert_column_after(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/insert_column_after/#int) | Belirtilen sütunun sonrasına yeni bir sütun ekler<br/>            Yeni sütundaki tüm öğeler başlangıçta None'dur. |
| [`delete_column(self, column_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/delete_column/#int) | Belirtilen sütunu siler |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix/get_children/#) | Alt öğeleri alır |

### Ayrıca Bakınız
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathMatrix`](/slides/python-net/tr/aspose.slides.mathtext/mathmatrix)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)