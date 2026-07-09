---
title: SlideCollection
second_title: Aspose.Sildes .NET API 參考
description: 表示投影片的集合。
type: docs
weight: 9970
url: /zh-hant/aspose.slides/slidecollection/
---
## SlideCollection 類別

表示投影片的集合。

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | 取得集合中實際包含的元素數量。唯讀 Int32。 |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 傳回一個值，表示是否同步存取集合（執行緒安全）。唯讀 Boolean。 |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 取得指定索引處的元素。唯讀 [`Slide`](../slide)。 |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 傳回同步根。唯讀 Object。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 將指定投影片的副本新增至指定章節的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 將指定來源投影片的副本新增至集合的末端。會自動從指定的母片中選取相應的版面配置（相應的版面配置是與來源投影片版面具有相同 Type 或 Name 的版面）。如果沒有相應的版面，則會複製來源投影片的版面（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 在集合的末端新增一張空的投影片。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | 根據 PDF 文件建立投影片，並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | 根據 PDF 文件建立投影片，並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 根據 PDF 文件建立投影片，並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 根據 PDF 文件建立投影片，並根據 PDF 匯入選項將其新增至集合的末端。 |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 將集合中的所有元素複製到指定的陣列。 |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 傳回可遍歷集合的列舉器。 |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 傳回指定投影片在集合中的索引。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 在集合的指定位置插入指定來源投影片的副本。會自動從指定的母片中選取相應的版面配置（相應的版面配置是與來源投影片版面具有相同 Type 或 Name 的版面）。如果沒有相應的版面，則會複製來源投影片的版面（如果 allowCloneMissingLayout 為 true）或拋出 PptxEditException（如果 allowCloneMissingLayout 為 false）。 |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 在集合的指定位置插入指定投影片的副本。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 根據 HTML 文字建立投影片，並在集合的指定位置插入它們。 |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 從集合中移除首次出現的特定物件。 |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 移除集合中指定索引處的元素。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 將投影片從集合中移動至指定位置。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 將投影片從集合中移動至指定位置。投影片將從該索引開始，依清單中出現的順序依序放置。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 建立並傳回包含所有投影片的陣列。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 建立並傳回包含指定範圍內所有投影片的陣列。第一個要加入的投影片索引。要加入的投影片數量。 |

### 參見

* 類別 [DomObject&lt;TParent&gt;](../domobject-1)
* 類別 [Presentation](../presentation)
* 介面 [ISlideCollection](../islidecollection)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->