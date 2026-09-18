---
title: MathFraction class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathfraction/
---
## MathFraction sınıf

Bir payda ve payı kesir çubuğu ile ayrılmış kesir nesnesini belirtir.
Kesir çubuğu, kesir özelliklerine bağlı olarak yatay veya çapraz olabilir.
Kesir nesnesi ayrıca, bir elemanı diğerinin üzerine yerleştiren ve kesir çubuğu olmayan yığın işlevini temsil etmek için de kullanılır.

**Kalıtım:**[`MathFraction`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathFraction türü aşağıdaki üyeleri içerir:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, numerator, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement-mathfractiontypes) | Belirtilen pay, payda ve tip ile MathFraction'ı başlatır |
| [`__init__(self, numerator, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/__init__/#imathelement-imathelement) | 'Bar' tipinde bir MathFraction'ı belirtilen pay ve payda ile başlatır |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`fraction_type`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/fraction_type/) | Kesir tipi<br/>            Varsayılan: Bar |
| [`numerator`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/numerator/) | Pay |
| [`denominator`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/denominator/) | Payda |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/divide/#imathelement-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/divide/#str-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/enclose/#) | Bir matematik öğesini parantez içinde kapsar |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerde ya da başka karakterlerde çerçeveleyerek kapsar |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/radical/#imathelement) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/radical/#str) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_upper_limit/#imathelement) | Üst limiti alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_upper_limit/#str) | Üst limiti alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_lower_limit/#imathelement) | Alt limiti alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/set_lower_limit/#str) | Alt limiti alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-imathelement-imathelement) | N'li bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/nary/#mathnaryoperatortypes-str-str) | N'li bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes) | Limitsiz integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/group/#) | Bu öğeyi alt süslü parantez kullanarak bir grup içinde yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt süslü parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir grup içinde yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/to_border_box/#) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/accent/#char) | Bir aksan işareti (bu öğenin üstünde bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/overbar/#) | Bu öğenin üstüne bir çubuk yerleştirir |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/underbar/#) | Bu öğenin altına bir çubuk yerleştirir |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) koyar <br/>            bu, bir denklemin veya diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör emülatörü olarak hizmet edebilir, <br/>            satır sonu noktası olarak işlev görebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction/get_children/#) | Alt öğeleri al |

### Ayrıca Bakınız
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathFraction`](/slides/python-net/tr/aspose.slides.mathtext/mathfraction)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)