---
title: MathBox class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathbox/
---
## MathBox sınıfı

Matematiksel öğenin mantıksal kutulanmasını (paketlenmesini) belirtir.
            Örneğin, kutulanmış bir nesne hizalama noktasıyla ya da hizalama noktası olmadan bir operatör emülatörü olarak hizmet verebilir,
            bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonları oluşmasına izin vermeyecek şekilde gruplanabilir.
            Örneğin, "==" operatörü satır sonlarını önlemek için kutulanmalıdır.

**Kalıtım:**[`MathBox`](/slides/python-net/tr/aspose.slides.mathtext/mathbox) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathBox türü aşağıdaki üyeleri sunar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, element)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/__init__/#imathelement) | MathBox'ı belirtilen öğeyle bir argüman olarak başlatır |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/base/) | Temel argüman |
| [`operator_emulator`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/operator_emulator/) | Operatör Emülatörü.<br/>Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır.<br/>Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir.<br/>Operatör Emülatörleri, bir veya birden fazla glifin '==' gibi bir operatör oluşturmak için birleştirildiği durumlarda sıkça kullanılır.<br/>Varsayılan değer: false |
| [`no_break`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/no_break/) | Kesinti yok<br/>Bu özellik, nesne kutusundaki "kesilemez" özelliğini belirtir.<br/>Doğru olduğunda, kutu içinde satır sonları oluşamaz.<br/>Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir.<br/>Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir.<br/>Varsayılan: true |
| [`differential`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/differential/) | Diferansiyel<br/>Doğru olduğunda, kutu bir diferansiyel (ör. bir integrand içinde 𝑑𝑥) gibi davranır ve uygun<br/>matematiksel diferansiyel için yatay boşluğu alır.<br/>Varsayılan: false |
| [`alignment_point`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/alignment_point/) | Doğru olduğunda, bu operatör emülatörü bir hizalama noktası olarak hizmet eder; yani,<br/>diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir.<br/>Varsayılan: false |
| [`explicit_break`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/explicit_break/) | Açık kesinti, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler,<br/>bu sayede satır, kutu nesnesinin başlangıcında kaydırılır.<br/>Matematiksel metnin önceki satırındaki operatörün numarasını belirtir ki bu<br/>geçerli satırın hizalama noktası olarak kullanılacak<br/>olası değerler: 1..255<br/>Varsayılan: 0 (açık kesinti yok) |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/join/#imathelement) | Bir matematiksel öğeyi birleştirir ve bir matematiksel blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/join/#str) | Bir matematiksel metni birleştirir ve bir matematiksel blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/divide/#imathelement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/divide/#str) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/divide/#imathelement-mathfractiontypes) | Belirtilen tipte bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/divide/#str-mathfractiontypes) | Belirtilen tipte bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/enclose/#) | Bir matematik öğesini parantez içine alır |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeve içine alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve belirtilen ek argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_right/#str-str) | Sağda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#imathelement-imathelement) | Solda alt ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_sub_superscript_on_the_left/#str-str) | Solda alt ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_upper_limit/#imathelement) | Üst limit alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_upper_limit/#str) | Üst limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_lower_limit/#imathelement) | Alt limit alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/set_lower_limit/#str) | Alt limit alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-imathelement-imathelement) | N-arlı bir operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/nary/#mathnaryoperatortypes-str-str) | N-arlı bir operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes) | Limitsiz integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/group/#) | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt süslü parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/to_border_box/#) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/accent/#char) | Bu öğenin üzerindeki bir aksan işareti (karakter) ayarlar |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir<br/>eşitlik bileşenlerini veya diğer matematiksel metin örneklerini gruplamak için kullanılır.<br/>Bir kutulanmış nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör emülatörü olarak hizmet verebilir,<br/>bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathbox/get_children/#) | Çocuk öğeleri al |

### Ayrıca Bakınız
* sınıf [`MathBox`](/slides/python-net/tr/aspose.slides.mathtext/mathbox)
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)