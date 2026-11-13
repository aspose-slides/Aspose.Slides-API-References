---
title: SlideCollection
second_title: Aspose.Sildes .NET API 參考
description: 表示投影片的集合。
type: docs
weight: 9990
url: /zh-hant/aspose.slides/slidecollection/
---
## SlideCollection 類別

代表投影片的集合。

```csharp
public sealed class SlideCollection : DomObject<Presentation>, ISlideCollection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides/slidecollection/count) { get; } | 取得集合中實際包含的元素數量。唯讀 Int32。 |
| [IsSynchronized](../../aspose.slides/slidecollection/issynchronized) { get; } | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 Boolean。 |
| [Item](../../aspose.slides/slidecollection/item) { get; } | 取得指定索引處的元素。唯讀 [`Slide`](../slide)。 |
| [SyncRoot](../../aspose.slides/slidecollection/syncroot) { get; } | 傳回同步根。唯讀 Object。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone)(ISlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_1)(ISlide, ILayoutSlide) | 將指定投影片的副本新增至集合的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_3)(ISlide, ISection) | 將指定投影片的副本新增至指定節的末端。 |
| [AddClone](../../aspose.slides/slidecollection/addclone#addclone_2)(ISlide, IMasterSlide, bool) | 將指定來源投影片的副本新增至集合的末端。將自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片版面相同 Type 或 Name 的版面配置）。如果不存在適當的版面配置，則會複製來源投影片的版面（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [AddEmptySlide](../../aspose.slides/slidecollection/addemptyslide)(ILayoutSlide) | 將新的空白投影片新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml)(Stream) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_4)(string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_2)(TextReader) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_1)(Stream, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_5)(string, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromHtml](../../aspose.slides/slidecollection/addfromhtml#addfromhtml_3)(TextReader, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf)(Stream) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_2)(string) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_1)(Stream, PdfImportOptions) | 從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [AddFromPdf](../../aspose.slides/slidecollection/addfrompdf#addfrompdf_3)(string, PdfImportOptions) | 根據 PDF 匯入選項，從 PDF 文件建立投影片並將其新增至集合的末端。 |
| [CopyTo](../../aspose.slides/slidecollection/copyto)(Array, int) | 將集合中的所有元素複製至指定的陣列。 |
| [GetEnumerator](../../aspose.slides/slidecollection/getenumerator)() | 傳回可遍歷集合的列舉器。 |
| [IndexOf](../../aspose.slides/slidecollection/indexof)(ISlide) | 傳回集合中指定投影片的索引。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone)(int, ISlide) | 將指定投影片的副本插入集合的指定位置。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_1)(int, ISlide, ILayoutSlide) | 將指定投影片的副本插入集合的指定位置。 |
| [InsertClone](../../aspose.slides/slidecollection/insertclone#insertclone_2)(int, ISlide, IMasterSlide, bool) | 將指定來源投影片的副本插入集合的指定位置。將自動從指定的母片中選取適當的版面配置（適當的版面配置是具有與來源投影片版面相同 Type 或 Name 的版面配置）。如果不存在適當的版面配置，則會複製來源投影片的版面（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |
| [InsertEmptySlide](../../aspose.slides/slidecollection/insertemptyslide)(int, ILayoutSlide) | 將指定投影片的副本插入集合的指定位置。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml)(int, Stream) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_6)(int, string) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_4)(int, TextReader) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_3)(int, Stream, bool) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_9)(int, string, bool) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_1)(int, Stream, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_7)(int, string, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_5)(int, TextReader, IExternalResourceResolver, string) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_2)(int, Stream, IExternalResourceResolver, string, bool) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [InsertFromHtml](../../aspose.slides/slidecollection/insertfromhtml#insertfromhtml_8)(int, string, IExternalResourceResolver, string, bool) | 從 HTML 文字建立投影片並在指定位置將其插入集合。 |
| [Remove](../../aspose.slides/slidecollection/remove)(ISlide) | 從集合中移除第一次出現的特定物件。 |
| [RemoveAt](../../aspose.slides/slidecollection/removeat)(int) | 移除集合中指定索引處的元素。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder)(int, ISlide) | 將投影片從集合中移動至指定位置。 |
| [Reorder](../../aspose.slides/slidecollection/reorder#reorder_1)(int, params ISlide[]) | 將投影片從集合中移動至指定位置。投影片將從索引開始依照列表出現的順序放置。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray)() | 建立並傳回包含所有投影片的陣列。 |
| [ToArray](../../aspose.slides/slidecollection/toarray#toarray_1)(int, int) | 建立並傳回包含指定範圍內所有投影片的陣列。第一張要加入的投影片索引。要加入的投影片數量。 |

### 另見

* 類別 [DomObject&lt;TParent&gt;](../domobject-1)
* 類別 [Presentation](../presentation)
* 介面 [ISlideCollection](../islidecollection)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->