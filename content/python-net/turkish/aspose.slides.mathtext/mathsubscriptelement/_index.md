---
title: MathSubscriptElement class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathsubscriptelement/
---
## MathSubscriptElement sınıfı

Alt simge nesnesini belirtir; bu nesne bir temel ve aşağıda ve sağda, boyutu azaltılmış bir alt simgeden oluşur.

**Kalıtım:**[`MathSubscriptElement`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement) → [`BaseScript`](/slides/python-net/tr/aspose.slides.mathtext/basescript) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

The MathSubscriptElement type exposes the following members:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, base_arg, sub_script)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/__init__/#imathelement-imathelement) | MathSubscriptElement sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/base/) | Temel argüman |
| [`subscript`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/subscript/) | Alt simge |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/join/#imathelement) | Matematiksel bir öğeyi birleştirir ve bir matematik blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/join/#str) | Matematiksel bir metni birleştirir ve bir matematik blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/divide/#str-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/radical/#imathelement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/radical/#str) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arlı bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/nary/#mathnaryoperatortypes-str-str) | N-arlı bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes) | Sınırları olmadan integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/group/#) | Bu öğeyi alt kıvırcık parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvırcık parantez veya başka bir gruplayıcı karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#) | Bu öğeyi kenar kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenar kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/to_math_array/#) | Dikey bir dizi içine koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/accent/#char) | Bu öğenin üstüne bir aksan işareti (bir karakter) koyar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/overbar/#) | Bu öğenin üstüne bir çubuk koyar |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/underbar/#) | Bu öğenin altına bir çubuk koyar |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bu, bir denklem ya da diğer matematiksel metin örneklerinin bileşenlerini gruplayın için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktası ile ya da olmadan bir operatör öykünücüsü olarak görev yapabilir, <br/>            satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement/get_children/#) | Alt öğeleri al |

### Ayrıca Bakınız
* sınıf [`BaseScript`](/slides/python-net/tr/aspose.slides.mathtext/basescript)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathSubscriptElement`](/slides/python-net/tr/aspose.slides.mathtext/mathsubscriptelement)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)