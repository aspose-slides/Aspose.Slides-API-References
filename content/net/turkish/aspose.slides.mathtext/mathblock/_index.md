---
title: MathBlock
second_title: Aspose.Sildes için .NET API Referansı
description: MathParagraph içinde bulunan ve kendi satırında başlayan matematiksel metin örneğini belirtir. Denklem, ifade, denklem veya ifade dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri bir math block ile temsil edilir.
type: docs
weight: 8610
url: /tr/aspose.slides.mathtext/mathblock/
---
## MathBlock sınıfı

Bir MathParagraph içinde bulunan ve kendi satırında başlayan matematiksel metin örneğini belirtir. Denklem, ifade, denklem veya ifade dizileri ve formüller dahil olmak üzere tüm matematik bölgeleri bir math block ile temsil edilir.

```csharp
public sealed class MathBlock : MathElementBase, IMathBlock
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathBlock](mathblock#constructor)() | MathBlock sınıfının yeni bir örneğini başlatır. |
| [MathBlock](mathblock#constructor_2)(IEnumerable&lt;IMathElement&gt;) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeleri içine koyar. |
| [MathBlock](mathblock#constructor_1)(IMathElement) | Yeni bir matematik bloğu oluşturur ve belirtilen öğeyi içine koyar. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathblock/count) { get; } | Koleksiyonda gerçekte bulunan çocuk matematik öğelerinin sayısını alır. Salt okunur Int32. |
| [IsReadOnly](../../aspose.slides.mathtext/mathblock/isreadonly) { get; } | Çocuk öğeler koleksiyonu değiştirilebilir olduğu için false döndürür. |
| [Item](../../aspose.slides.mathtext/mathblock/item) { get; set; } | Belirtilen indeksteki IMathElement'i alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bir karakter) ayarlar. |
| [Add](../../aspose.slides.mathtext/mathblock/add)(IMathElement) | Bir matematik öğesini koleksiyonun sonuna ekler. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği ve belirtilen ek argümanı argüman olarak kullanarak belirtilen işlevi alır. |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği ve belirtilen ek argümanı argüman olarak kullanarak belirtilen işlevi alır. |
| [Clear](../../aspose.slides.mathtext/mathblock/clear)() | Koleksiyondaki tüm öğeleri kaldırır. |
| [Contains](../../aspose.slides.mathtext/mathblock/contains)(IMathElement) | Koleksiyonun belirli bir değeri içerip içermediğini belirler. |
| [CopyTo](../../aspose.slides.mathtext/mathblock/copyto)(IMathElement[], int) | Belirtilen diziye kopyalar. |
| [Delimit](../../aspose.slides.mathtext/mathblock/delimit)(char) | Çocuk öğeleri ayırıcı karakterle (köşeli parantez olmadan) sınırlamayı ayarlar. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur. |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır. |
| override [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_1)(char, char) | Bu bloğun çocuk öğelerini belirtilen karakterlerle (örneğin parantez veya başka karakterler) çerçeveleyerek kapsar. |
| [Enclose](../../aspose.slides.mathtext/mathblock/enclose#enclose_2)(char, char, char) | Bu bloğun çocuk öğelerini belirtilen karakterlerle (örneğin parantez) çerçeveleyip bir ayırıcı karakterle sınırlar. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği işlev adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği işlev adı olarak kullanarak bir argüman fonksiyonunu alır. |
| [GetChildren](../../aspose.slides.mathtext/mathblock/getchildren)() | Çocuk öğeleri al. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt kıvrımlı parantezle bir grup içinde konumlandırır. |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt kıvrımlı parantez gibi bir gruplama karakteriyle grup içinde konumlandırır. |
| [IndexOf](../../aspose.slides.mathtext/mathblock/indexof)(IMathElement) | Koleksiyondaki belirli bir matematik öğesinin indeksini belirler. |
| [Insert](../../aspose.slides.mathtext/mathblock/insert)(int, IMathElement) | Belirtilen indekste koleksiyona bir MathElement ekler. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırlama olmadan integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join)(IMathElement) | Bir matematiksel öğeyi bu matematik bloğu ile birleştirir. |
| override [Join](../../aspose.slides.mathtext/mathblock/join#join_1)(string) | Matematiksel bir metni bu matematik bloğu ile birleştirir. |
| [JoinBlock](../../aspose.slides.mathtext/mathblock/joinblock)(IMathBlock) | Başka bir matematik bloğunu bu blokla birleştirir. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur. |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur. |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk koyar. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [Remove](../../aspose.slides.mathtext/mathblock/remove)(IMathElement) | Koleksiyondan belirli bir nesnenin ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides.mathtext/mathblock/removeat)(int) | Koleksiyondaki belirtilen indeksteki öğeyi kaldırır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limit alır. |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limit alır. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge (subscript) oluşturur. |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge (subscript) oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge (superscript) oluşturur. |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge (superscript) oluşturur. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limit alır. |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limit alır. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir. |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görsel olmayan bir kutuya (mantıksal grup) yerleştirir; bu kutu, bir denklem ya da diğer matematiksel metin örneklerinin bileşenlerini gruplamak için kullanılır. Kutulu bir nesne, örneğin bir hizalama noktasıyla ya da olmadan bir operatör emülatörü, satır sonu noktası gibi hizmet edebilir ya da satır sonlarına izin vermeyecek şekilde gruplandırılabilir. |
| override [ToMathArray](../../aspose.slides.mathtext/mathblock/tomatharray)() | Çocuk öğeleri dikey bir diziye koyar. |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk koyar. |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathblock/writeasmathml)(Stream) | Bu [`MathBlock`](../mathblock) içeriğini MathML olarak kaydeder. |

### Örnekler

Örnek:

```csharp
[C#]
MathBlock mathBlock = new MathBlock();
```

### Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathBlock](../imathblock)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->