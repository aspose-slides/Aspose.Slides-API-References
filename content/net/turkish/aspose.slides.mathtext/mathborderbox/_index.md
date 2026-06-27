---
title: MathBorderBox
second_title: Aspose.Slides için .NET API Referansı
description: IMathElement etrafında dikdörtgen veya başka bir kenar çizer.
type: docs
weight: 8590
url: /tr/aspose.slides.mathtext/mathborderbox/
---
## MathBorderBox sınıfı

IMathElement etrafında dikdörtgen veya başka bir kenar çizer.

```csharp
public sealed class MathBorderBox : MathElementBase, IMathBorderBox
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBorderBox](mathborderbox#constructor)(IMathElement) | Dikdörtgen kenarlıklı MathBorderBox öğesi oluşturur |
| [MathBorderBox](mathborderbox#constructor_1)(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) | MathBorderBox öğesi oluşturur |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathborderbox/base) { get; } | Temel bağımsız değişken |
| [HideBottom](../../aspose.slides.mathtext/mathborderbox/hidebottom) { get; set; } | Alt Kenarı Gizle (varsayılan false) - kenar kutusunun alt kenarının gizli ya da gösterili durumunu belirtir. |
| [HideLeft](../../aspose.slides.mathtext/mathborderbox/hideleft) { get; set; } | Sol Kenarı Gizle (varsayılan false) - kenar kutusunun sol kenarının gizli ya da gösterili durumunu belirtir. |
| [HideRight](../../aspose.slides.mathtext/mathborderbox/hideright) { get; set; } | Sağ Kenarı Gizle (varsayılan false) - kenar kutusunun sağ kenarının gizli ya da gösterili durumunu belirtir. |
| [HideTop](../../aspose.slides.mathtext/mathborderbox/hidetop) { get; set; } | Üst Kenarı Gizle (varsayılan false) - kenar kutusunun üst kenarının gizli ya da gösterili durumunu belirtir. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/mathborderbox/strikethroughbottomlefttotopright) { get; set; } | Alt Sol'dan Üst Sağ'a Üzerinden Çizgi (varsayılan false). Kenar kutusunun alt-sol köşesinden üst-sağ köşesine giden çapraz çizginin gizli ya da gösterili durumunu belirtir. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/mathborderbox/strikethroughhorizontal) { get; set; } | Yatay Üzerinden Çizgi (varsayılan false) - yatay bir üzeri çizili satırın gizli ya da gösterili durumunu belirtir. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/mathborderbox/strikethroughtoplefttobottomright) { get; set; } | Üst Sol'dan Alt Sağ'a Üzerinden Çizgi (varsayılan false). Kenar kutusunun üst-sol köşesinden alt-sağ köşesine giden çapraz çizginin gizli ya da gösterili durumunu belirtir. |
| [StrikethroughVertical](../../aspose.slides.mathtext/mathborderbox/strikethroughvertical) { get; set; } | Dikey Üzerinden Çizgi (varsayılan false) - dikey bir üzeri çizili satırın gizli ya da gösterili durumunu belirtir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üzerindeki bir karakter) ayarlar. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği ve belirtilen ek argümanı kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği ve belirtilen ek argümanı kullanarak belirtilen işlevi alır. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydasıyla bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu payı ve belirtilen paydasıyla belirtilen tipte bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Parantez gibi belirtilen karakterlerle veya başka karakterlerle bir matematik öğesini çerçeve içine alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği işlev adı olarak kullanarak bir argüman fonksiyonu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği işlev adı olarak kullanarak bir argüman fonksiyonu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathborderbox/getchildren)() | Alt öğeleri alır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt süslü parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Alt süslü parantez gibi bir gruplayıcı karakter veya başka bir karakter kullanarak bu öğeyi bir gruba yerleştirir. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırlama olmadan integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematiksel kökünü belirtir. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt sınırı alır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt sınırı alır. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst sınırı alır. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst sınırı alır. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenar kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenar kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görünmez bir kutuya (mantıksal gruplama) yerleştirir; bu kutu bir denklemin veya diğer matematiksel metin parçalarının bileşenlerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) bir hizalama noktasıyla ya da olmadan bir operatör taklitçisi olarak, bir satır sonu noktası olarak hizmet edebilir veya içinde satır sonlarına izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler. |

### Örnekler

Örnek:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBorderBox](../imathborderbox)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->