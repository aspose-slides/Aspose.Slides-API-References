---
title: MathPhantom class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathphantom/
---
## MathPhantom sınıfı

Phantom bir matematik nesnesini (<m:phant>) temsil eder; bu nesne alt öğesinin düzenini etkilebilir ancak mutlaka görüntülenmesi gerekmez. Bir phantom, baz ifadesini gizleyebilir ve formülleri hizalamak veya boşluk ayırmak için genişliğini, yüksekliğini veya derinliğini korur. Görünürlük ve geometrik davranış, Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

**Inheritance:**[`MathPhantom`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathPhantom türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/__init__/#imathelement) | Belirtilen temel matematik öğesini kullanarak [`MathPhantom`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom) sınıfının<br/>yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/base/) | Temel argüman |
| [`show`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/show/) | Temel öğenin görüntülenip görüntülenmediğini gösteren bir değeri alır veya ayarlar. |
| [`zero_width`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/zero_width/) | Temel öğenin genişliğinin sıfır olarak değerlendirilip değerlendirilmediğini gösteren bir değeri alır veya ayarlar. |
| [`zero_asc`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/zero_asc/) | Temel öğenin çıkışının (taban çizgisi üzerindeki yükseklik) sıfır olarak değerlendirilip değerlendirilmediğini gösteren bir değeri alır veya ayarlar. |
| [`zero_desc`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/zero_desc/) | Temel öğenin alçalmasının (taban çizgisi altındaki derinlik) sıfır olarak değerlendirilip değerlendirilmediğini gösteren bir değeri alır veya ayarlar. |
| [`transp`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/transp/) | Sınıf tabanlı boşluk kuralları için phantomun şeffaf olup olmadığını gösteren bir değeri alır veya ayarlar. |

## Metotlar

| Metod | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/divide/#imathelement) | Bu payı ve belirtilen payda ile bir kesir oluşturur. |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/divide/#str) | Bu payı ve belirtilen payda ile bir kesir oluşturur. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/divide/#imathelement-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu pay ve belirtilen payda kullanılarak. |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/divide/#str-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu pay ve belirtilen payda kullanılarak. |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/enclose/#) | Bir matematik öğesini parantez içine alır. |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/enclose/#char-char) | Bir matematik öğesini, parantez gibi belirtilen karakterler ya da başka karakterler ile çerçeveleyerek içine alır. |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argüman alır. |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argüman alır. |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_subscript/#imathelement) | Alt simge oluşturur. |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_subscript/#str) | Alt simge oluşturur. |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_superscript/#imathelement) | Üst simge oluşturur. |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_superscript/#str) | Üst simge oluşturur. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur. |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/radical/#imathelement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/radical/#str) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_upper_limit/#imathelement) | Üst sınırı alır. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_upper_limit/#str) | Üst sınırı alır. |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_lower_limit/#imathelement) | Alt sınırı alır. |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/set_lower_limit/#str) | Alt sınırı alır. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur. |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır. |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes) | Sınırsız integrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır. |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/integral/#mathintegraltypes-str-str) | İntegrali alır. |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/group/#) | Bu öğeyi alt kavisli parantez kullanarak bir gruba yerleştirir. |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kavisli parantez ya da başka bir gruplayıcı karakter kullanarak bir gruba yerleştirir. |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/to_math_array/#) | Dikey bir diziye koyar. |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/accent/#char) | Bir aksan işareti ayarlar (bu öğenin üstündeki karakter). |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/overbar/#) | Bu öğenin üstüne bir çubuk ekler. |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/underbar/#) | Bu öğenin altına bir çubuk ekler. |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) <br/>            bir denklemin bileşenlerini veya diğer matematik metni örneklerini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör öykünücüsü olarak hizmet edebilir, <br/>            satır sonu noktası olarak kullanılabilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom/get_children/#) | Çocuk öğeleri al. |

### Ayrıca Bakınız
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathPhantom`](/slides/python-net/tr/aspose.slides.mathtext/mathphantom)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)