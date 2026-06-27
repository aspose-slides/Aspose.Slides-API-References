---
title: MathBar
second_title: Aspose.Sildes için .NET API Referansı
description: Temel argüman ve bir üst çubuk ya da alt çubuktan oluşan çubuk işlevini belirtir
type: docs
weight: 8550
url: /tr/aspose.slides.mathtext/mathbar/
---
## MathBar sınıfı

Temel argüman ve bir üst ya da alt çubuktan oluşan çubuk işlevini belirtir.

```csharp
public sealed class MathBar : MathElementBase, IMathBar
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [MathBar](mathbar#constructor)(IMathElement) | MathBar'ı üst çubuk (Üst konum) ile başlatır |
| [MathBar](mathbar#constructor_1)(IMathElement, MathTopBotPositions) | MathBar'ı belirtilen konumla başlatır |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathbar/base) { get; } | Temel argüman |
| [Position](../../aspose.slides.mathtext/mathbar/position) { get; set; } | Çubuk çizgisinin konumu. Varsayılan: Üst |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (üstünde bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek string argümanını kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterlerle ya da başka karakterlerle çerçeveleyerek içine alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathbar/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt süslü parantez gibi bir gruplanma karakteri ya da başka bir karakterle bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve matematiksel bir blok oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematiksel bir metni birleştirir ve matematiksel bir blok oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N'li bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N'li bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limit alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limit alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt simge ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt simge ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt simge ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt simge ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limit alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limit alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklem ya da diğer bir matematiksel metin örneğinin bileşenlerini gruplayan, görünür olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne, örneğin hizalama noktası olan ya da olmayan bir operatör taklitçisi, satır sonu noktası olarak hizmet edebilir ya da satır sonlarına izin verilmeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Example:

```csharp
[C#]
MathBar mathBar = new MathBar(new MathematicalText("x"));
```

### İlgili Bağlantılar

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBar](../imathbar)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->