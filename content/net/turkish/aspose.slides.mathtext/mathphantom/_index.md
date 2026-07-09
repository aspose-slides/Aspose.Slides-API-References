---
title: MathPhantom
second_title: Aspose.Sildes için .NET API Referansı
description: Çocuğu öğesinin düzenini etkileyen, zorunlu olarak görüntülenmeyebilen bir hayalet matematik nesnesi ltmphantgt'yi temsil eder. Bir hayalet, formülleri hizalamak veya boşluk ayırmak için genişliğini, yüksekliğini veya derinliğini korurken temel ifadesini gizleyebilir. Görünürlük ve geometri davranışı Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.
type: docs
weight: 8920
url: /tr/aspose.slides.mathtext/mathphantom/
---
## MathPhantom sınıfı

Çocuk öğesinin düzenini etkileyen, ancak zorunlu olarak görüntülenmeyen bir hayalet matematik nesnesini (<m:phant>) temsil eder. Bir hayalet, temel ifadesini gizleyebilir ancak formülleri hizalamak veya boşluk ayırmak için genişlik, yükseklik veya derinliğini korur. Görünürlük ve geometri davranışı, Show, ZeroWid, ZeroAsc, ZeroDesc ve Transp gibi özelliklerle kontrol edilir.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## Yapıcılar

| Name | Description |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | Belirtilen temel matematik öğesini kullanarak [`MathPhantom`](../mathphantom) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | Temel argüman |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | Temel öğenin görüntülenip görüntülenmediğini gösteren bir değeri alır veya ayarlar. |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | Hayaletin sınıf tabanlı aralık kuralları için şeffaf olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | Temel öğenin yükselişinin (tabana göre yükseklik) sıfır olarak kabul edilip edilmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | Temel öğenin alçalmasının (tabanın altındaki derinlik) sıfır olarak kabul edilip edilmeyeceğini gösteren bir değeri alır veya ayarlar. |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | Temel öğenin genişliğinin sıfır olarak kabul edilip edilmeyeceğini gösteren bir değeri alır veya ayarlar. |

## Metotlar

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (öğenin üst kısmındaki bir karakter) koyar. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek argümanı kullanarak belirtilen fonksiyonu alır. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen türde bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirli karakterlerle veya başka karakterlerle çerçeve içine alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | Alt öğeleri alır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bir gruba yerleştirir. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırları olmadan integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirler. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limiti alır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limiti alır. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limiti alır. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limiti alır. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklemin veya diğer matematik metni örneklerinin bileşenlerini gruplayan, görünür olmayan bir kutuya (mantıksal grup) yerleştirir. Kutulu bir nesne, örneğin hizalama noktası ile ya da olmadan bir operatör öykünücüsü olarak, bir satır sonu noktası olarak kullanılabilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler. |

### Örnekler

Example:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // İçeriği gizle
phantom.ZeroWidth = false;     // Genişliği koru
```

### Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathPhantom](../imathphantom)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->