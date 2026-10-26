---
title: MathGroupingCharacter class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter sınıfı

Bir ifadeyi üstünde veya altında bir gruplaştırma simgesi belirler, genellikle öğeler arasındaki ilişkiyi vurgulamak için

**Kalıtım:**[`MathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathGroupingCharacter türü aşağıdaki üyeleri sağlar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement) | MathGroupingCharacter sınıfının yeni bir örneğini varsayılan gruplaştırma karakteri U+23DF (ALT KÖŞELİ KAPATMA) ile başlatır |
| [`__init__(self, element, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/__init__/#imathelement-char-mathtopbotpositions-mathtopbotpositions) | MathGroupingCharacter sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/base/) | Temel argüman |
| [`character`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/character/) | Gruplama Karakteri<br/>            Varsayılan değer: U+23DF (ALT KÖŞELİ KAPATMA) |
| [`position`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/position/) | Gruplama karakterinin konumu.<br/>            Varsayılan: Alt |
| [`vertical_justification`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/vertical_justification/) | Grup karakterinin dikey hizalaması.<br/>            Nesnenin taban çizgisine göre hizalamasını belirtir.<br/>            Örneğin, grup karakteri nesnenin üstünde olduğunda,<br/>            VerticalJustification değerinin Top olması, nesnenin üst kısmının taban çizgisine denk geldiği anlamına gelir;<br/>            VerticalJustification değeri Bottom olduğunda, nesnenin alt kısmı taban çizgesindedir.<br/>            Varsayılan: Position=Top için Bottom, ve Position=Bottom için Top |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/join/#imathelement) | Matematiksel bir öğeyi birleştirir ve bir matematik bloğu oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/join/#str) | Matematiksel bir metni birleştirir ve bir matematik bloğu oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/divide/#str) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/divide/#imathelement-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/divide/#str-mathfractiontypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/enclose/#char-char) | Matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek belirtilen argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek belirtilen argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/radical/#imathelement) | Belirtilen argümandan verilen derecedeki matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/radical/#str) | Belirtilen argümandan verilen derecedeki matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arlı bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/nary/#mathnaryoperatortypes-str-str) | N-arlı bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes) | Sınırlarsız integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/group/#) | Bu öğeyi alt köşeli parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt köşeli parantez gibi bir gruplaştırma karakteri ya da başka bir karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/accent/#char) | Bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir <br/>            bu kutu bir denklemin ya da başka bir matematik metninin bileşenlerini gruplamak için kullanılır.<br/>            Kutulu bir nesne, (örneğin) hizalama noktasına sahip veya olmayan bir operatör taklitçisi olarak hizmet edebilir, <br/>            satır sonu noktası olarak işlev görebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter/get_children/#) | Alt öğeleri al |

### Ayrıca

* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathGroupingCharacter`](/slides/python-net/tr/aspose.slides.mathtext/mathgroupingcharacter)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)