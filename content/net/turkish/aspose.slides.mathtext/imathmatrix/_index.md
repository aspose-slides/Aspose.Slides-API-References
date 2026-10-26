---
title: IMathMatrix
second_title: Aspose.Sildes için .NET API Referansı
description: Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşacak şekilde tanımlar. Matrislerin yerleşik sınırlayıcıları olmadığını unutmamak gerekir. Matrisi köşeli parantez içinde yerleştirmek için IMathDelimiter sınırlayıcı nesnesi kullanılmalıdır. Boşluk oluşturmak için null argümanları kullanılabilir.
type: docs
weight: 8340
url: /tr/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix arayüz

Matrix nesnesini, bir veya daha fazla satır ve sütunda düzenlenmiş alt öğelerden oluşan şekilde tanımlar. Matrislerin yerleşik sınırlayıcıları olmadığını unutmamak gerekir. Matrisi köşeli parantez içine yerleştirmek için sınırlayıcı nesnesi (IMathDelimiter) kullanılmalıdır. Boşluk oluşturmak için null argümanları kullanılabilir.

```csharp
public interface IMathMatrix : IMathElement
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | Temel IMathElement arayüzünü almayı sağlar [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | Matnin etrafına göre dikey hizalamayı belirtir. Olası değerler top, bottom ve center. Varsayılan: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | Matrisdeki sütun sayısı |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk değeri; ColumnGapRule 3 ("Exactly") ise birim twip olarak yorumlanır (1/20 nokta). ColumnGapRule 4 ("Multiple") ise birim 0.5 em artışının sayısı olarak yorumlanır. Diğer durumlarda yoksayılır. Varsayılan: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | Bir matrisin sütunları arasındaki yatay boşluk türü; Yatay boşluk birimleri ems ya da noktalar (twip olarak saklanır). Varsayılan: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | Boş matris elemanları için yer tutucuları gizle. Varsayılan: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | Matrisin elemanları |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | MinColumnWidth (twip cinsinden, 1/20 nokta) Minimum sütun genişliği. Boşluk (“Column Gap” veya “Gap Width” olarak da bilinir) MinColumnWidth’e eklenerek Toplam Matris Sütun Boşluğu (farklı sütunların aynı kenarları arasındaki mesafe) elde edilir. Varsayılan: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | Matrisdeki satır sayısı |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk değeri; RowGapRule 3 ("Exactly") ise birim twip olarak yorumlanır (1/20 nokta). RowGapRule 4 ("Multiple") ise birim yarım satır olarak yorumlanır. Varsayılan: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | Bir matrisin satırları arasındaki dikey boşluk türü; Dikey boşluk birimleri satırlar ya da noktalar (twip olarak saklanır). Varsayılan: SingleSpacingGap (0) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | Belirtilen sütunu siler |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | Belirtilen satırı siler |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | Belirtilen sütunun yatay hizalamasını alır |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | Belirtilen sütundan sonra yeni bir sütun ekler. Başlangıçta yeni sütundaki tüm elemanlar nulldır. |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | Belirtilen sütundan önce yeni bir sütun ekler. Başlangıçta yeni sütundaki tüm elemanlar nulldır. |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | Belirtilen satırdan sonra yeni bir satır ekler. Başlangıçta yeni satırdaki tüm elemanlar nulldır. |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | Belirtilen satırdan önce yeni bir satır ekler. Başlangıçta yeni satırdaki tüm elemanlar nulldır. |
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