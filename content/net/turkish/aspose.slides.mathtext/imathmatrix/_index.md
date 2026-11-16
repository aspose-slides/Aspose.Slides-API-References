---
title: IMathMatrix
second_title: Aspose.Sildes için .NET API Referansı
description: Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş çocuk öğelerden oluşan şekilde belirtir. Matrislerin yerleşik ayraçları olmadığını belirtmek önemlidir. Matrisi köşeli parantez içine yerleştirmek için IMathDelimiter nesnesini kullanmalısınız. Null argümanları, matrislerde boşluk oluşturmak için kullanılabilir.
type: docs
weight: 8360
url: /tr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix arayüz

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

```csharp
public interface IMathMatrix : IMathElement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | [`IMathElement`](../imathelement) temel IMathElement arayüzünü almayı sağlar |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Çevre metne göre dikey hizalamayı belirtir. Possible values are top, bottom, and center. Varsayılan: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Matrisdeki sütun sayısı |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ("Exactly") olarak ayarlanmışsa birim twips (bir puanın 1/20'i) olarak yorumlanır. ColumnGapRule 4 ("Multiple") olarak ayarlanmışsa birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yok sayılır. Varsayılan: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri ems veya puan (twips olarak saklanır). Varsayılan: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Boş matris elemanları için yer tutucuları gizle. Varsayılan: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Matris elemanları |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | Twips cinsinden minimum sütun genişliği (bir puanın 1/20'i). Boşluk aralığı (“Column Gap” veya “Gap Width” olarak da adlandırılır) MinColumnWidth değerine eklenerek toplam Matrix Column Spacing (farklı sütunların aynı kenarları arasındaki mesafe) belirlenir. Varsayılan: 0 |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Matrisdeki satır sayısı |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ("Exactly") olarak ayarlanmışsa birim twips (bir puanın 1/20'i) olarak yorumlanır. RowGapRule 4 ("Multiple") olarak ayarlanmışsa birim yarım satır olarak yorumlanır. Varsayılan: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satır veya puan (twips olarak saklanır). Varsayılan: SingleSpacingGap (0) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Belirtilen sütunu siler |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Belirtilen satırı siler |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Belirtilen sütunun yatay hizalamasını alır |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Belirtilen sütunun ardından yeni bir sütun ekler. Yeni sütundaki tüm elemanlar başlangıçta null olur. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Belirtilen sütunun önüne yeni bir sütun ekler. Yeni sütundaki tüm elemanlar başlangıçta null olur. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Belirtilen satırın ardından yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta null olur. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Belirtilen satırın önüne yeni bir satır ekler. Yeni satırdaki tüm elemanlar başlangıçta null olur. |
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