---
title: MathMatrix
second_title: Aspose.Sildes for .NET API Referansı
description: Satır ve sütunlarda düzenlenmiş alt öğelerden oluşan Matrix nesnesini belirtir. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için IMathDelimiter sınırlayıcı nesnesini kullanmalısınız. Null argümanlar, matrislerde boşluklar oluşturmak için kullanılabilir.
type: docs
weight: 8850
url: /tr/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix sınıfı

Matris nesnesini belirtir; bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşur. Matrislerin yerleşik sınırlayıcıları olmadığını unutmamak önemlidir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Null argümanlar, matrislerde boşluklar oluşturmak için kullanılabilir.

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
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | Çevredeki metne göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center'dir. Varsayılan: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | Matrisin sütun sayısı |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk değerini belirler; ColumnGapRule 3 ('Exactly') olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. ColumnGapRule 4 ('Multiple') olarak ayarlanmışsa birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk türünü belirler; Yatay boşluk birimleri em veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | Boş matris öğeleri için yer tutucuları gizler. Varsayılan: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | Matris öğesi |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | Twip cinsinden minimum sütun genişliği (bir noktanın 1/20'si). Boşluk aralığı (“Column Gap” veya “Gap Width” olarak da adlandırılır), MinColumnWidth’e eklenerek toplam Matris Sütun Boşluğu (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | Matrisin satır sayısı |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk değerini belirler; RowGapRule 3 ('Exactly') olarak ayarlanmışsa birim twip (bir noktanın 1/20'si) olarak yorumlanır. RowGapRule 4 ('Multiple') olarak ayarlanmışsa birim yarım satır olarak yorumlanır. Varsayılan: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk türünü belirler; Dikey boşluk birimleri satır veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | Bu öğenin üstüne bir aksan işareti (bir karakter) koyar |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | Bu örneği argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen işlevi alır |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | Bu örneği argüman ve belirtilen ek argüman olarak kullanarak belirtilen işlevi alır |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | Belirtilen sütunu siler |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | Belirtilen satırı siler |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | Bu payı ve belirtilen paydayı kullanarak bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | Belirtilen tipte, bu pay ve belirtilen payda ile bir kesir oluşturur |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | Bir matematik öğesini parantez içine alır |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | Bir matematik öğesini parantez veya başka bir çerçeve karakteri gibi belirtilen karakterler arasına alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | Bu örneği fonksiyon adı olarak kullanarak bir argümanın fonksiyonunu alır |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | Çocuk öğeleri alır |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | Belirtilen sütunun yatay hizalamasını alır |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | Bu öğeyi alt köşeli parantez kullanarak bir gruba yerleştirir |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | Bu öğeyi alt köşeli parantez gibi bir grup karakteri kullanarak bir gruba yerleştirir |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm öğeler null olur. |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler null olur. |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | Belirtilen satırın ardından yeni bir satır ekler. Yeni satırdaki tüm öğeler null olur. |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler null olur. |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | Sınırlı olmayan integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | Integral alır |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | Integral alır |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | Matematiksel bir öğeyi birleştirerek bir matematik bloğu oluşturur |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | Matematiksel bir metni birleştirerek bir matematik bloğu oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N'li bir operatör oluşturur |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N'li bir operatör oluşturur |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | Bu öğenin üstüne bir çubuk ekler |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | Belirtilen argümandan verilen dereceli matematiksel kökü belirtir. |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Belirtilen sütunun yatay hizalamasını ayarlar |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Belirtilen sütunların yatay hizalamasını ayarlar |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | Alt limit alır |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | Alt limit alır |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | Alt simge oluşturur |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | Alt simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | Sol tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | Sağ tarafta alt ve üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | Üst simge oluşturur |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | Üst simge oluşturur |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | Üst limit alır |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | Üst limit alır |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | Bu öğeyi bir kenarlık kutusuna yerleştirir |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | Bu öğeyi görünmez bir kutuya (mantıksal gruplama) yerleştirir; bu kutu bir denklemin veya diğer matematiksel metin parçasının bileşenlerini gruplamak için kullanılır. Kutu, bir operatör taklidi, satır sonu noktası gibi işlevler görebilir ya da içinde satır sonu izin vermeyecek şekilde gruplandırılabilir. |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | Dikey bir diziye yerleştirir |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | Bu öğenin altına bir çubuk ekler |

### Örnekler

Örnek:

```csharp
[C#]
IMMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ayrıca Bakınız

* sınıf [MathElementBase](../mathelementbase)
* arayüz [IMathMatrix](../imathmatrix)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->