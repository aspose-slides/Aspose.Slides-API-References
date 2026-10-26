---
title: MathematicalText class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText sınıfı

Matematiksel metin

**Kalıtım:**[`MathematicalText`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathematicalText türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/__init__/#) | Varsayılan yapıcı (String.Empty değerini oluşturur) |
| [`__init__(self, math_symbol)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/__init__/#char) | Tek sembolle MathText oluşturur |
| [`__init__(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/__init__/#str) | Metinden MathematicalText oluşturur |
| [`__init__(self, math_text, portion_format)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/__init__/#str-iportionformat) | Metin ve biçim ayarlarından MathematicalText oluşturur |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`value`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/value/) | Metin değeri |
| [`format`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/format/) | Metin biçimlendirme özellikleri |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/join/#imathelement) | Bir matematik öğesini birleştirir ve matematiksel bir blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/join/#str) | Bir matematik metnini birleştirir ve matematiksel bir blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/divide/#imathelement) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/divide/#str) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/divide/#str-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/enclose/#) | Bir matematik öğesini parantez içinde sarar |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerde veya başka karakterlerle çerçeveler |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak ve belirtilen ek argümanla kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak ve belirtilen ek argümanla kullanarak belirtilen fonksiyonu alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_subscript/#imathelement) | Taban oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_subscript/#str) | Taban oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/radical/#imathelement) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/radical/#str) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes) | Sınırsız integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/group/#) | Bu öğeyi alt kıvrımlı parantezle bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrımlı parantez veya başka bir gruplama karakteriyle bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/accent/#char) | Üstüne bir aksan işareti (bu öğenin üstüne bir karakter) koyar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/overbar/#) | Bu öğenin üstüne bir çubuk koyar |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/underbar/#) | Bu öğenin altına bir çubuk koyar |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bu kutu bir denklem ya da başka bir matematiksel metin bileşenini gruplamak için kullanılır.<br/>            Kutulu bir nesne, örneğin, hizalama noktası olsun ya da olmasın bir operatör öykünücüsü olarak işlev görebilir, <br/>            satır sonlandırma noktası olarak hizmet edebilir ya da içinde satır sonlandırmaya izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext/get_children/#) |  |

### İlgili
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathematicalText`](/slides/python-net/tr/aspose.slides.mathtext/mathematicaltext)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)