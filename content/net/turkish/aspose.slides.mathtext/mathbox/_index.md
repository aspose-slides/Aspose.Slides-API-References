---
title: MathBox
second_title: Aspose.Slides için .NET API Referansı
description: Matematiksel elemanın mantıksal kutulanmasını (paketlenmesini) belirtir. Örneğin, kutulanmış bir nesne hizalama noktasına sahip ya da sahip olmadan bir operatör taklitçisi olarak, bir satır sonu noktası olarak hizmet verebilir veya satır sonlarının içinde yer almasına izin vermeyecek şekilde gruplanabilir. Örneğin, operatörün satır sonlarını önlemek için kutulanması gerekir.
type: docs
weight: 8630
url: /tr/aspose.slides.mathtext/mathbox/
---
## MathBox sınıfı

Matematik elemanının mantıksal kutulanmasını (paketlenmesini) belirtir. Örneğin, kutulanmış bir nesne, hizalama noktasıyla veya hizalama noktası olmadan bir operatör taklitçisi olarak hizmet verebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. Örneğin, "==" operatörü satır sonlarını önlemek için kutulanmalıdır.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Belirtilen öğeyi argüman olarak alarak MathBox'ı başlatır |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Doğru olduğunda, bu operatör taklitçisi bir hizalama noktası olarak hizmet verir; yani diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. Varsayılan: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Temel argüman |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. bir integrand içinde 𝑑𝑥) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirler, böylece satır kutu nesnesinin başlangıcında kayar. Mevcut satırdaki matematik metninin hizalama noktası olarak kullanılacak, önceki satırdaki operatörün sayısını belirler; olası değerler: 1..255 Varsayılan: 0 (belirtilmiş bir satır sonu yok) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Bu özellik, nesne kutusunun "bölünemez" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör taklitçileri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Varsayılan: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini miras alır. Bu, örneğin karakterin bir satır sonu noktası olarak hizmet verebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Emulatorları, bir veya daha fazla glifin '==' gibi bir operatör oluşturduğu durumlarda sıkça kullanılır. Varsayılan değer: false |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu elemanın üstüne bir aksan işareti (bir karakter) yerleştirir |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik elemanını parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik elemanını parantez gibi belirli karakterler veya başka karakterlerle çerçeve içine alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Alt elemanları alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu elemanı alt süslü parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu elemanı alt süslü parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırlama olmadan integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik elemanını birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N'li bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N'li bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu elemanın üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt sınırı alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt sınırı alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst sınırı alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst sınırı alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu elemanı bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu elemanı bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu elemanı, bir denklemin ya da diğer bir matematik metninin bileşenlerini gruplamak için kullanılan görsel olmayan bir kutuya (mantıksal grup) yerleştirir. Kutulanmış bir nesne (örneğin) hizalama noktasıyla veya olmadan bir operatör taklitçisi olarak hizmet verebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu elemanın altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### İlgili

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBox](../imathbox)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->