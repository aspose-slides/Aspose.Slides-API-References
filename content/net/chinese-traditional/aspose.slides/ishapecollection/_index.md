---
title: IShapeCollection
second_title: Aspose.Sildes .NET API 參考
description: 表示形狀的集合。
type: docs
weight: 6980
url: /zh-hant/aspose.slides/ishapecollection/
---
## IShapeCollection 介面

表示形狀的集合。

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | 取得在指定索引處的元素。唯讀 [`IShape`](../ishape)。 |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | 取得形狀集合的父群組形狀物件。唯讀 [`IGroupShape`](../igroupshape)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框架，並將其添加至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | 建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其添加至形狀集合的末端。 |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | 建立一個內嵌 WAV 檔案的新音訊框架，並將其添加至形狀集合的末端。內嵌的音訊會加入 Presentation.Audios 集合中。 |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | 建立一個連結至外部音訊檔案的新音訊框架，並將其添加至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | 建立一個使用預設格式的新自動形狀，並將其添加至形狀集合的末端。 |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | 建立一個新自動形狀並將其添加至形狀集合的末端，可選擇以預設範本格式進行初始化。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | 建立一個新圖表，並以樣本系列資料與設定進行初始化，然後將其添加至形狀集合的末端。 |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | 建立一個新圖表，並以樣本系列資料與設定進行初始化，可選擇使用預設範本設定，然後將其添加至形狀集合的末端。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | 建立指定形狀的副本，並將其添加至形狀集合的末端。複製的形狀保留原始位置與大小。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | 建立指定形狀的副本，並將其添加至形狀集合的末端。新形狀保留 *sourceShape* 的寬度與高度。 |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | 建立指定形狀的副本，並將其添加至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | 建立一個使用預設範本樣式的新連接線形狀，並將其添加至形狀集合的末端。 |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | 建立一個新連接線形狀，並將其添加至形狀集合的末端，可選擇套用預設範本樣式。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | 建立一個新的空白群組形狀，並將其添加至形狀集合的末端。群組框架會自動調整以容納加入的任何形狀。 |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | 建立一個新群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組添加至形狀集合的末端。 |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | 建立一個用於容納數學內容的矩形自動形狀，並將其添加至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框架，並將其添加至形狀集合的末端。 |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | 建立一個新的 OLE 物件框架，並將其添加至形狀集合的末端。 |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定圖像的新圖片框架，並將其添加至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | 建立一個新的 Section Zoom 框架，並將其添加至形狀集合的末端。 |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | 建立一個帶有預先定義圖像的 Section Zoom 框架，並將其添加至形狀集合的末端。 |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | 建立一個 SmartArt 圖表，並將其添加至形狀集合的末端。 |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | 建立一個新的 Summary Zoom 框架，並將其添加至形狀集合的末端。 |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | 建立一個新表格，並將其添加至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | 建立一個新影片框架，並將其添加至形狀集合的末端。 |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | 建立一個新影片框架，並將其添加至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | 建立一個新 Zoom 框架，並將其添加至形狀集合的末端。 |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | 建立一個新 Zoom 框架，並將其添加至形狀集合的末端。 |
| [Clear](../../aspose.slides/ishapecollection/clear)() | 從形狀集合中移除所有形狀。 |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | 傳回指定形狀在集合中首次出現的零基索引。 |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | 建立一個連結至 CD 曲目的新音訊框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | 建立一個新音訊框架，並使用 Presentation.Audios 清單中的現有音訊物件，將其插入至形狀集合中指定的索引位置。 |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | 建立一個內嵌 WAV 檔案的新音訊框架，並將其插入至形狀集合中指定的索引位置。內嵌的音訊會加入 Presentation.Audios 集合中。 |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | 建立一個連結至外部音訊檔案的新音訊框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | 建立一個新自動形狀，並將其插入至形狀集合中指定的索引位置，套用預設範本格式。 |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | 建立一個新自動形狀，並將其插入至形狀集合中指定的索引位置，可選擇以預設範本樣式初始化。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | 建立一個新圖表，並以樣本系列資料與設定進行初始化，然後將其插入至形狀集合中指定的索引位置。 |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | 建立一個新圖表，並以樣本系列資料與設定進行初始化，並可選擇使用預設範本設定，然後將其插入至形狀集合中指定的索引位置。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。複製的形狀保留原始位置與大小。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。新形狀保留 *sourceShape* 的寬度與高度。 |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | 建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | 建立一個新連接線形狀，並將其插入至形狀集合中指定的索引位置，套用預設範本樣式。 |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | 建立一個新連接線形狀，並將其插入至形狀集合中指定的索引位置，可選擇套用預設範本樣式。 |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | 建立一個新的空白群組形狀，並將其插入至形狀集合中指定的索引位置。群組框架會自動調整以容納加入的任何形狀。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | 建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | 建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | 建立一個包含指定圖像的新圖片框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | 建立一個新的 Section Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | 建立一個帶有預先定義圖像的 Section Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | 建立一個新的 Summary Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | 建立一個新表格，並將其插入至形狀集合中指定的索引位置。 |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | 建立一個新影片框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | 建立一個新 Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | 建立一個帶有預先定義圖像的 Zoom 框架，並將其插入至形狀集合中指定的索引位置。 |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | 從形狀集合中移除指定形狀的首次出現。 |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | 從形狀集合中移除指定索引處的形狀。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | 將指定形狀移動至形狀集合中的新位置。 |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | 將指定的形狀在形狀集合中移動，從給定的索引開始依序放置。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | 建立並傳回包含所有形狀的陣列。 |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | 建立並傳回包含指定範圍內所有形狀的陣列。 |

### 另請參閱

* 介面 [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* 介面 [IShape](../ishape)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->