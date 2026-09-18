---
title: MathBorderBox class
second_title: Aspose.Slides için .NET üzerinden Python API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox sınıfı

IMathElement etrafına dikdörtgen veya başka bir kenarlık çizer.

**Kalıtım:**[`MathBorderBox`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathBorderBox türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/__init__/#imathelement) | Dikdörtgen kenarlıklı MathBorderBox öğesi oluşturur |
| [`__init__(self, element, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/__init__/#imathelement-bool-bool-bool-bool-bool-bool-bool-bool) | MathBorderBox öğesi oluşturur |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/base/) | Temel argüman |
| [`hide_top`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/hide_top/) | Üst Kenarı Gizle (varsayılan false) - kenarlık kutusunun üst kenarının gizli veya gösterili durumunu belirtir. |
| [`hide_bottom`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/hide_bottom/) | Alt Kenarı Gizle (varsayılan false) - kenarlık kutusunun alt kenarının gizli veya gösterili durumunu belirtir. |
| [`hide_left`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/hide_left/) | Sol Kenarı Gizle (varsayılan false) - kenarlık kutusunun sol kenarının gizli veya gösterili durumunu belirtir. |
| [`hide_right`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/hide_right/) | Sağ Kenarı Gizle (varsayılan false) - kenarlık kutusunun sağ kenarının gizli veya gösterili durumunu belirtir. |
| [`strikethrough_horizontal`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/strikethrough_horizontal/) | Yatay Üstü Çizili (varsayılan false) - yatay bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [`strikethrough_vertical`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/strikethrough_vertical/) | Dikey Üstü Çizili (varsayılan false) - dikey bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [`strikethrough_bottom_left_to_top_right`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/strikethrough_bottom_left_to_top_right/) | Alt Sol'dan Üst Sağ'a Üstü Çizili (varsayılan false).<br/>            Kenarlık kutusunun alt-sol köşesinden üst-sağ köşesine kadar uzanan çapraz bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |
| [`strikethrough_top_left_to_bottom_right`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/strikethrough_top_left_to_bottom_right/) | Üst Sol'dan Alt Sağ'a Üstü Çizili (varsayılan false).<br/>            Kenarlık kutusunun üst-sol köşesinden alt-sağ köşesine kadar uzanan çapraz bir üstü çizili çizginin gizli veya gösterili durumunu belirtir. |

## Metodlar

| Metod | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/join/#imathelement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/join/#str) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/divide/#imathelement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/divide/#str) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/divide/#imathelement-mathfractiontypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/divide/#str-mathfractiontypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-ary bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/nary/#mathnaryoperatortypes-str-str) | N-ary bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | Integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-imathelement-imathelement) | Integral alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes) | Sınırsız integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | Integral alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/integral/#mathintegraltypes-str-str) | Integral alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/group/#) | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt süslü parantez gibi bir gruplayıcı karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/to_border_box/#) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/to_math_array/#) | Dikey bir diziye yerleştirir |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/accent/#char) | Bir vurgu işareti ayarlar (bu öğenin üstüne bir karakter). |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/to_box/#) | Görsel olmayan bir kutuya (mantıksal grup) yerleştirir <br/>            bir denklem veya diğer bir matematik metni bileşenlerini gruplamak için kullanılır.<br/>            Kutu içindeki bir nesne (örneğin) hizalama noktasına sahip ya da sahip olmadan bir operatör öykünücüsü olarak hizmet edebilir, <br/>            satır sonu noktası olarak hizmet edebilir veya satır sonlarının içinde izin vermeyecek şekilde gruplandırılabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox/get_children/#) | Alt öğeleri al |

### İlgili
* sınıf [`MathBorderBox`](/slides/python-net/tr/aspose.slides.mathtext/mathborderbox)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)