---
title: MathMatrix
second_title: Aspose.Sildes için .NET API Referansı
description: Bir veya daha fazla satır ve sütunda düzenlenen alt elemanlardan oluşan Matris nesnesini belirtir. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için IMathDelimiter sınırlayıcı nesnesini kullanmalısınız. Null argümanlar, matrislerde boşluk oluşturmak için kullanılabilir.
type: docs
weight: 8830
url: /tr/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix sınıf

Bir veya daha fazla satır ve sütunda düzenlenen alt elemanlardan oluşan Matris nesnesini belirtir. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matris'i parantez içine yerleştirmek için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Matrislerde boşluk oluşturmak için null argümanlar kullanılabilir.

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | MathMatrix sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Çevre metne göre dikey hizalamayı belirtir. Olası değerler üst, alt ve orta. Varsayılan: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Matris içindeki sütun sayısı |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Matris sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim 0.5 em artış sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Matris sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Boş matris elemanları için yer tutucuları gizler. Varsayılan: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Matrisin elemanı |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Twip cinsinden minimum sütun genişliği (noktanın 1/20'i) “Column Gap” veya “Gap Width” olarak da adlandırılan boşluk, MinColumnWidth'e eklenerek toplam Matris Sütun Boşluğu (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Matris içindeki satır sayısı |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Matris satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanmışsa birim twip (noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanmışsa birim yarım satır olarak yorumlanır. Varsayılan: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Matris satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu elemanın üstüne bir aksan işareti (bir karakter) yerleştirir |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen fonksiyonu alır |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Belirtilen sütunu siler |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Belirtilen satırı siler |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Bu pay ve belirtilen payda ile belirtilen tipte bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik elemanını parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik elemanını parantez gibi belirtilen karakterlerle veya başka karakterlerle çerçeveleyerek alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Alt elemanları alır |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Belirtilen sütunun yatay hizalamasını alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu elemanı alt süslü parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu elemanı alt süslü parantez gibi bir gruplama karakteri veya başka bir karakter kullanarak bir gruba yerleştirir |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Belirtilen sütunun sonrasına yeni bir sütun ekler. Yeni sütundaki tüm elemanlar başlangıçta nulldır. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm elemanlar başlangıçta nulldır. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta nulldır. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta nulldır. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırsız integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Bir matematik elemanını birleştirir ve matematiksel bir blok oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Bir matematik metnini birleştirir ve matematiksel bir blok oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu elemanın üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Verilen dereceden matematiksel kökü verilen argümandan belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Verilen dereceden matematiksel kökü verilen argümandan belirtir. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Belirtilen sütunun yatay hizalamasını ayarlar |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Belirtilen sütunların yatay hizalamasını ayarlar |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limiti alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limiti alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Solda alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Solda alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağda alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağda alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limiti alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limiti alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu elemanı kenarlıklı bir kutuya yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu elemanı kenarlıklı bir kutuya yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu elemanı görsel olmayan bir kutuya (mantıksal gruplama) yerleştirir; bu, bir denklem ya da başka bir matematik metni bileşenini gruplayıp kullanılır. Kutulu bir nesne, örneğin hizalama noktasıyla ya da olmadan bir operatör taklitcisi, satır kesme noktası olarak hizmet edebilir ya da içinde satır kesilmesine izin vermeyecek şekilde gruplandırılabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir dizi içine koyar |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu elemanın altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathMatrix](../imathmatrix)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->