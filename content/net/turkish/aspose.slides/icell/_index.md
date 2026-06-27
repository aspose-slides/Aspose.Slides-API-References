---
title: ICell
second_title: Aspose.Sildes for .NET API Referansı
description: Bir tabloda hücreyi temsil eder.
type: docs
weight: 5430
url: /tr/aspose.slides/icell/
---
## ICell arabirimi

Bir tabloda hücreyi temsil eder.

```csharp
public interface ICell : ISlideComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AnchorCenter](../../aspose.slides/icell/anchorcenter) { get; set; } | Bir hücre içinde metin kutusunun ortalanıp ortalanmadığını belirler. Okunur/yazılabilir Boolean. |
| [AsISlideComponent](../../aspose.slides/icell/asislidecomponent) { get; } | Temel ISlideComponent arabirimini almayı sağlar. Yalnızca okunabilir [`ISlideComponent`](../islidecomponent). |
| [CellFormat](../../aspose.slides/icell/cellformat) { get; } | Bu hücre için biçimlendirme özelliklerini içeren CellFormat nesnesini döndürür. Yalnızca okunabilir [`ICellFormat`](../icellformat). |
| [ColSpan](../../aspose.slides/icell/colspan) { get; } | Üst tablonun tablo ızgarasındaki, mevcut hücre tarafından kapsanacak ızgara sütun sayısını döndürür. Bu özellik, hücrelerin tablo içindeki diğer hücrelerin dikey sınırlarını kapsayarak birleştirilmiş gibi görünmesini sağlar. Yalnızca okunabilir Int32. |
| [FirstColumn](../../aspose.slides/icell/firstcolumn) { get; } | Hücrenin ilk sütununu alır. Yalnızca okunabilir [`IColumn`](../icolumn). |
| [FirstColumnIndex](../../aspose.slides/icell/firstcolumnindex) { get; } | Hücre tarafından kapsanan ilk sütunun dizinini döndürür. Yalnızca okunabilir Int32. |
| [FirstRow](../../aspose.slides/icell/firstrow) { get; } | Hücrenin ilk satırını alır. Yalnızca okunabilir [`IRow`](../irow). |
| [FirstRowIndex](../../aspose.slides/icell/firstrowindex) { get; } | Hücre tarafından kapsanan ilk satırın dizinini döndürür. Yalnızca okunabilir Int32. |
| [Height](../../aspose.slides/icell/height) { get; } | Hücrenin yüksekliğini döndürür. Yalnızca okunabilir Double. |
| [IsMergedCell](../../aspose.slides/icell/ismergedcell) { get; } | Hücre herhangi bir ayarlanmış hücreyle birleştirilmişse true, aksi takdirde false döndürür. Yalnızca okunabilir Boolean. |
| [MarginBottom](../../aspose.slides/icell/marginbottom) { get; set; } | Bir TextFrame içindeki alt kenar boşluğunu döndürür veya ayarlar. Okunur/yazılabilir Double. |
| [MarginLeft](../../aspose.slides/icell/marginleft) { get; set; } | Bir TextFrame içindeki sol kenar boşluğunu döndürür veya ayarlar. Okunur/yazılabilir Double. |
| [MarginRight](../../aspose.slides/icell/marginright) { get; set; } | Bir TextFrame içindeki sağ kenar boşluğunu döndürür veya ayarlar. Okunur/yazılabilir Double. |
| [MarginTop](../../aspose.slides/icell/margintop) { get; set; } | Bir TextFrame içindeki üst kenar boşluğunu döndürür veya ayarlar. Okunur/yazılabilir Double. |
| [MinimalHeight](../../aspose.slides/icell/minimalheight) { get; } | Bir hücrenin minimum yüksekliğini döndürür. Bu, hücre tarafından kapsanan tüm satırların minimum yüksekliklerinin toplamıdır. Yalnızca okunabilir Double. |
| [OffsetX](../../aspose.slides/icell/offsetx) { get; } | Bir tablonun sol kenarından hücrenin sol kenarına olan mesafeyi döndürür. Yalnızca okunabilir Double. |
| [OffsetY](../../aspose.slides/icell/offsety) { get; } | Bir tablonun üst kenarından hücrenin üst kenarına olan mesafeyi döndürür. Yalnızca okunabilir Double. |
| [RowSpan](../../aspose.slides/icell/rowspan) { get; } | Bir birleştirilmiş hücrenin kapsadığı satır sayısını döndürür. Bu, diğer hücrelerdeki vMerge özelliği ile birlikte, yatay bir birleştirmenin başlangıç hücresini belirtmek için kullanılır. Yalnızca okunabilir Int32. |
| [Table](../../aspose.slides/icell/table) { get; } | Bir hücrenin üst Tablo nesnesini döndürür. Yalnızca okunabilir [`ITable`](../itable). |
| [TextAnchorType](../../aspose.slides/icell/textanchortype) { get; set; } | Metin çapa türünü döndürür veya ayarlar. Okunur/yazılabilir [`TextAnchorType`](../textanchortype). |
| [TextFrame](../../aspose.slides/icell/textframe) { get; } | Bir hücrenin metin çerçevesini döndürür. Yalnızca okunabilir [`ITextFrame`](../itextframe). |
| [TextVerticalType](../../aspose.slides/icell/textverticaltype) { get; set; } | Dikey metnin tipini döndürür veya ayarlar. Okunur/yazılabilir [`TextVerticalType`](../textverticaltype). |
| [Width](../../aspose.slides/icell/width) { get; } | Hücrenin genişliğini döndürür. Yalnızca okunabilir Double. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SplitByColSpan](../../aspose.slides/icell/splitbycolspan)(int) | Hücreyi sütun dizinine göre iki hücreye böler. |
| [SplitByHeight](../../aspose.slides/icell/splitbyheight)(double) | Hücreyi yükseklikte böler. |
| [SplitByRowSpan](../../aspose.slides/icell/splitbyrowspan)(int) | Hücreyi satır dizinine göre iki hücreye böler. |
| [SplitByWidth](../../aspose.slides/icell/splitbywidth)(double) | Hücreyi genişlikte böler. |

### Ayrıca Bakınız

* arayüz [ISlideComponent](../islidecomponent)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->