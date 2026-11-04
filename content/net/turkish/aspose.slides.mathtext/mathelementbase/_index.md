---
title: MathElementBase
second_title: Aspose.Sildes .NET API Referansı
description: IMathElement için, tüm türetilen sınıflarda ortak olan bazı yöntemlerin uygulanmasıyla birlikte temel sınıf. Yalnızca dahili kullanım içindir. Türetilen sınıf IMathElement olmalıdır.
type: docs
weight: 8700
url: /tr/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase sınıf

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.

```csharp
public abstract class MathElementBase : IMathElement
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen işlevi alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterler veya başka karakterler ile çerçeve içinde alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N'li bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | N'li bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | Alt sınırı alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | Alt sınırı alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | Üst sınırı alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | Üst sınırı alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | Bu öğeyi bir sınır kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir sınır kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir; bu kutu, bir denklemin veya başka bir matematiksel metnin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) hizalama noktasıyla veya hizalama noktasız bir operatör emülatörü olarak, satır sonu noktası olarak kullanılabilir veya satır sonu izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Ayrıca Bakınız

* arayüz [IMathElement](../imathelement)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->