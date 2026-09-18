---
title: MathDelimiter class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter sınıf

Açılış ve kapanış karakterlerinden (parantez, süslü parantez, köşeli parantez ve dikey çubuk gibi) oluşan ayırıcı nesnesini ve içinde belirtilen bir karakterle ayrılmış bir veya daha fazla matematiksel öğeyi belirtir.  
Örnekler: (𝑥2); [𝑥2|𝑦2]

**Kalıtım:**[`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathDelimiter tipi aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/__init__/#imathelement) | Belirtilen öğeyi tek temel argüman olarak kullanarak MathDelimiter'ı başlatır |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`arguments`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/arguments/) | Ayırıcı karakterlerle ayrılmış bir veya daha fazla matematiksel öğe |
| [`beginning_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/beginning_character/) | Delimiter Beginning Character, başlangıç (veya açılış) ayırıcı karakterini belirtir.<br/>Matematiksel ayırıcılar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir.<br/>Varsayılan: '('. |
| [`separator_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/separator_character/) | Delimiter Separator Character, ayırıcı nesnedeki argümanları ayıran karakteri belirtir.<br/>Varsayılan: '\|'. |
| [`ending_character`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/ending_character/) | Delimiter Ending Character, bitiş (veya kapanış) ayırıcı karakterini belirtir.<br/>Matematiksel ayırıcılar parantez, köşeli parantez ve süslü parantez gibi kapsayıcı karakterlerdir.<br/>Varsayılan: ')'. |
| [`grow_to_match_operand_height`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/grow_to_match_operand_height/) | BeginningCharacter, SeparatorCharacter, EndingCharacter'ın büyümesini belirtir<br/>true olduğunda, ayırıcılar işlenenin yüksekliğine uyacak şekilde dikey olarak büyür.<br/>Varsayılan değer true'tur |
| [`delimiter_shape`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/delimiter_shape/) | Ayırıcı nesnedeki ayırıcıların şeklini belirtir.<br/>MathDelimiterShape.Centered olduğunda, ayırıcılar matematik metninin eksenine göre ortalanır ve içeriklerinin tüm yüksekliğine sığacak şekilde ayarlanır.<br/>MathDelimiterShape.Match olduğunda, yüksekliği ve şekli içeriklerine tam olarak uyması için değiştirilir. |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/join/#imathelement) | Bir matematiksel öğeyi birleştirir ve matematiksel bir blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/join/#str) | Bir matematiksel metni birleştirir ve matematiksel bir blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#imathelement-mathfractiontypes) | Belirtilen tipte bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/divide/#str-mathfractiontypes) | Belirtilen tipte bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/enclose/#) | Bir matematik öğesini parantez içinde çerçeve alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_subscript/#imathelement) | Alt simge (subscript) oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_subscript/#str) | Alt simge (subscript) oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_superscript/#imathelement) | Üst simge (superscript) oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_superscript/#str) | Üst simge (superscript) oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İnttegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-imathelement-imathelement) | İnttegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes) | Sınırları olmadan integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str-mathlimitlocations) | İnttegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/integral/#mathintegraltypes-str-str) | İnttegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/group/#) | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplandırma karakteriyle bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/accent/#char) | Üst işaret (bu öğenin üstüne bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/overbar/#) | Bu öğenin üstüne bir çubuk koyar |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/underbar/#) | Bu öğenin altına bir çubuk koyar |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir <br/>denklemin ya da diğer bir matematiksel metin örneğinin öğelerini gruplamak için kullanılır.<br/>Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör taklidi görevi görebilir, <br/>satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin verilmeyecek şekilde gruplanabilir. |
| [`delimit(self, separator_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/delimit/#char) | Belirtilen ayırıcı karakteri kullanarak argümanları sınırlayan |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter/get_children/#) | Alt öğeleri al |

### Bakınız
* sınıf [`MathDelimiter`](/slides/python-net/tr/aspose.slides.mathtext/mathdelimiter)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)