---
title: MathNaryOperator class
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator sınıfı

N-ary bir matematiksel nesneyi belirtir; örneğin Toplam ve İntegral.
            Bir operatör, bir temel (veya işlenen) ve isteğe bağlı üst ve alt sınırdan oluşur. 
            N-ary operatörlerin örnekleri: Toplam, Birleşim, Kesişim, İntegral

**Inheritance:**[`MathNaryOperator`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator) → [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)

MathNaryOperator türü aşağıdaki üyeleri yayınlar:

## Yapıcılar

| Yapıcı | Açıklama |
| :- | :- |
| [`__init__(self, operator_symbol, base_argument, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement-imathelement) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |
| [`__init__(self, operator_symbol, base_argument, lower_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement-imathelement) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |
| [`__init__(self, operator_symbol, base_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/__init__/#char-imathelement) | MathNaryOperator sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Özellik | Açıklama |
| :- | :- |
| [`base`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/base/) | Temel argüman |
| [`subscript`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/subscript/) | Örneğin bir integral durumunda, alt sınırı ayarlayan alt simge argümanını belirtir |
| [`superscript`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/superscript/) | Örneğin bir integral durumunda, üst sınırı ayarlayan üst simge argümanını belirtir |
| [`operator`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/operator/) | Nary Operatör Karakteri<br/>            Örneğin: '∑', '∫' |
| [`limit_location`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/limit_location/) | Sınırların (alt simge ve üst simge) konumu |
| [`grow_to_match_operand_height`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/grow_to_match_operand_height/) | Operatör Karakteri, işlenenin yüksekliğine uyması için dikey olarak büyür |
| [`hide_subscript`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/hide_subscript/) | Alt Simgeyi Gizle |
| [`hide_superscript`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/hide_superscript/) | Üst Simgeyi Gizle |

## Yöntemler

| Yöntem | Açıklama |
| :- | :- |
| [`join(self, math_element)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/join/#imathelement) | Bir matematiksel öğeyi birleştirir ve bir matematik blok oluşturur |
| [`join(self, math_text)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/join/#str) | Bir matematik metnini birleştirir ve bir matematik blok oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/divide/#str) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/divide/#imathelement-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu payı ve belirtilen paydayı kullanır |
| [`divide(self, denominator, fraction_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/divide/#str-mathfractiontypes) | Belirtilen tipte bir kesir oluşturur; bu payı ve belirtilen paydayı kullanır |
| [`enclose(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/enclose/#) | Bir matematik öğesini parantez içinde kapsar |
| [`enclose(self, beginning_character, ending_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/enclose/#char-char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveler |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/function/#imathelement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`function(self, function_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/function/#str) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_name)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsofoneargument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-imathelement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`as_argument_of_function(self, function_type, additional_argument)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/as_argument_of_function/#mathfunctionsoftwoarguments-str) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu ve ek bir argümanı alır |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_subscript/#imathelement) | Alt simge oluşturur |
| [`set_subscript(self, subscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_subscript/#str) | Alt simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_superscript/#imathelement) | Üst simge oluşturur |
| [`set_superscript(self, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_superscript/#str) | Üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#imathelement-imathelement) | Sağ tarafta alt simge ve üst simge oluşturur |
| [`set_sub_superscript_on_the_right(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_right/#str-str) | Sağ tarafta alt simge ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#imathelement-imathelement) | Sol tarafta alt simge ve üst simge oluşturur |
| [`set_sub_superscript_on_the_left(self, subscript, superscript)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_sub_superscript_on_the_left/#str-str) | Sol tarafta alt simge ve üst simge oluşturur |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/radical/#imathelement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`radical(self, degree)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/radical/#str) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#imathelement) | Üst sınırı alır |
| [`set_upper_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_upper_limit/#str) | Üst sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#imathelement) | Alt sınırı alır |
| [`set_lower_limit(self, limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/set_lower_limit/#str) | Alt sınırı alır |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-imathelement-imathelement) | Bir N-ary operatör oluşturur |
| [`nary(self, type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/nary/#mathnaryoperatortypes-str-str) | Bir N-ary operatör oluşturur |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-imathelement-imathelement) | İntegrali alır |
| [`integral(self, integral_type)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes) | Sınırları olmadan integrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit, limit_locations)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str-mathlimitlocations) | İntegrali alır |
| [`integral(self, integral_type, lower_limit, upper_limit)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/integral/#mathintegraltypes-str-str) | İntegrali alır |
| [`group(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/group/#) | Bu öğeyi alt kıvırcık parantezle bir gruba yerleştirir |
| [`group(self, character, position, vertical_justification)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/group/#char-mathtopbotpositions-mathtopbotpositions) | Bu öğeyi alt kıvırcık parantez gibi bir gruplama karakteriyle bir gruba yerleştirir |
| [`to_border_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/to_border_box/#) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_border_box(self, hide_top, hide_bottom, hide_left, hide_right, strikethrough_horizontal, strikethrough_vertical, strikethrough_bottom_left_to_top_right, strikethrough_top_left_to_bottom_right)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/to_border_box/#bool-bool-bool-bool-bool-bool-bool-bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [`to_math_array(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/to_math_array/#) | Dikey bir diziye koyar |
| [`accent(self, accent_character)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/accent/#char) | Bir aksan işareti ayarlar (bu öğenin üstüne bir karakter) |
| [`overbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/overbar/#) | Bu öğenin üstüne bir çubuk ekler |
| [`underbar(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/underbar/#) | Bu öğenin altına bir çubuk ekler |
| [`to_box(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/to_box/#) | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir <br/>            bir denklem ya da başka bir matematik metni örneğinin bileşenlerini gruplamak için kullanılır.<br/>            Kutulu bir nesne (örneğin) bir hizalama noktasıyla veya olmadan bir operatör öykünücüsü gibi işlev görebilir, <br/>            bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [`get_children(self)`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator/get_children/#) | Alt öğeleri alır |

### Ayrıca Bakınız
* sınıf [`MathElementBase`](/slides/python-net/tr/aspose.slides.mathtext/mathelementbase)
* sınıf [`MathNaryOperator`](/slides/python-net/tr/aspose.slides.mathtext/mathnaryoperator)
* modül [`aspose.slides.mathtext`](/slides/python-net/tr/aspose.slides.mathtext)
* kütüphane [`Aspose.Slides`](/slides/python-net)