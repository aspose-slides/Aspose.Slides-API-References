---
title: ISlideCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片的集合。
type: docs
weight: 7070
url: /zh-hant/aspose.slides/islidecollection/
---
## ISlideCollection 介面

表示投影片集合。

```csharp
public interface ISlideCollection : IGenericCollection<ISlide>
```

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [Item](../../aspose.slides/islidecollection/item) { get; } | 取得指定索引處的元素。唯讀 [`ISlide`](../islide)。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone)(ISlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_3)(ISlide, ISection) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/islidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 將指定來源投影片的副本新增至集合的末端。系統會自動從指定的主投影片中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果沒有適當的版面配置，則會克隆來源投影片的版面配置（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [AddEmptySlide](../../aspose.slides/islidecollection/addemptyslide)(ILayoutSlide) | 在集合的末端新增一個空白投影片。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml)(Stream) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_4)(string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_2)(TextReader) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/islidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf)(Stream) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_2)(string) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/islidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 從 PDF 文件建立投影片，並依據 pdf 匯入選項將其新增至集合的末端。 |
| [IndexOf](../../aspose.slides/islidecollection/indexof)(ISlide) | 傳回集合中指定投影片的索引。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone)(int, ISlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertClone](../../aspose.slides/islidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 在集合的指定位置插入指定來源投影片的副本。系統會自動從指定的主投影片中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果沒有適當的版面配置，則會克隆來源投影片的版面配置（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [InsertEmptySlide](../../aspose.slides/islidecollection/insertemptyslide)(int, ILayoutSlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [InsertFromHtml](../../aspose.slides/islidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 從 HTML 文字建立投影片，並在指定位置插入至集合中。 |
| [Remove](../../aspose.slides/islidecollection/remove)(ISlide) | 從集合中移除首次出現的特定物件。 |
| [RemoveAt](../../aspose.slides/islidecollection/removeat)(int) | 移除集合中指定索引處的元素。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder)(int, ISlide) | 將投影片從集合中移動至指定位置。 |
| [Reorder](../../aspose.slides/islidecollection/reorder#reorder_1)(int, params ISlide[]) | 將投影片從集合中移動至指定位置。投影片將從索引開始，依照清單中出現的順序依次放置。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray)() | 建立並傳回包含所有投影片的陣列。 |
| [ToArray](../../aspose.slides/islidecollection/toarray#toarray_1)(int, int) | 建立並傳回包含指定範圍內所有投影片的陣列。 |

### 另見

* 介面 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 介面 [ISlide](../islide)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->