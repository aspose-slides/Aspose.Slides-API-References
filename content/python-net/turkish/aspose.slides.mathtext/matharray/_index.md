---
title: MathArray class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/matharray/
---
## MathArray sınıfı

Denklemlerin veya herhangi bir matematiksel nesnenin dikey bir dizisini belirtir

**Kalıtım:**[`MathArray`](/slides/python-net/tr/aspose.slides.mathtext/matharray) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathArray türü aşağıdaki üyelere sahiptir:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/__init__/#imathelement) | Matematiksel bir dizi oluşturur ve belirtilen öğeyi içinde konumlandırır |
| [`__init__(self, elements)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/__init__/#iterableimathelement) |  |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`arguments`](/slides/python-net/tr/aspose.slides.mathtext/matharray/arguments/) | Dizinin öğe kümesi |
| [`base_justification`](/slides/python-net/tr/aspose.slides.mathtext/matharray/base_justification/) | Array'nin çevredeki metne göre hizalamasını belirtir<br/>            Array dışındaki metin, bir array nesnesinin alt, üst veya ortası ile hizalanabilir.<br/>            Varsayılan değer: Center |
| [`maximum_distribution`](/slides/python-net/tr/aspose.slides.mathtext/matharray/maximum_distribution/) | Maksimum Dağıtım<br/>            true olduğunda, dizi içerik öğesinin (sayfa, sütun, hücre vb.) maksimum genişliğine göre boşluk bırakılır. |
| [`object_distribution`](/slides/python-net/tr/aspose.slides.mathtext/matharray/object_distribution/) | Nesne Dağıtımı<br/>            true olduğunda, dizinin içeriği dizi nesnesinin maksimum genişliğine göre boşluk bırakılır. |
| [`row_spacing_rule`](/slides/python-net/tr/aspose.slides.mathtext/matharray/row_spacing_rule/) | Dizi öğeleri arasındaki dikey boşluk türü<br/>            Varsayılan: SingleLineGap |
| [`row_spacing`](/slides/python-net/tr/aspose.slides.mathtext/matharray/row_spacing/) | Dizinin satırları arasındaki boşluk<br/>            yalnızca RowSpacingRule 3 Exactly olarak ayarlandığında kullanılır ve bu durumda ölçü birimi puan olur <br/>            veya Multiple olduğunda ölçü birimi yarım satırdır.<br/>            Varsayılan: 0 |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/join/#imathelement) | Bir matematiksel öğeyi birleştirir ve bir matematiksel blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/join/#str) | Bir matematiksel metni birleştirir ve bir matematiksel blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/divide/#imathelement) | Bu payı ve belirtilen paydası ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/divide/#str) | Bu payı ve belirtilen paydası ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen paydası ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/divide/#str-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen paydası ile bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/enclose/#) | Bir matematik öğesini parantez içinde sarar |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterler veya başka karakterler içinde çerçeveler |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/radical/#imathelement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/radical/#str) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arlı bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/nary/#mathnaryoperatortypes-str-str) | N-arlı bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-imathelement-imathelement) | Integrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/integral/#mathintegraltypes) | Sınırsız integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/integral/#mathintegraltypes-str-str) | Integrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/group/#) | Bu öğeyi alt kıvrık parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvrık parantez veya başka bir gruplaşma karakteri kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/to_border_box/#) | Bu öğeyi kenarlıklı bir kutuya yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlıklı bir kutuya yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/to_math_array/#) | Dikey bir diziye ekler |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/accent/#char) | Bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/overbar/#) | Bu öğenin üstüne bir çubuk koyar |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/underbar/#) | Bu öğenin altına bir çubuk koyar |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bu kutu bir denklemin bileşenlerini veya başka bir matematiksel metin örneğini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktası ile ya da olmadan bir operatör öykünücüsü olarak işlev görebilir, <br/>            satır sonu noktası olarak kullanılabilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/matharray/get_children/#) | Alt öğeleri al |

### Ayrıca Bakınız
* sınıf [`MathArray`](/slides/python-net/tr/aspose.slides.mathtext/matharray)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)