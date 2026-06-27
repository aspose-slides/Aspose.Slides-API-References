---
title: IMathElement
second_title: Aspose.Sildes for .NET API Referansı
description: Herhangi bir matematiksel öğenin temel arabirimi: kesir, matematiksel metin, fonksiyon, birden çok öğe içeren ifade vb.
type: docs
weight: 8210
url: /tr/aspose.slides.mathtext/imathelement/
---
## IMathElement arayüz

Base interface of any mathematical element: fraction, mathmatical text, function, expression with multiple elements etc

```csharp
public interface IMathElement
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | Bir matematik öğesini parantez içine alır |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | Bu öğeyi parantez gibi belirtilen karakterlerle çerçeve içine alır |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonu alır |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | Bu öğeyi alt süslü parantez kullanarak bir grupta konumlandırır |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt süslü parantez gibi bir gruplaştırma karakteri kullanarak bir grupta konumlandırır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | Sınırları olmayan integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | Alt sınırı alır |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | Alt sınırı alır |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | Alt gösterge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | Alt gösterge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | Solda alt ve üst gösterge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | Solda alt ve üst gösterge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağda alt ve üst gösterge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | Sağda alt ve üst gösterge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | Üst gösterge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | Üst gösterge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | Üst sınırı alır |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | Üst sınırı alır |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | Bu öğeyi, bir denklemin veya başka bir matematik metninin bileşenlerini gruplamak için kullanılan görsel olmayan bir kutuya (mantıksal grup) yerleştirir. Kutulanmış bir nesne (örneğin) hizalama noktası olan veya olmayan bir operatör taklitçisi, satır sonu noktası olarak hizmet edebilir ya da satır sonlarının içinde bulunmasına izin verilmeyecek şekilde gruplandırılabilir. |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### Ayrıca Bakınız

* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->