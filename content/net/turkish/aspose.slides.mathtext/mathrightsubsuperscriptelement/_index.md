---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides için .NET API Referansı
description: Temel ve alt simge ile üst simgenin temelinin sağ tarafına yerleştirildiği Alt-Üst Simge nesnesini belirtir.
type: docs
weight: 8940
url: /tr/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement sınıf

Alt ve üst simge nesnesini belirtir; bu nesne bir temel ve temelinin sağ tarafına yerleştirilmiş bir alt simge ve bir üst simgeden oluşur.

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | MathRightSubSuperscriptElement sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | Alt ve üst simgenin hizalamasını belirtir. true olduğunda alt ve üst simgeler birbirine yatay olarak hizalanır. false olduğunda temel şeklinin biçimine göre yaklaştırılır. Varsayılan değer false'tur. |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | Temel argüman |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | Alt simge argümanı |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | Üst simge argümanı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üstünde bir karakter) ayarlar. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen işlevi alır. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterler ya da başka karakterler ile çerçeve içine alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | Çocuk öğeleri alır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir grupta konumlandırır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplayıcı karakter ya da başka bir karakter kullanarak bir grupta konumlandırır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen dereceden matematiksel kökü belirtilen argümandan tanımlar. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen dereceden matematiksel kökü belirtilen argümandan tanımlar. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limit alır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limit alır. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limit alır. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limit alır. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklem ya da diğer matematik metni örneklerinde bileşenleri gruplamak için kullanılan, görünmez bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne, örneğin bir hizalama noktasıyla ya da olmadan bir operatör taklitçisi, bir satır sonu noktası olarak hizmet edebilir ya da satır sonlarının içinde bulunmasına izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler. |

### Örnekler

Örnek:

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Ayrıca Bakınız

* sınıf [BaseScript](../basescript)
* arayüz [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->