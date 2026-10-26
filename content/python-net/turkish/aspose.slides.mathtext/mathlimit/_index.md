---
title: MathLimit class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathlimit/
---
## MathLimit sınıfı

Alt çizgi üzerindeki metin ve hemen üstünde ya da altında bulunan küçültülmüş boyutlu metni içeren Limit nesnesini belirtir.

**Kalıtım:**[`MathLimit`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathLimit türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, base_arg, limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement-bool) | MathLimit sınıfının yeni bir örneğini başlatır. |
| [`__init__(self, base_arg, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/__init__/#imathelement-imathelement) | Alt limit ile MathLimit sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/base/) | Temel argüman |
| [`limit`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/limit/) | Limit argümanı |
| [`upper_limit`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/upper_limit/) | Üst ya da alt limiti belirtir |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/join/#str) | Matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/divide/#imathelement-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/divide/#str-mathfractiontypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/enclose/#) | Bir matematik öğesini parantez içine alır. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır. |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır. |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_subscript/#imathelement) | Alt simge (subscript) oluşturur. |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_subscript/#str) | Alt simge (subscript) oluşturur. |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_superscript/#imathelement) | Üst simge (superscript) oluşturur. |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_superscript/#str) | Üst simge (superscript) oluşturur. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/radical/#imathelement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/radical/#str) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_upper_limit/#imathelement) | Üst limiti alır. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_upper_limit/#str) | Üst limiti alır. |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_lower_limit/#imathelement) | Alt limiti alır. |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/set_lower_limit/#str) | Alt limiti alır. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-imathelement-imathelement) | N üzeri bir operatör oluşturur. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/nary/#mathnaryoperatortypes-str-str) | N üzeri bir operatör oluşturur. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır. |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes) | Sınırlama olmadan integrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/integral/#mathintegraltypes-str-str) | İntegrali alır. |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/group/#) | Bu öğeyi alt kıvrımlı parantez kullanarak bir grupta yerleştirir. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrımlı parantez veya başka bir gruplama karakteri kullanarak bir grupta yerleştirir. |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/to_border_box/#) | Bu öğeyi bir kenar kutusuna yerleştirir. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenar kutusuna yerleştirir. |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/to_math_array/#) | Dikey bir diziye koyar. |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/accent/#char) | Bu öğenin üstüne bir aksan işareti (karakter) koyar. |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/overbar/#) | Bu öğenin üstüne bir çubuk koyar. |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/underbar/#) | Bu öğenin altına bir çubuk koyar. |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) koyar<br/>            bu, bir denklemin bileşenlerini veya diğer bir matematik metni örneğini gruplayacak şekilde kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör öykünücüsü olarak işlev görebilir, <br/>            bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit/get_children/#) | Alt öğeleri al. |

### İlgili
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathLimit`](/slides/python-net/tr/aspose.slides.mathtext/mathlimit)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)