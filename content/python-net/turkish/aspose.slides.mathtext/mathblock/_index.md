---
title: MathBlock class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathblock/
---
## MathBlock sınıfı

Matematik paragrafı içinde yer alan ve kendi satırında başlayan matematik metni örneğini belirtir.
            Tüm matematik bölgelleri, denklemler, ifadeler, denklemler veya ifadeler dizileri ve formüller matematik bloğu ile temsil edilir.

**Kalıtım:**[`MathBlock`](/slides/python-net/tr/aspose.slides.mathtext/mathblock) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathBlock türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/__init__/#) | MathBlock sınıfının yeni bir örneğini başlatır. |
| [`__init__(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/__init__/#imathelement) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine yerleştirir |
| [`__init__(self, math_elements)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/__init__/#iterableimathelement) |  |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`count`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/count/) | Koleksiyonda gerçekten bulunan alt matematik öğelerinin sayısını alır.<br/>            Salt okunur **int**. |
| [`is_read_only`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/is_read_only/) | Alt öğeler koleksiyonu değiştirilebildiği için false döndürür. |

Belirtilen dizindeki IMathElement öğesini alır veya ayarlar.

## Dizinleyici

| Ad | Açıklama |
| :- | :- |
| [`[index]`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/__getitem__/) | Öğenin sıfır tabanlı indeksi |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/join/#imathelement) | Bir matematik öğesini bu matematik bloğu ile birleştirir |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/join/#str) | Bir matematik metnini bu matematik bloğu ile birleştirir |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/divide/#str-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/enclose/#char-char) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeve içine alır |
| [`enclose(self, beginning_character, ending_character, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/enclose/#char-char-char) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeve içine alır<br/>            ve bir ayırıcı karakter ile sınırlamaya ekler |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/radical/#imathelement) | Belirtilen argümandan verilen dereceden matematiksel kökü belirler. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/radical/#str) | Belirtilen argümandan verilen dereceden matematiksel kökü belirler. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes) | Sınırları olmadan integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/integral/#mathintegraltypes-str-str) | Integrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/group/#) | Bu öğeyi alt kısmı kıvrımlı parantez olan bir grup içine yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrımlı parantez veya başka bir grup karakteriyle bir grup içine yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/to_border_box/#) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/to_math_array/#) | Alt öğeleri dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/accent/#char) | Bir aksan işareti (öğenin üstüne bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/overbar/#) | Öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/underbar/#) | Öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir <br/>            bu, bir denklem veya diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılır.<br/>            Kutu içinde bir nesne, örneğin bir hizalama noktasıyla veya olmadan bir operatör öykünücüsü olarak hizmet edebilir, <br/>            bir satır sonu noktası olarak hizmet edebilir ya da satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/get_children/#) | Alt öğeleri al |
| [`add(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/add/#imathelement) | Bir matematik öğesini koleksiyonun sonuna ekler. |
| [`clear(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/clear/#) | Koleksiyondaki tüm öğeleri kaldırır. |
| [`contains(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/contains/#imathelement) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [`copy_to(self, array, array_index)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/copy_to/#listimathelement-int) | Belirtilen diziye kopyalar. |
| [`remove(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/remove/#imathelement) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [`index_of(self, item)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/index_of/#imathelement) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [`insert(self, index, item)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/insert/#int-imathelement) | Belirtilen indekste koleksiyona bir MathElement ekler. |
| [`remove_at(self, index)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/remove_at/#int) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [`join_block(self, other)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/join_block/#imathblock) | Başka bir matematik bloğunu bu blokla birleştirir |
| [`delimit(self, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/delimit/#char) | Alt öğeleri ayırıcı karakterle (köşeli parantez olmadan) sınırlar |
| [`write_as_math_ml(self, stream)`](/slides/python-net/tr/aspose.slides.mathtext/mathblock/write_as_math_ml/#iorawiobase) | Bu [`MathBlock`](/slides/python-net/tr/aspose.slides.mathtext/mathblock) içeriğini MathML olarak kaydeder |


### Bakınız
* sınıf [`MathBlock`](/slides/python-net/tr/aspose.slides.mathtext/mathblock)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)