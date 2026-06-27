---
title: MathSuperscriptElement
second_title: Aspose.Sildes .NET API Referansı
description: Üst simge nesnesini tanımlar; bir taban ve sağ üstte yer alan küçültülmüş boyutta bir üst simge içerir.
type: docs
weight: 9000
url: /tr/aspose.slides.mathtext/mathsuperscriptelement/
---
## MathSuperscriptElement sınıfı

Üst simge nesnesini tanımlar; bir taban ve sağ üstte yer alan küçültülmüş boyutta bir üst simge içerir.

```csharp
public sealed class MathSuperscriptElement : BaseScript, IMathSuperscriptElement
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathSuperscriptElement](mathsuperscriptelement)(IMathElement, IMathElement) | MathSuperscriptElement sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Temel argüman |
| [Superscript](../../aspose.slides.mathtext/mathsuperscriptelement/superscript) { get; } | Üst simge |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu elemanın üst kısmına bir aksan işareti (bir karakter) ayarlar. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydasıyla belirtilen türde bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu payı ve belirtilen paydasıyla belirtilen türde bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik elemanını parantez içine alır. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik elemanını parantez gibi belirtilen karakterler veya başka karakterlerle çerçeve içine alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathsuperscriptelement/getchildren)() | Alt elemanları getir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu elemanı alt süslü parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu elemanı alt süslü parantez gibi bir gruplayıcı karakter veya başka bir karakterle bir gruba yerleştirir. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırlama olmadan integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik elemanını birleştirir ve bir matematik bloğu oluşturur. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik elemanını birleştirir ve bir matematik bloğu oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu elemanın üstüne bir çubuk ekler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceye sahip matematik kökünü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceye sahip matematik kökünü belirtir. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limit alır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limit alır. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt simge ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt simge ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt simge ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt simge ve üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limit alır. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limit alır. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu elemanı kenarlık kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu elemanı kenarlık kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu elemanı bir görsel olmayan kutuya (mantıksal grup) yerleştirir; bu, bir denklemin veya diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılır. Kutu içinde bir nesne, örneğin bir operatör emülatörü olarak hizalama noktasıyla veya olmadan, satır sonlandırma noktası olarak ya da satır sonlarının içinde kesilmesine izin verilmeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu elemanın altına bir çubuk ekler. |

### Örnekler

Örnek:

```csharp
[C#]
MathSuperscriptElement superscriptElement = new MathematicalText("N").SetSuperscript("i");
```

### Ayrıca bakınız

* sınıf [BaseScript](../basescript)
* arayüz [IMathSuperscriptElement](../imathsuperscriptelement)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->