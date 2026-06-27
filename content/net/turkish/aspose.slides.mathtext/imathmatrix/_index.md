---
title: IMathMatrix
second_title: Aspose.Sildes için .NET API Referansı
description: Bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşan Matrix nesnesini tanımlar. Matrislerin yerleşik sınırlayıcıları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için IMathDelimiter sınırlayıcı nesnesini kullanmalısınız. Null argümanları, matrislerde boşluklar oluşturmak için kullanılabilir.
type: docs
weight: 8320
url: /tr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix arayüz

Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşan şekilde tanımlar. Matrislerin yerleşik sınırlayıcıları olmadığını not etmek önemlidir. Matris'i parantez içinde konumlandırmak için sınırlayıcı nesnesini (IMathDelimiter) kullanmalısınız. Null argümanları, matrislerde boşluklar oluşturmak için kullanılabilir.

```csharp
public interface IMathMatrix : IMathElement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Base IMathElement arayüzünü almayı sağlar [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Çevresindeki metne göre dikey hizalamayı belirler. Olası değerler top, bottom ve center. Varsayılan: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Matrisdeki sütun sayısı |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 (\"Exactly\") olarak ayarlanırsa, birim twip (noktanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 (\"Multiple\") olarak ayarlanırsa, birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri em veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Boş matris öğeleri için yer tutucuları gizler Varsayılan: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Matrisin öğeleri |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Twip cinsinden minimum sütun genişliği (noktanın 1/20'i) Boşluk aralığı (“Column Gap” veya “Gap Width” olarak da adlandırılır), MinColumnWidth'e eklenerek toplam Matris Sütun Aralığı (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Matrisdeki satır sayısı |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 (\"Exactly\") olarak ayarlanırsa, birim twip (noktanın 1/20'i) olarak yorumlanır. RowGapRule 4 (\"Multiple\") olarak ayarlanırsa, birim yarı satır olarak yorumlanır. Varsayılan: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya point (twip olarak depolanır) olabilir. Varsayılan: SingleSpacingGap (0) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Belirtilen sütunu siler |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Belirtilen satırı siler |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Belirtilen sütunun yatay hizalamasını alır |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Belirtilen sütunun sonrasına yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm öğeler başlangıçta null olur. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Belirtilen satırın sonrasına yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm öğeler başlangıçta null olur. |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | Belirtilen sütunun yatay hizalamasını ayarlar |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | Belirtilen sütunların yatay hizalamasını ayarlar |

### Örnekler

Örnek:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### Ayrıca Bakınız

* arayüz [IMathElement](../imathelement)
* ad alanı [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->