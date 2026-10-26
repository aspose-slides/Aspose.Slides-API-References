---
title: MathAccent class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathaccent/
---
## MathAccent sınıfı

Aksan işlevini belirtir; bir temel ve birleştirici diakritik işaretten oluşur
            Örnek: 𝑎́

**Kalıtım:**[`MathAccent`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathAccent türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/__init__/#imathelement) | Belirtilen bir matematik öğesine varsayılan aksan karakter değeriyle bir matematik aksanı oluşturur |
| [`__init__(self, element, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/__init__/#imathelement-char) | Belirtilen bir matematik öğesine bir matematik aksanı oluşturur |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/base/) | Aksanın uygulandığı argüman |
| [`character`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/character/) | Aksan Karakteri<br/>            Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır<br/>            Varsayılan değer: Birleştirici Çatı Aksanı (U+0302) |

## Metodlar

| Metod | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/divide/#imathelement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/divide/#str) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/divide/#imathelement-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/divide/#str-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak ve belirtilen ek argümanla birlikte belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak ve belirtilen ek argümanla birlikte belirtilen fonksiyonu alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/radical/#imathelement) | Belirtilen argümandan verilen derecedeki matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/radical/#str) | Belirtilen argümandan verilen derecedeki matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-imathelement-imathelement) | N'li bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/nary/#mathnaryoperatortypes-str-str) | N'li bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-imathelement-imathelement) | Integrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes) | Sınırları olmadan integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/integral/#mathintegraltypes-str-str) | Integrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/group/#) | Bu öğeyi alt kıvırcık parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvırcık parantez veya başka bir gruplayıcı karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/to_border_box/#) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/accent/#char) | Bir aksan işareti ayarlar (bu öğenin üstünde bir karakter) |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/overbar/#) | Bu öğenin üstüne bir çubuk koyar |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/underbar/#) | Bu öğenin altına bir çubuk koyar |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) <br/>            bu, bir denklemin bileşenlerini veya başka bir matematiksel metin örneğini gruplamak için kullanılır.<br/>            Örneğin, kutulu bir nesne hizalama noktası ile veya olmadan bir operatör öykünücüsü olarak hizmet edebilir, <br/>            satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplandırılabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent/get_children/#) | Alt öğeleri al |

### Ayrıca Bakınız
* sınıf [`MathAccent`](/slides/python-net/tr/aspose.slides.mathtext/mathaccent)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)