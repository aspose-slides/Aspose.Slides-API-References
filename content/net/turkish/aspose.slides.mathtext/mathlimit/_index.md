---
title: MathLimit
second_title: Aspose.Sildes for .NET API Referansı
description: Temel çizgi üzerindeki metin ve hemen üstünde veya altında bulunan küçültülmüş boyuttaki metinden oluşan Limit nesnesini belirtir.
type: docs
weight: 8800
url: /tr/aspose.slides.mathtext/mathlimit/
---
## MathLimit sınıfı

Alt satırdaki metin ve hemen üstünde ya da altında bulunan küçültülmüş boyutta metinden oluşan Limit nesnesini belirtir.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | MathLimit sınıfının yeni bir örneğini alt limit ile başlatır |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | MathLimit sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | Temel argüman |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | Limit argümanı |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | Üst veya alt limiti belirtir |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (üst karakter) ekler |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Belirtilen fonksiyonu bu örneği bağımsız değişken ve ek bir argüman olarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Belirtilen fonksiyonu bu örneği bağımsız değişken ve ek bir argüman olarak alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Belirtilen tipte, bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Belirtilen tipte, bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içinde kapsar |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterlerde veya başka karakterlerle çerçeveler |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | Alt öğeleri al |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez veya başka bir gruplama karakteri kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceden matematiksel kökü belirtir. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limiti alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limiti alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limiti alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limiti alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi bir görsel olmayan kutuya (mantıksal gruplama) yerleştirir; bu kutu bir denklemin bileşenlerini veya diğer matematik metni örneklerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör taklidi, bir satır kesme noktası görevini görebilir ya da satır sonlarına izin vermeyecek şekilde gruplandırılabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### Ayrıca bakınız

* class [MathElementBase](../mathelementbase)
* interface [IMathLimit](../imathlimit)
* namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->