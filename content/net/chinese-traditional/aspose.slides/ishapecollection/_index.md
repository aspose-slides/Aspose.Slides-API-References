---
title: IShapeCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示形狀的集合。
type: docs
weight: 6980
url: /zh-hant/aspose.slides/ishapecollection/
---
## IShapeCollection 介面

代表一個形狀的集合。

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 取得指定索引處的元素。唯讀 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | 取得形狀集合的父群組形狀物件。唯讀 [`IGroupShape`](../igroupshape)。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框，並將其新增至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 使用 Presentation.Audios 清單中的既有音訊物件，建立新音訊框並將其新增至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 建立一個內嵌 WAV 檔的新音訊框，並將其新增至形狀集合的末端。內嵌音訊會加入 Presentation.Audios 集合。 |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 建立一個連結至外部音訊檔的新音訊框，並將其新增至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 建立一個使用預設格式的新自動圖形，並將其新增至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 建立一個新自動圖形，並將其新增至形狀集合的末端，可選擇以預設範本格式初始化。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 建立一個新圖表，使用範例系列資料與設定初始化，並將其新增至形狀集合的末端。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 建立一個新圖表，使用範例系列資料與設定初始化，並將其新增至形狀集合的末端。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 建立指定形狀的副本，並將其新增至形狀集合的末端。複製的形狀保留原始位置與大小。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 建立指定形狀的副本，並將其新增至形狀集合的末端。新形狀保留 *sourceShape* 的寬度與高度。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 建立指定形狀的副本，並將其新增至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 建立一個使用預設範本樣式的新連接線形狀，並將其新增至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 建立一個新連接線形狀，並將其新增至形狀集合的末端，可選擇套用預設範本樣式。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 建立一個空的群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以符合加入的任何形狀。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 建立一個新群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。 |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 建立一個用於容納數學內容的矩形自動圖形，並將其新增至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框，並將其新增至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 建立一個新的 OLE 物件框，並將其新增至形狀集合的末端。 |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定影像的圖片框，並將其新增至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 建立一個新的 Section Zoom 框，並將其新增至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 建立一個帶有預設影像的 Section Zoom 框，並將其新增至形狀集合的末端。 |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 建立一個 SmartArt 圖表，並將其新增至形狀集合的末端。 |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 建立一個新的 Summary Zoom 框，並將其新增至形狀集合的末端。 |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 建立一個新表格，並將其新增至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 建立一個新影片框，並將其新增至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 建立一個新影片框，並將其新增至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 建立一個新 Zoom 框，並將其新增至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 建立一個新 Zoom 框，並將其新增至形狀集合的末端。 |
| [Clear](../../aspose.slides/ishapecollection/clear)() | 移除形狀集合中的所有形狀。 |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | 取得集合中首次出現指定形狀的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框，並將其插入至指定索引的形狀集合中。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 使用 Presentation.Audios 清單中的既有音訊物件，建立新音訊框並將其插入至指定索引的形狀集合中。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 建立一個內嵌 WAV 檔的新音訊框，並將其插入至指定索引的形狀集合中。內嵌音訊會加入 Presentation.Audios 集合。 |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 建立一個連結至外部音訊檔的新音訊框，並將其插入至指定索引的形狀集合中。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 建立一個新自動圖形，並將其插入至指定索引的形狀集合中，套用預設範本格式。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 建立一個新自動圖形，並將其插入至指定索引的形狀集合中，可選擇以預設範本樣式初始化。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 建立一個新圖表，使用範例系列資料與設定初始化，並將其插入至指定索引的形狀集合中。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 建立一個新圖表，使用範例系列資料與設定初始化，並將其插入至指定索引的形狀集合中。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 建立指定形狀的副本，並將其插入至指定索引的形狀集合中。複製的形狀保留原始位置與大小。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 建立指定形狀的副本，並將其插入至指定索引的形狀集合中。新形狀保留 *sourceShape* 的寬度與高度。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 建立指定形狀的副本，並將其插入至指定索引的形狀集合中。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 建立一個新連接線形狀，並將其插入至指定索引的形狀集合中，套用預設範本樣式。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 建立一個新連接線形狀，並將其插入至指定索引的形狀集合中，可選擇套用預設範本樣式。 |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 建立一個空的群組形狀，並將其插入至指定索引的形狀集合中。群組的框架會自動調整以符合加入的任何形狀。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框，並將其插入至指定索引的形狀集合中。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 建立一個新的 OLE 物件框，並將其插入至指定索引的形狀集合中。 |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定影像的圖片框，並將其插入至指定索引的形狀集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 建立一個新的 Section Zoom 框，並將其插入至指定索引的形狀集合中。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 建立一個帶有預設影像的 Section Zoom 框，並將其插入至指定索引的形狀集合中。 |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 建立一個新的 Summary Zoom 框，並將其插入至指定索引的形狀集合中。 |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 建立一個新表格，並將其插入至指定索引的形狀集合中。 |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 建立一個新影片框，並將其插入至指定索引的形狀集合中。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 建立一個新 Zoom 框，並將其插入至指定索引的形狀集合中。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 建立一個帶有預設影像的 Zoom 框，並將其插入至指定索引的形狀集合中。 |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 移除形狀集合中首次出現的指定形狀。 |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 移除位於指定索引的形狀。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 將指定形狀移動至形狀集合中的新位置。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 將指定形狀在形狀集合中移動，從給定索引開始依次放置。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | 建立並傳回包含所有形狀的陣列。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 建立並傳回指定範圍內所有形狀的陣列。 |

### 另請參閱

* 介面 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 介面 [IShape](../ishape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->