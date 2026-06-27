---
title: MathArray
second_title: Aspose.Sildes for .NET API Referansı
description: Denkliklerin veya herhangi bir matematiksel nesnenin dikey bir dizisini belirtir
type: docs
weight: 8530
url: /tr/aspose.slides.mathtext/matharray/
---
## MathArray sınıfı

Denkliklerin veya herhangi bir matematiksel nesnenin dikey bir dizisini belirtir

```csharp
public sealed class MathArray : MathElementBase, IMathArray
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathArray](matharray#constructor_1)(IEnumerable&lt;IMathElement&gt;) | Creates a mathematical array and places specified elements in it |
| [MathArray](matharray#constructor)(IMathElement) | Creates a mathematical array and places the specified element in it |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/matharray/arguments) { get; } | Dizinin öğe kümesi |
| [BaseJustification](../../aspose.slides.mathtext/matharray/basejustification) { get; set; } | Dizi hizalamasını çevresindeki metne göre belirtir. Dizi dışındaki metin, dizi nesnesinin altı, üstü veya ortası ile hizalanabilir. Varsayılan değer: Center |
| [MaximumDistribution](../../aspose.slides.mathtext/matharray/maximumdistribution) { get; set; } | Maksimum Dağıtım. True olduğunda, dizi, içeren öğenin (sayfa, sütun, hücre, vb.) maksimum genişliğine göre aralanır. |
| [ObjectDistribution](../../aspose.slides.mathtext/matharray/objectdistribution) { get; set; } | Nesne Dağıtımı. True olduğunda, dizi içeriği dizi nesnesinin maksimum genişliğine göre aralanır. |
| [RowSpacing](../../aspose.slides.mathtext/matharray/rowspacing) { get; set; } | Dizi satırları arasındaki boşluk. Yalnızca RowSpacingRule 3 olarak ayarlandığında kullanılır. Bu durumda ölçü birimi puan, Multiple olduğunda ölçü birimi yarım satırdır. Varsayılan: 0 |
| [RowSpacingRule](../../aspose.slides.mathtext/matharray/rowspacingrule) { get; set; } | Dizi öğeleri arasındaki dikey boşluk türü. Varsayılan: SingleLineGap |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (karakter) ekler. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği ve belirtilen ek argümanı kullanarak iki argümanlı işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği ve belirtilen ek argümanı kullanarak iki argümanlı işlevi alır. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu payı ve belirtilen paydayı kullanarak belirtilen tipte bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Belirtilen karakterler (parantez gibi) kullanarak bir matematik öğesini çerçeve içine alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/matharray/getchildren)() | Alt öğeleri al. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt köşeli parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Alt köşeli parantez gibi bir gruplama karakteri kullanarak bu öğeyi bir gruba yerleştirir. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur. |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Verilen dereceye göre belirtilen argümandan matematiksel kök belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Verilen dereceye göre belirtilen argümandan matematiksel kök belirtir. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi kenar kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi kenar kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir; bu, bir denklemin ya da diğer matematiksel metin parçalarının bileşenlerini gruplamak için kullanılır. Kutulu bir nesne, örneğin, hizalama noktasıyla ya da olmadan bir operatör taklitçisi, satır sonu noktası olarak hizmet edebilir ya da içinde satır sonu izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir dizi içine yerleştirir. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler. |

### Örnekler

Örnek:

```csharp
[C#]
MathArray mathArray = new MathArray(new MathematicalText("item1"));
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathArray](../imatharray)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->