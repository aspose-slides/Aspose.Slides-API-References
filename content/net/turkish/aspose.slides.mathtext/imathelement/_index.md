---
title: IMathElement
second_title: Aspose.Sildes için .NET API Referansı
description: Her türlü matematiksel öğenin, kesir, matematiksel metin, fonksiyon, birden çok öğe içeren ifade vb. temel arayüzü
type: docs
weight: 8250
url: /tr/aspose.slides.mathtext/imathelement/
---
## IMathElement arayüz

Her türlü matematiksel öğenin temel arayüzü: kesir, matematiksel metin, fonksiyon, birden çok öğe içeren ifade vb

```csharp
public interface IMathElement
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Bu elemanın üstüne bir aksan işareti (bu öğenin üstünde bir karakter) ekler |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Bu örnekeyi argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Bu örnekeyi argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Bu örnekeyi argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Bu örnekeyi argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Bu örnekeyi argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Bir matematik öğesini parantez içine alır |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Bu öğeyi parantez gibi belirli karakterler veya başka karakterlerle çerçeveleyerek içine alır |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Bu öğeyi alt kısmı kıvırcık parantez olan bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kısmı kıvırcık parantez gibi bir gruplama karakteriyle gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Integral alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Bir matematik öğesini birleştirerek bir matematik bloğu oluşturur |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Bir matematik metnini birleştirerek bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Belirtilen argümandan verilen dereceye sahip matematiksel kökü belirler. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Belirtilen argümandan verilen dereceye sahip matematiksel kökü belirler. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Alt sınırı alır |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Alt sınırı alır |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Üst sınırı alır |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Üst sınırı alır |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir; bu kutu bir denklemin veya diğer matematiksel metin örneklerinin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) hizalama noktasıyla veya olmadan bir operatör emülatörü, satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Dikey bir diziye koyar |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### İlgili

* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->