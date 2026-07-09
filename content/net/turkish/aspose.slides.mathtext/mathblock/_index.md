---
title: MathBlock
second_title: Aspose.Slides için .NET API Referansı
description: Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirtir. Denklemler, ifadeler, denklem veya ifade dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri bir math block ile temsil edilir.
type: docs
weight: 8590
url: /tr/aspose.slides.mathtext/mathblock/
---
## MathBlock sınıfı

Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematik metni örneğini belirler. Denklemler, ifadeler, denklem ya da ifade dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri bir math block ile temsil edilir.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Yapıcılar

| Name | Description |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock sınıfının yeni bir örneğini başlatır. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine koyar |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine koyar |

## Özellikler

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Koleksiyonda gerçekten bulunan alt matematik öğelerinin sayısını alır. Salt okunur Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Alt öğe koleksiyonu değiştirilebilir olduğu için false döndürür. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Belirtilen dizinde IMathElement öğesini alır veya ayarlar. |

## Metotlar

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bir karakter) ayarlar. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Bir matematik öğesini koleksiyonun sonuna ekler. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman olarak ve belirtilen ek argümanı kullanarak belirtilen işlevi alır. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Koleksiyondaki tüm öğeleri siler. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Belirtilen diziye kopyalar. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Alt öğeleri ayırıcı karakterle sınırlar (köşeli parantezler olmadan). |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirtilen karakterler içinde çerçeveler. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Bu bloğun alt öğelerini parantez veya başka karakterler gibi belirtilen karakterler içinde çerçeveler ve ayırıcı karakterle sınırlar. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Alt öğeleri alır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrık parantez kullanarak bir gruba yerleştirir. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrık parantez gibi bir gruplaştırma karakteri kullanarak bir gruba yerleştirir. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Belirtilen indekste koleksiyona bir MathElement ekler. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınır olmadan integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integrali alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integrali alır. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Bir matematik öğesini bu matematik bloğu ile birleştirir. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Bir matematik metnini bu matematik bloğu ile birleştirir. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Başka bir matematik bloğunu bu ile birleştirir. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk yerleştirir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen derecenin matematik kökünü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen derecenin matematik kökünü belirtir. |
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
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir; bu, bir denklem ya da başka bir matematik metni örneğinin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne (örneğin) hizalama noktasına sahip ya da olmadan bir operatör taklidi, satır sonlandırma noktası görevi görebilir ya da satır sonlandırmalara izin vermeyecek şekilde gruplanabilir. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Alt öğeleri dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk yerleştirir. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Bu [`MathBlock`](../mathblock) içeriğini MathML olarak kaydeder. |

### Örnekler

Example:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBlock](../imathblock)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->