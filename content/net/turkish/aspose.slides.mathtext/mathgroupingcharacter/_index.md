---
title: MathGroupingCharacter
second_title: Aspose.Sildes .NET API Referansı
description: Bir ifadeyi üstünde veya altında bir gruplama sembolü belirler; genellikle öğeler arasındaki ilişkiyi vurgulamak için
type: docs
weight: 8740
url: /tr/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter sınıfı

Bir ifadeye üstünde veya altında bir gruplama simgesi belirler, genellikle öğeler arasındaki ilişkiyi vurgulamak için

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | MathGroupingCharacter sınıfının yeni bir örneğini varsayılan gruplama karakteri U+23DF (BOTTOM CURLY BRACKET) ile başlatır |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | MathGroupingCharacter sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | Temel bağımsız değişken |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | Gruplama Karakteri Varsayılan değer: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | Gruplama karakterinin konumu. Varsayılan: Bottom |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | Grup karakterinin dikey hizalaması. Nesnenin taban çizgisine göre hizalamasını belirtir. Örneğin, grup karakteri nesnenin üzerinde olduğunda, VerticalJustification'ın Top olması nesnenin üstünün taban çizgisine denk geldiğini gösterir; VerticalJustification Bottom olarak ayarlandığında, nesnenin altı taban çizgisinde olur. Varsayılan: Bottom for Position=Top, and Top for Position=Bottom |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Belirtilen fonksiyonu bu örneği bağımsız değişken olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Belirtilen fonksiyonu bu örneği bağımsız değişken ve belirtilen ek bağımsız değişken olarak kullanarak alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Belirtilen fonksiyonu bu örneği bağımsız değişken ve belirtilen ek bağımsız değişken olarak kullanarak alır |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Belirtilen türde bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Belirtilen türde bir kesir, bu pay ve belirtilen payda ile oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez gibi belirtilen karakterler ya da başka karakterlerle çerçeveleyerek kapsar |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | Alt öğeleri alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteriyle veya başka bir karakterle bir gruba yerleştirir |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik öğesini birleştirir ve bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Verilen dereceden matematiksel kökü belirtilen argümandan tanımlar |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Verilen dereceden matematiksel kökü belirtilen argümandan tanımlar |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir; bu kutu bir denklemin ya da diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) hizalama noktasıyla veya olmadan bir operatör öykünücüsü olarak, satır sonu noktası olarak hizmet edebilir ya da içinde satır sonu izin vermeyecek şekilde gruplanabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir dizi içine koyar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathGroupingCharacter](../imathgroupingcharacter)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->