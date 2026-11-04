---
title: MathematicalText
second_title: Aspose.Sildes için .NET API Referansı
description: Matematiksel metin
type: docs
weight: 9080
url: /tr/aspose.slides.mathtext/mathematicaltext/
---
## MathematicalText sınıfı

Matematiksel metin

```csharp
public sealed class MathematicalText : MathElementBase, IMathematicalText
```

## Yapıcılar

| Name | Description |
| --- | --- |
| [MathematicalText](mathematicaltext#constructor)() | Varsayılan yapıcı (String.Empty değeri oluşturur) |
| [MathematicalText](mathematicaltext#constructor_1)(char) | Tek bir sembolle MathText oluşturur |
| [MathematicalText](mathematicaltext#constructor_2)(string) | Metinden MathematicalText oluşturur |
| [MathematicalText](mathematicaltext#constructor_3)(string, IPortionFormat) | Metinden ve biçim ayarlarından MathematicalText oluşturur |

## Özellikler

| Name | Description |
| --- | --- |
| [Format](../../aspose.slides.mathtext/mathematicaltext/format) { get; } | Metin biçimlendirme özellikleri |
| [Value](../../aspose.slides.mathtext/mathematicaltext/value) { get; set; } | Metin değeri |

## Yöntemler

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstündeki bir karakter (akson işareti) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örnek ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örnek ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini belirtilen karakterler (örneğin parantez veya diğer karakterler) ile çerçeve içine alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örnek fonksiyon adı olarak kullanılarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örnek fonksiyon adı olarak kullanılarak bir argümanın fonksiyonunu alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteri kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırları olmayan integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceye göre matematiksel kökü belirtir. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklemin ya da diğer bir matematiksel metnin bileşenlerini gruplamak için kullanılan görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne (örneğin) hizalama noktasıyla ya da olmadan bir operatör taklitçisi, bir satır sonu noktası ya da içinde satır sonlarına izin vermeyecek şekilde gruplama için kullanılabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
MathematicalText mathText = new MathematicalText("x+y");
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathematicalText](../imathematicaltext)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->