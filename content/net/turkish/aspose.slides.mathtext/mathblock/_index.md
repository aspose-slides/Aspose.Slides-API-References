---
title: MathBlock
second_title: Aspose.Sildes için .NET API Referansı
description: Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematiksel metin örneğini belirtir. Tüm matematik bölgeleri, denklemler, ifadeler, denklemlerin veya ifadelerin dizileri ve formüller dahil olmak üzere, math block tarafından temsil edilir.
type: docs
weight: 8570
url: /tr/aspose.slides.mathtext/mathblock/
---
## MathBlock sınıf

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock sınıfının yeni bir örneğini başlatır. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine koyar |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine koyar |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Koleksiyonda gerçekte bulunan alt matematik öğelerinin sayısını alır. Salt-okunur Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Alt öğeler koleksiyonu değiştirilebildiği için false döndürür. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Belirtilen indeksteki IMathElement öğesini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bu öğenin üstündeki bir karakter) ayarlar. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Koleksiyonun sonuna bir matematik öğesi ekler. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak kullanarak ve belirtilen ek argümanı da ekleyerek belirtilen fonksiyonu alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak kullanarak ve belirtilen ek argümanı da ekleyerek belirtilen fonksiyonu alır. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Koleksiyondaki tüm öğeleri kaldırır. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Belirtilen diziye kopyalar. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Alt öğeleri ayırıcı karakterle (köşeli parantez olmadan) sınırlamaya koyar. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen türde bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen türde bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Bu bloğun alt öğelerini parantez gibi belirtilen karakterlerle çerçeveleyerek sarar. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Bu bloğun alt öğelerini belirtilen karakterlerle (örneğin parantez) çerçeveleyerek ve bir ayırıcı karakterle sınırlayarak sarar. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Alt öğeleri al. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt köşeli süslü parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt köşeli süslü parantez gibi bir gruplayıcı karakter ya da başka bir karakter kullanarak bir gruba yerleştirir. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Belirtilen indekse bir MathElement öğesini koleksiyona ekler. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | İntegrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | İntegrali alır. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Bu matematik blokla bir matematik öğesini birleştirir. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Bu matematik blokla bir matematik metnini birleştirir. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Başka bir matematik bloğunu bu blokla birleştirir. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-aralıklı bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-aralıklı bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk koyar. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirler. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceli matematiksel kökü belirler. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
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
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi, bir denklemin ya da diğer matematik metni örneklerinin bileşenlerini gruplamak için kullanılan, görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir. Kutulu bir nesne, örneğin hizalama noktası olsun ya da olmasın bir operatör taklitçisi, satır sonu noktası olarak hizmet edebilir veya satır sonlarına izin vermeyecek şekilde gruplandırılabilir. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Alt öğeleri dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk koyar. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Bu [`MathBlock`](../mathblock) içeriğini MathML olarak kaydeder. |

### Örnekler

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### İlgili

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBlock](../imathblock)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->