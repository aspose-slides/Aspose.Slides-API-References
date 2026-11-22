---
title: MathDelimiter class
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter sınıfı

Açma ve kapama karakterlerinden (parantez, küme, köşeli parantez ve dikey çubuk gibi) oluşan ve içinde bir veya daha fazla matematiksel öğe bulunan ayırıcı nesnesini belirtir; öğeler belirtilen bir karakterle ayrılır. Örnekler: (𝑥2); [𝑥2|𝑦2]

**Kalıtım:**[`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathDelimiter türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | MathDelimiter'ı belirtilen öğeyle tek temel argüman olarak başlatır |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`arguments`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/arguments/) | Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe |
| [`beginning_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character, başlangıç ya da açma ayırıcı karakteri belirtir. <br/>Matematiksel ayırıcılar, parantez, köşeli parantez ve küme gibi çevreleyen karakterlerdir.<br/>Varsayılan: '('. |
| [`separator_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir. <br/>Varsayılan: '\|'. |
| [`ending_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character, bitiş ya da kapanış ayırıcı karakterini belirtir. <br/>Matematiksel ayırıcılar, parantez, köşeli parantez ve küme gibi çevreleyen karakterlerdir.<br/>Varsayılan: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter karakterlerinin büyümesini belirtir<br/>True olduğunda, ayırıcılar yüksekliğine uyacak şekilde dikey olarak büyür.<br/>Varsayılan değer true'tur |
| [`delimiter_shape`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Ayırıcı nesnedeki ayırıcıların şeklini belirtir. <br/>MathDelimiterShape.Centered olduğunda, ayırıcılar matematiksel metnin matematik ekseni etrafında ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde ayarlanır.<br/>MathDelimiterShape.Match olduğunda, yükseklikleri ve şekilleri tam olarak içeriklerine uyacak şekilde değiştirilir. |

## Metotlar

| Metot | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Bir matematiksel öğeyi birleştirir ve bir matematiksel blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/join/#str) | Bir matematiksel metni birleştirir ve bir matematiksel blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen türde bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen türde bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya çerçeve olarak başka karakterlerle sarar |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek belirtilen argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek belirtilen argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafa alt ve üst simge ekler |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Sağ tarafa alt ve üst simge ekler |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafa alt ve üst simge ekler |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Sol tarafa alt ve üst simge ekler |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arityeli bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N-arityeli bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Sınırsız bir integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/group/#) | Bu öğeyi alt kıvrımlı parantez kullanarak bir grupta yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrımlı parantez veya başka bir gruplama karakteri kullanarak bir grupta yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Bu öğeyi sınırlı bir kutuya yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi sınırlı bir kutuya yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/accent/#char) | Bu öğenin üstüne bir aksan işareti (karakter) ekler |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/> bir denklemin veya başka bir matematiksel metin örneğinin bileşenlerini gruplamak için kullanılır.<br/> Kutulu bir nesne, örneğin, hizalama noktasıyla ya da olmadan bir operatör taklitçisi olarak hizmet edebilir, <br/> satır kesme noktası olarak işlev görebilir ya da satır kesmelerine izin vermeyecek şekilde gruplanabilir. |
| [`delimit(self, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Belirtilen ayırıcı karakteri kullanarak argümanları sınırlar |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/get_children/#) | Çocuk öğeleri alır |

### Ayrıca Bakınız
* sınıf [`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)