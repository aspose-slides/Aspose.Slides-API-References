---
title: IMathElement
second_title: Aspose.Sildes için .NET API Referansı
description: Çoklu öğeler vb. içeren herhangi bir matematiksel öğe, kesir, matematiksel metin, fonksiyon, ifade vb.'nin temel arabirimi
type: docs
weight: 8230
url: /tr/aspose.slides.mathtext/imathelement/
---
## IMathElement arayüz

Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc

```csharp
public interface IMathElement
```

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üzerinde bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Bir matematik öğesini parantez içine alır |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Bu öğeyi, parantez gibi veya başka karakterlerle çerçevelemek için belirtilen karakterler içinde sarar |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Bu öğeyi alt kavisli parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kavisli parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Sınırlama olmadan integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirler. |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Belirtilen argümandan verilen dereceli matematiksel kökü belirler. |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Alt limit alır |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Alt limit alır |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Üst limit alır |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Üst limit alır |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Bu öğeyi kenarlıklı kutuya yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi kenarlıklı kutuya yerleştirir |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir; bu kutu, bir denklem ya da diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne, örneğin bir hizalama noktası ile ya da olmadan bir operatör taklitçisi gibi görev görebilir, satır sonu noktası olabilir veya satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Dikey bir diziye koyar |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Bakınız

* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->