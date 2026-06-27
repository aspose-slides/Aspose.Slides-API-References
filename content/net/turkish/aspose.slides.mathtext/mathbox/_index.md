---
title: MathBox
second_title: Aspose.Slides için .NET API Referansı
description: Matematik öğesinin mantıksal kutulama ve paketlemesini belirtir. Örneğin, bir kutulanmış nesne hizalama noktasıyla veya hizalama noktası olmadan bir operatör emülatörü olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarının içinde oluşmasını engelleyecek şekilde gruplanabilir. Örneğin, operatörün satır sonlarını önlemek için kutulanması gerekir.
type: docs
weight: 8610
url: /tr/aspose.slides.mathtext/mathbox/
---
## MathBox sınıfı

Matematik öğesinin mantıksal kutulanmasını (paketlenmesini) belirtir. Örneğin, kutulanmış bir nesne, hizalama noktasıyla veya hizalama noktası olmadan bir operatör emülatörü olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarının içinde oluşmasını engelleyecek şekilde gruplanabilir. Örneğin, "==" operatörünün satır sonlarını önlemek için kutulanması gerekir.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | MathBox'ı belirtilen öğeyi argüman olarak alarak başlatır |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | true olduğunda, bu operatör emülatörü bir hizalama noktası olarak hizmet eder; yani diğer denklemlerde belirlenen hizalama noktaları bununla hizalanabilir. Default: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Temel argüman |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Differansial: true olduğunda, kutu bir diferansiyel olarak davranır (örneğin, bir integrand içindeki 𝑑𝑥) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Default: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Açık kırılma, Box nesnesinin başlangıcında bir satır sonu olup olmadığını belirtir; böylece satır kutu nesnesinin başlangıcında kayar. Matematiksel metnin önceki satırındaki operatör sayısını belirler; bu sayı mevcut satırın hizalama noktası olarak kullanılacaktır. Olası değerler: 1..255 Default: 0 (açık kırılma yok) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break bu özellik, nesne kutusunun "unbreakable" (kesilemez) özelliğini belirtir. true olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör emülatörleri için önemli olabilir. Bu öğe belirtilmediğinde, kutu içinde satır sonları oluşabilir. Default: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. true olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin, karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operator Emulator'lar, bir veya daha fazla glifin '==' gibi bir operatör oluşturduğu durumlarda sıklıkla kullanılır. Default değer: false |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bir karakter) ekler |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Belirtilen karakterler (ör. parantez) ile bir matematik öğesini çerçeveleyerek içine alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Alt kavisli parantez kullanarak bu öğeyi bir grupta yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Alt kavisli parantez gibi bir gruplama karakteri kullanarak bu öğeyi bir grupta yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary (n-arlı) bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary (n-arlı) bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt sınırı alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt sınırı alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge (subscript) oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge (subscript) oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge (superscript) oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge (superscript) oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst sınırı alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst sınırı alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklemin veya diğer bir matematik metni örneğinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulanmış bir nesne, örneğin, hizalama noktasıyla ya da hizalama noktası olmadan bir operatör emülatörü olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarının içinde oluşmasını engelleyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBox](../imathbox)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->