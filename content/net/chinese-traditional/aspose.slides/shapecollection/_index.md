---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示一個形狀集合。
type: docs
weight: 9860
url: /zh-hant/aspose.slides/shapecollection/
---
## ShapeCollection 類別

表示一個形狀集合。

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | 取得集合中實際包含的元素數量。唯讀 Int32。 |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | 傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 Boolean。 |
| [Item](../../aspose.slides/shapecollection/item) { get; } | 取得指定索引處的元素。唯讀 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | 取得形狀集合的父群組形狀物件。唯讀 [`IGroupShape`](../igroupshape)。 |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | 傳回同步根。唯讀 Object。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框架，並將其新增至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件將其新增至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 建立一個內嵌 WAV 檔案的新音訊框架，並將其新增至形狀集合的末端。內嵌的音訊會加入 Presentation.Audios 集合中。 |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | 建立一個連結至外部音訊檔案的新音訊框架，並將其新增至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 建立一個具預設格式的新自動形狀，並將其新增至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 建立一個新自動形狀並將其新增至形狀集合的末端，可選地以預設範本格式進行初始化。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | 建立一個新圖表，並以範例系列資料與設定進行初始化，然後將其新增至形狀集合的末端。 |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 建立一個新圖表，並以範例系列資料與設定進行初始化，然後將其新增至形狀集合的末端。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | 建立指定形狀的副本，並將其新增至形狀集合的末端。複製的形狀保留原始的位罝與大小。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | 建立指定形狀的副本，並將其新增至形狀集合的末端。新形狀保留 *sourceShape* 的寬度與高度。 |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 建立指定形狀的副本，並將其新增至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 建立一個具預設範本樣式的新連接線形狀，並將其新增至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 建立一個新連接線形狀，將其新增至形狀集合的末端，可選地套用預設範本樣式。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | 建立一個新的空白群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以容納任何加入的形狀。 |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 建立一個新群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。 |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | 建立一個用於呈現數學內容的矩形自動形狀，並將其新增至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框架，並將其新增至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 建立一個新的 OLE 物件框架，並將其新增至形狀集合的末端。 |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定圖像的圖片框架，並將其新增至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 建立一個新的 Section Zoom 框架，並將其新增至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 建立一個帶有預設圖像的 Section Zoom 框架，並將其新增至形狀集合的末端。 |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 建立一個 SmartArt 圖表，並將其新增至形狀集合的末端。 |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | 建立一個新的 Summary Zoom 框架，並將其新增至形狀集合的末端。 |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | 建立一個新表格，並將其新增至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 建立一個新影片框架，並將其新增至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 建立一個新影片框架，並將其新增至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 建立一個新 Zoom 框架，並將其新增至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 建立一個新 Zoom 框架，並將其新增至形狀集合的末端。 |
| [Clear](../../aspose.slides/shapecollection/clear)() | 從形狀集合中移除所有形狀。 |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | 將集合中的所有元素複製到指定的陣列。 |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | 傳回一個可遍歷集合的列舉器。 |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | 傳回集合中指定形狀第一次出現的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 建立一個新音訊框架，使用 Presentation.Audios 清單中的現有音訊物件，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 建立一個內嵌 WAV 檔案的新音訊框架，並將其插入至形狀集合中指定的索引位置。內嵌的音訊會加入 Presentation.Audios 集合。 |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 建立一個連結至外部音訊檔案的新音訊框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 建立一個新自動形狀，套用預設範本格式，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 建立一個新自動形狀，將其插入至形狀集合中指定的索引位置，可選地以預設範本樣式進行初始化。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 建立一個新圖表，並以範例系列資料與設定進行初始化，然後將其插入至形狀集合中指定的索引位置。 |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 建立一個新圖表，並以範例系列資料與設定進行初始化，然後將其插入至形狀集合中指定的索引位置。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。複製的形狀保留原始的位罝與大小。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。新形狀保留 *sourceShape* 的寬度與高度。 |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 建立一個具預設範本樣式的連接線形狀，並將其插入至形狀集合中指定的索引位置。 |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 建立一個連接線形狀，將其插入至形狀集合中指定的索引位置，可選地套用預設範本樣式。 |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | 建立一個新的空白群組形狀，並將其插入至形狀集合中指定的索引位置。群組的框架會自動調整以容納任何加入的形狀。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定圖像的圖片框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 建立一個新的 Section Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 建立一個帶有預設圖像的 Section Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 建立一個新的 Summary Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | 建立一個新表格，並將其插入至形狀集合中指定的索引位置。 |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | 建立一個新影片框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 建立一個新 Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 建立一個帶有預設圖像的 Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | 移除形狀集合中首次出現的指定形狀。 |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | 移除形狀集合中指定索引處的形狀。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | 將指定形狀移動至形狀集合中的新位置。 |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | 將指定的形狀在形狀集合中移動，從給定的索引開始依次放置。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | 建立並傳回一個包含所有形狀的陣列。 |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | 建立並傳回一個包含指定範圍內所有形狀的陣列。 |

### 另見

* 類別 [DomObject&lt;TParent&gt;](../domobject-1)
* 類別 [GroupShape](../groupshape)
* 介面 [IShapeCollection](../ishapecollection)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->