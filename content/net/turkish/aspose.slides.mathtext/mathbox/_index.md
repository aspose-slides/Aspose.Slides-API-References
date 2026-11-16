---
title: MathBox
second_title: Aspose.Sildes .NET API Referansı
description: Matematiksel öğenin mantıksal paketleme (boxing) işlemini belirtir. Örneğin, bir kutulu nesne hizalama noktasına sahip ya da sahip olmadan bir operatör öykünücüsü olarak hizmet edebilir, bir satır sonu noktası olarak kullanılabilir veya satır sonlarına izin vermeyecek şekilde gruplandırılabilir. Örneğin,  operatörü satır sonlarını önlemek için kutulanmalıdır.
type: docs
weight: 8650
url: /tr/aspose.slides.mathtext/mathbox/
---
## MathBox sınıfı

Matematiksel öğenin mantıksal paketlenmesini (box) belirtir. Örneğin, bir kutulu nesne hizalama noktasına sahip veya sahip olmadan bir operatör öykünücüsü olarak hizmet edebilir, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplandırılabilir. Örneğin, "==" operatörü satır sonlarını önlemek için kutulanmalıdır.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | Belirtilen öğeyi argüman olarak kullanarak MathBox'ı başlatır |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | Doğru olduğunda, bu operatör öykünücüsü bir hizalama noktası olarak görev yapar; yani, diğer denklemlerde belirlenen hizalama noktaları onunla hizalanabilir. Varsayılan: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | Temel argüman |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | Diferansiyel Doğru olduğunda, kutu bir diferansiyel olarak davranır (ör. bir integrand içinde 𝑑𝑥) ve matematiksel diferansiyel için uygun yatay boşluğu alır. Varsayılan: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | Explicit break belirler, kutu nesnesinin başlangıcında bir satır sonu olup olmadığını; böylece satır kutunun başlangıcında sarar. Önceki matematik metni satırındaki operatör sayısını belirtir ve bu, mevcut matematik metni satırı için hizalama noktası olarak kullanılacaktır. olası değerler: 1..255 Varsayılan: 0 (açık kırılma yok) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | No break Bu özellik nesne kutusunun "kırılmaz" özelliğini belirtir. Doğru olduğunda, kutu içinde satır sonları oluşamaz. Bu, birden fazla ikili operatörden oluşan operatör öykünücüleri için önemli olabilir. Bu öğe belirtilmediğinde, kutunun içinde kırılmalar gerçekleşebilir. Varsayılan: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | Operator Emulator. Doğru olduğunda, kutu ve içeriği tek bir operatör gibi davranır ve bir operatörün özelliklerini devralır. Bu, örneğin karakterin bir satır sonu noktası olarak hizmet edebileceği ve diğer operatörlerle hizalanabileceği anlamına gelir. Operatör Öykünücüleri genellikle '==' gibi birden fazla glifin bir operatör oluşturduğu durumlarda kullanılır. Varsayılan değer: false |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Belirtilen fonksiyonu bu örneği argüman olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Belirtilen fonksiyonu bu örneği argüman olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Belirtilen fonksiyonu bu örneği argüman olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Belirtilen fonksiyonu bu örneği argüman ve belirtilen ek argümanı kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Belirtilen fonksiyonu bu örneği argüman ve belirtilen ek argümanı kullanarak alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterler veya başka karakterler içinde çerçeveler |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt köşeli ayraç kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt köşeli ayraç gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırları olmayan integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk (bar) ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklemin veya diğer matematik metni örneğinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulanmış bir nesne (örneğin) bir operatör öykünücüsü olarak hizalama noktasına sahip veya olmadan hizmet edebilir, bir satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplandırılabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk (bar) ekler |

### Örnekler

Örnek:

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