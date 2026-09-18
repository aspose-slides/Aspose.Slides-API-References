---
title: MathElementBase class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase sınıfı

Base class for IMathElement with the implementation of some methods that are common to all inherited classes
For internal use only. Inherited class must be IMathElement.

The MathElementBase type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/divide/#imathelement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/divide/#str) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/divide/#str-mathfractiontypes) | Belirtilen tipte, bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/enclose/#char-char) | Bir matematik öğesini, parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçevelendirir |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak ve belirtilen ek argümanla kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak ve belirtilen ek argümanla kullanarak belirtilen fonksiyonu alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_upper_limit/#imathelement) | Üst limit alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_upper_limit/#str) | Üst limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_lower_limit/#imathelement) | Alt limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/set_lower_limit/#str) | Alt limit alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arlı bir işlemci oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/nary/#mathnaryoperatortypes-str-str) | N-arlı bir işlemci oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegreyi alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-imathelement-imathelement) | İntegreyi alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes) | Sınırlarsız entegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegreyi alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/integral/#mathintegraltypes-str-str) | İntegreyi alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/group/#) | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt süslü parantez gibi bir gruplama karakteri ya da başka bir karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/to_border_box/#) | Bu öğeyi kenarlıklı bir kutuya yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlıklı bir kutuya yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/accent/#char) | Üst işaret (bu öğenin üstünde bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bu, bir denklemin ya da başka bir matematik metni örneğinin bileşenlerini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktasıyla veya olmadan bir işlemci emülatörü görevi görebilir, <br/>            bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin verilmeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase/get_children/#) |  |

### See Also
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)