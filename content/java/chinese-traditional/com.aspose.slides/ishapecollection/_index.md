---
title: IShapeCollection
second_title: Aspose.Slides for Java API 參考
description: 表示形狀的集合。
type: docs
url: /zh-hant/com.aspose.slides/ishapecollection/
---
**已實作的全部介面：**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

表示形狀的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getParentGroup()](#getParentGroup--) | 取得形狀集合的父群組形狀物件。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 建立新的 chart，使用樣本系列資料與設定進行初始化，並將其加入形狀集合的末端。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 建立新的 chart，使用樣本系列資料與設定進行初始化，並將其加入形狀集合的末端。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 建立 SmartArt 圖表並將其加入形狀集合的末端。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 建立新的 chart，使用樣本系列資料與設定進行初始化，並在形狀集合中於指定索引插入它。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 建立新的 chart，使用樣本系列資料與設定進行初始化，並在形狀集合中於指定索引插入它。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立新的 OLE 物件框架並將其加入形狀集合的末端。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 建立新的 OLE 物件框架並將其加入形狀集合的末端。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立新的 OLE 物件框架並在形狀集合中於指定索引插入它。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 建立新的 OLE 物件框架並在形狀集合中於指定索引插入它。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 建立新的 Zoom 框架並將其加入形狀集合的末端。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立新的 Zoom 框架並將其加入形狀集合的末端。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 建立新的 Zoom 框架並在形狀集合中於指定索引插入它。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立帶預設影像的 Zoom 框架，並在形狀集合中於指定索引插入它。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 建立新的 Section Zoom 框架並將其加入形狀集合的末端。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立帶預設影像的 Section Zoom 框架並將其加入形狀集合的末端。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 建立新的 Section Zoom 框架，並在形狀集合中於指定索引插入它。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立帶預設影像的 Section Zoom 框架，並在形狀集合中於指定索引插入它。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 建立新的 Summary Zoom 框架並將其加入形狀集合的末端。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 建立新的 Summary Zoom 框架，並在形狀集合中於指定索引插入它。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 建立新的 video 框架並將其加入形狀集合的末端。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 建立新的 video 框架並將其加入形狀集合的末端。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 建立新的 video 框架，並在形狀集合中於指定索引插入它。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 建立連結至 CD 曲目的 audio 框架並將其加入形狀集合的末端。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 建立連結至 CD 曲目的 audio 框架，並在形狀集合中於指定索引插入它。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 建立連結至外部音訊檔案的 audio 框架並將其加入形狀集合的末端。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 建立連結至外部音訊檔案的 audio 框架，並在形狀集合中於指定索引插入它。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 建立內嵌 WAV 檔案的 audio 框架並將其加入形狀集合的末端。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中的現有 audio 物件，建立 audio 框架並將其加入形狀集合的末端。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 建立內嵌 WAV 檔案的 audio 框架，並在形狀集合中於指定索引插入它。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中的現有 audio 物件，於指定索引將 audio 框架插入形狀集合。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 傳回集合中第一個符合條件的形狀的零基索引。 |
| [toArray()](#toArray--) | 建立並傳回包含所有形狀的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回包含指定範圍內所有形狀的陣列。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 將指定形狀移動至形狀集合中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 將指定的形狀在形狀集合中重新排序，從給定的索引開始放置。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 建立具有預設格式的自動形狀，並將其加入形狀集合的末端。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 建立自動形狀並將其加入形狀集合的末端，可選擇使用預設範本格式進行初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 建立用於容納數學內容的矩形自動形狀，並將其加入形狀集合的末端。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 建立自動形狀，並在形狀集合中於指定索引插入它，套用預設範本格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 建立自動形狀，並在形狀集合中於指定索引插入它，可選擇使用預設範本樣式初始化。 |
| [addGroupShape()](#addGroupShape--) | 建立空的群組形狀並將其加入形狀集合的末端。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 建立群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組加入形狀集合的末端。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 建立空的群組形狀，並在形狀集合中於指定索引插入它。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 建立具有預設範本樣式的連接線形狀，並將其加入形狀集合的末端。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 建立連接線形狀並將其加入形狀集合的末端，可選擇套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 建立連接線形狀，並在形狀集合中於指定索引插入它，套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 建立連接線形狀，並在形狀集合中於指定索引插入它，可選擇套用預設範本樣式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立包含指定影像的圖片框架，並將其加入形狀集合的末端。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立包含指定影像的圖片框架，並在形狀集合中於指定索引插入它。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 建立新表格並將其加入形狀集合的末端。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 建立新表格，並在形狀集合中於指定索引插入它。 |
| [removeAt(int index)](#removeAt-int-) | 從形狀集合中移除指定索引處的形狀。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 從形狀集合中移除首次出現的指定形狀。 |
| [clear()](#clear--) | 移除形狀集合中的所有形狀。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本，並將其加入形狀集合的末端。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本，並將其加入形狀集合的末端。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 建立指定形狀的副本，並將其加入形狀集合的末端。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本，並在形狀集合中於指定索引插入它。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本，並在形狀集合中於指定索引插入它。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 建立指定形狀的副本，並在形狀集合中於指定索引插入它。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

取得指定索引處的元素。唯讀 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

取得形狀集合的父群組形狀物件。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

**傳回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

建立新的 chart，使用樣本系列資料與設定進行初始化，並將其加入形狀集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要加入的 chart 類型。 |
| x | float | 新 chart 的 x 座標（單位：點）。 |
| y | float | 新 chart 的 y 座標（單位：點）。 |
| width | float | chart 的寬度（單位：點）。 |
| height | float | chart 的高度（單位：點）。 |

**傳回值：**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

建立新的 chart，使用樣本系列資料與設定進行初始化，並將其加入形狀集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要加入的 chart 類型。 |
| x | float | 新 chart 的 x 座標（單位：點）。 |
| y | float | 新 chart 的 y 座標（單位：點）。 |
| width | float | chart 的寬度（單位：點）。 |
| height | float | chart 的高度（單位：點）。 |
| initWithSample | boolean | true 表示以樣本系列資料與設定初始化新 chart；false 表示建立沒有系列且僅有最小設定的 chart，以加快建立速度。 |

**傳回值：**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

建立 SmartArt 圖表並將其加入形狀集合的末端。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 圖表框架的 x 座標（單位：點）。 |
| y | float | 圖表框架的 y 座標（單位：點）。 |
| width | float | 圖表框架的寬度（單位：點）。 |
| height | float | 圖表框架的高度（單位：點）。 |
| layoutType | int | SmartArt 版面配置類型。 |

**傳回值：**
[ISmartArt](../../com.aspose.slides/ismartart) - 新建立的 [ISmartArt](../../com.aspose.slides/ismartart)。

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

建立新的 chart，使用樣本系列資料與設定進行初始化，並在形狀集合中於指定索引插入它。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要建立的 chart 類型。 |
| x | float | 新 chart 的 x 座標（單位：點）。 |
| y | float | 新 chart 的 y 座標（單位：點）。 |
| width | float | 新 chart 的寬度（單位：點）。 |
| height | float | 新 chart 的高度（單位：點）。 |
| index | int | 在形狀集合中插入新 chart 的零基索引。 |

**傳回值：**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

建立新的 chart，使用樣本系列資料與設定進行初始化，並在形狀集合中於指定索引插入它。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 要建立的 chart 類型。 |
| x | float | 新 chart 的 x 座標（單位：點）。 |
| y | float | 新 chart 的 y 座標（單位：點）。 |
| width | float | 新 chart 的寬度（單位：點）。 |
| height | float | 新 chart 的高度（單位：點）。 |
| index | int | 在形狀集合中插入新 chart 的零基索引。 |
| initWithSample | boolean | true 表示以樣本系列資料與設定初始化新 chart；false 表示建立沒有系列且僅有最小設定的 chart，以加快建立速度。 |
| initWithSample | boolean | 設為 true 可使用樣本系列資料與設定初始化新圖表；設為 false 則建立無系列且僅有最少設定的圖表，能加快建立速度。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框架，並將其加入形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 OLE 框架的 x 座標，以點為單位。 |
| y | float | 新 OLE 框架的 y 座標，以點為單位。 |
| width | float | 新 OLE 框架的寬度，以點為單位。 |
| height | float | 新 OLE 框架的高度，以點為單位。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 資料資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框架，並將其加入形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 OLE 框架的 x 座標，以點為單位。 |
| y | float | 新 OLE 框架的 y 座標，以點為單位。 |
| width | float | 新 OLE 框架的寬度，以點為單位。 |
| height | float | 新 OLE 框架的高度，以點為單位。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 連結檔案的路徑。此路徑會以原樣儲存在簡報中。若指定相對路徑，於從不同目錄開啟簡報時檔案將無法存取。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框架，並在指定的索引位置插入至形狀集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 OLE 物件框架的零基索引。 |
| x | float | 新 OLE 框架的 x 座標，以點為單位。 |
| y | float | 新 OLE 框架的 y 座標，以點為單位。 |
| width | float | 新 OLE 框架的寬度，以點為單位。 |
| height | float | 新 OLE 框架的高度，以點為單位。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 資料資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框架，並在指定的索引位置插入至形狀集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 OLE 物件框架的零基索引。 |
| x | float | 新 OLE 框架的 x 座標，以點為單位。 |
| y | float | 新 OLE 框架的 y 座標，以點為單位。 |
| width | float | 新 OLE 框架的寬度，以點為單位。 |
| height | float | 新 OLE 框架的高度，以點為單位。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 連結檔案的路徑。此路徑會以原樣儲存在簡報中。若指定相對路徑，於從不同目錄開啟簡報時檔案將無法存取。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框架，並將其加入形狀集合的末端。

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Zoom 框架的高度，以點為單位。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架所參照的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

建立一個新的 Zoom 框架，並將其加入形狀集合的末端。

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Zoom 框架的高度，以點為單位。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架所參照的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參照投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框架，並在指定的索引位置插入至形狀集合。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Zoom 物件
>  （假設 "Presentation.pptx" 簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 Zoom 框架的零基索引。 |
| x | float | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Zoom 框架的高度，以點為單位。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架所參照的 [ISlide](../../com.aspose.slides/islide)。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

建立一個帶預設圖像的 Zoom 框架，並在指定的索引位置插入至形狀集合。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Zoom 物件
>  (假設 "Presentation.pptx" 簡報中至少有兩張投影片)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 Zoom 框架的零基索引。 |
| x | float | 新 Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Zoom 框架的高度，以點為單位。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架所參照的 [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參照投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框架，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範在集合的末端新增 Section Zoom 物件
>  (假設在 "Presentation.pptx" 簡報中至少有兩個節)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶預設圖像的 Section Zoom 框架，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範在集合的末端新增 Section Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在 Section Zoom 框架內顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框架，並在指定的索引位置插入至形狀集合。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Section Zoom 物件
>  (假設 "Presentation.pptx" 簡報中至少有兩個節)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 Section Zoom 框架的零基索引。 |
| x | float | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶預設圖像的 Section Zoom 框架，並在指定的索引位置插入至形狀集合。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Section Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 Section Zoom 框架的零基索引。 |
| x | float | 新 Section Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Section Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Section Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Section Zoom 框架的高度，以點為單位。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在 Section Zoom 框架內顯示的圖像。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

建立一個新的 Summary Zoom 框架，並將其加入形狀集合的末端。

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新 Summary Zoom 框架的 x 座標，以點為單位。 |
| y | float | 新 Summary Zoom 框架的 y 座標，以點為單位。 |
| width | float | 新 Summary Zoom 框架的寬度，以點為單位。 |
| height | float | 新 Summary Zoom 框架的高度，以點為單位。 |
|  |  |  |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**傳回值：**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index.

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Summary Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the Summary Zoom frame. |
| x | float | The x-coordinate of the new Summary Zoom frame, in points. |
| y | float | The y-coordinate of the new Summary Zoom frame, in points. |
| width | float | The width of the new Summary Zoom frame, in points. |
| height | float | The height of the new Summary Zoom frame, in points. |

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**傳回值：**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


Creates a new video frame and adds it to the end of the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | java.lang.String | The path or name of the video file to embed. |

**傳回值：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Creates a new video frame and adds it to the end of the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| video | [IVideo](../../com.aspose.slides/ivideo) | The [IVideo](../../com.aspose.slides/ivideo) to embed in the video frame. |

**傳回值：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


Creates a new video frame and inserts it into the shape collection at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the video frame. |
| x | float | The x-coordinate of the new video frame, in points. |
| y | float | The y-coordinate of the new video frame, in points. |
| width | float | The width of the new video frame, in points. |
| height | float | The height of the new video frame, in points. |
| fname | java.lang.String | The path or name of the video file to embed. |

**傳回值：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


Creates a new audio frame linked to a CD track and adds it to the end of the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | java.lang.String | The path or name of the external audio file to link. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| fname | java.lang.String | The path or name of the external audio file to link. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. The embedded audio is added to the Presentation.Audios collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | java.io.InputStream | An input stream containing WAV audio data to embed. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | An [IAudio](../../com.aspose.slides/iaudio) instance from the Presentation.Audios collection. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. The embedded audio is added to the Presentation.Audios collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio_stream | java.io.InputStream | An input stream containing WAV audio data to embed. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based index at which to insert the audio frame. |
| x | float | The x-coordinate of the new audio frame, in points. |
| y | float | The y-coordinate of the new audio frame, in points. |
| width | float | The width of the new audio frame, in points. |
| height | float | The height of the new audio frame, in points. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | An [IAudio](../../com.aspose.slides/iaudio) instance from the Presentation.Audios collection to embed. |

**傳回值：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


Returns the zero-based index of the first occurrence of the specified shape in the collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | The shape to locate in the collection. |

**傳回值：**
int - The zero-based index of the first occurrence of the shape in the shape collection if found; otherwise, \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


Creates and returns an array that contains all shapes.

**傳回值：**
com.aspose.slides.IShape[] - 一個 [IShape](../../com.aspose.slides/ishape) 物件的陣列。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


Creates and returns an array that contains all shapes in the specified range.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| startIndex | int | The index of the first shape to return. |
| count | int | The number of shapes to return. |

**傳回值：**
com.aspose.slides.IShape[] - 一個 [IShape](../../com.aspose.slides/ishape) 物件的陣列。
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


Moves the specified shape to a new position within the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based target index where the shape will be placed. |
| shape | [IShape](../../com.aspose.slides/ishape) | The [IShape](../../com.aspose.slides/ishape) to move within the collection. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


Moves the specified shapes within the shape collection, placing them starting at the given index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | The zero-based target index where the first specified shape will be placed; subsequent shapes follow in the order provided. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | One or more [IShape](../../com.aspose.slides/ishape) instances to move within the collection. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


Creates a new auto shape with default formatting and adds it to the end of the shape collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | The [ShapeType](../../com.aspose.slides/shapetype) of the auto shape to add. |
| x | float | 形狀框架的 x 坐標（以點為單位）。 |
| y | float | 形狀框架的 y 坐標（以點為單位）。 |
| width | float | 形狀框架的寬度（以點為單位）。 |
| height | float | 形狀框架的高度（以點為單位）。 |

**返回值:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新的自動形狀，並將其新增至形狀集合的末端，此外還可以選擇以預設範本格式進行初始化。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要新增的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標（以點為單位）。 |
| y | float | 形狀框架的 y 坐標（以點為單位）。 |
| width | float | 形狀框架的寬度（以點為單位）。 |
| height | float | 形狀框架的高度（以點為單位）。 |
| createFromTemplate | boolean | 若為 true，則為新形狀套用預設範本樣式（簡易樣式、置中文字且名稱非空）；若為 false，則以所有屬性設定為預設值的方式建立形狀。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

建立一個新的矩形自動形狀以容納數學內容，並將其新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 形狀框架的 x 坐標（以點為單位）。 |
| y | float | 形狀框架的 y 坐標（以點為單位）。 |
| width | float | 形狀框架的寬度（以點為單位）。 |
| height | float | 形狀框架的高度（以點為單位）。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

建立一個新的自動形狀，並依指定索引將其插入形狀集合，同時套用預設範本格式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入新自動形狀的零基索引。 |
| shapeType | int | 要插入的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標（以點為單位）。 |
| y | float | 形狀框架的 y 坐標（以點為單位）。 |
| width | float | 形狀框架的寬度（以點為單位）。 |
| height | float | 形狀框架的高度（以點為單位）。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新的自動形狀，並依指定索引將其插入形狀集合，可選擇以預設範本樣式進行初始化。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入自動形狀的零基索引。 |
| shapeType | int | 要插入的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標（以點為單位）。 |
| y | float | 形狀框架的 y 坐標（以點為單位）。 |
| width | float | 形狀框架的寬度（以點為單位）。 |
| height | float | 形狀框架的高度（以點為單位）。 |
| createFromTemplate | boolean | 若為 true，則套用預設範本樣式（包括非空名稱、簡易樣式與置中文字）；若為 false，則以所有屬性設定為預設值的方式建立形狀。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

建立一個新的空白群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以容納加入的任何形狀。

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

建立一個新的群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 包含要轉換為形狀之向量內容的 [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | 群組框架的 x 坐標（以點為單位）。 |
| y | float | 群組框架的 y 坐標（以點為單位）。 |
| width | float | 群組框架的寬度（以點為單位）。 |
| height | float | 群組框架的高度（以點為單位）。 |

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

建立一個新的空白群組形狀，並依指定索引將其插入形狀集合。群組的框架會自動調整以容納加入的任何形狀。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入群組形狀的零基索引。 |

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

建立一個具備預設範本樣式的連接線形狀，並將其新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要新增的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 x 坐標（以點為單位）。 |
| y | float | 連接線框架的 y 坐標（以點為單位）。 |
| width | float | 連接線框架的寬度（以點為單位）。 |
| height | float | 連接線框架的高度（以點為單位）。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新的連接線形狀，並將其新增至形狀集合的末端，可選擇套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要建立的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 x 坐標（以點為單位）。 |
| y | float | 連接線框架的 y 坐標（以點為單位）。 |
| width | float | 連接線框架的寬度（以點為單位）。 |
| height | float | 連接線框架的高度（以點為單位）。 |
| createFromTemplate | boolean | 若為 true，則套用預設範本樣式（包括非空名稱、簡易樣式）；若為 false，則以預設屬性值建立連接線。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

建立一個新的連接線形狀，並依指定索引將其插入形狀集合，套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入連接線形狀的零基索引。 |
| shapeType | int | 要插入的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 x 坐標（以點為單位）。 |
| y | float | 連接線框架的 y 坐標（以點為單位）。 |
| width | float | 連接線框架的寬度（以點為單位）。 |
| height | float | 連接線框架的高度（以點為單位）。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新的連接線形狀，並依指定索引將其插入形狀集合，可選擇套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入連接線形狀的零基索引。 |
| shapeType | int | 要插入的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 x 坐標（以點為單位）。 |
| y | float | 連接線框架的 y 坐標（以點為單位）。 |
| width | float | 連接線框架的寬度（以點為單位）。 |
| height | float | 連接線框架的高度（以點為單位）。 |
| createFromTemplate | boolean | 若為 true，則套用預設範本樣式（包括非空名稱、簡易樣式）；若為 false，則以預設屬性值建立連接線。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定影像的新圖片框，並將其新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中的形狀類型，以下各種線條除外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 圖片框的 x 坐標（以點為單位）。 |
| y | float | 圖片框的 y 坐標（以點為單位）。 |
| width | float | 圖片框的寬度（以點為單位）。 |
| height | float | 圖片框的高度（以點為單位）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定影像的新圖片框，並依指定索引將其插入形狀集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入圖片框的零基索引。 |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中的形狀類型，以下各種線條除外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 圖片框的 x 坐標（以點為單位）。 |
| y | float | 圖片框的 y 坐標（以點為單位）。 |
| width | float | 圖片框的寬度（以點為單位）。 |
| height | float | 圖片框的高度（以點為單位）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

建立一個新表格，並將其新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 表格的 x 坐標（以點為單位）。 |
| y | float | 表格的 y 坐標（以點為單位）。 |
| columnWidths | double[] | 以點為單位，代表表格欄寬的 double 陣列。 |
| rowHeights | double[] | 以點為單位，代表表格列高的 double 陣列。 |

**返回值:**
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Creates a new table and inserts it into the shape collection at the specified index.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 table 的基於零的索引。 |
| x | float | table 的 x 座標（單位：點）。 |
| y | float | table 的 y 座標（單位：點）。 |
| columnWidths | double[] | 表示 table 欄寬的 double 陣列（單位：點）。 |
| rowHeights | double[] | 表示 table 列高的 double 陣列（單位：點）。 |

**傳回：**
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the shape at the specified index from the shape collection.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之 shape 的基於零的索引。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Removes the first occurrence of the specified shape from the shape collection.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要移除的 [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public abstract void clear()
```

Removes all shapes from the shape collection.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and adds it to the end of the shape collection.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 shape。 |
| x | float | clone 後 shape 框架的 x 座標（單位：點）。 |
| y | float | clone 後 shape 框架的 y 座標（單位：點）。 |
| width | float | clone 後 shape 框架的寬度（單位：點）。 |
| height | float | clone 後 shape 框架的高度（單位：點）。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The new shape retains the width and height of the sourceShape .

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | clone 後 shape 框架的 x 座標（單位：點）。 |
| y | float | clone 後 shape 框架的 y 座標（單位：點）。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Creates a copy of the specified shape and adds it to the end of the shape collection. The cloned shape retains the original's position and size.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 [IShape](../../com.aspose.slides/ishape)。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 clone shape 的基於零的索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | clone 後 shape 框架的 x 座標（單位：點）。 |
| y | float | clone 後 shape 框架的 y 座標（單位：點）。 |
| width | float | clone 後 shape 框架的寬度（單位：點）。 |
| height | float | clone 後 shape 框架的高度（單位：點）。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The new shape retains the width and height of the sourceShape .

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 clone shape 的基於零的索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | clone 後 shape 框架的 x 座標（單位：點）。 |
| y | float | clone 後 shape 框架的 y 座標（單位：點）。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Creates a copy of the specified shape and inserts it into the shape collection at the specified index. The cloned shape retains the original's position and size.

**Parameters:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 clone shape 的基於零的索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要 clone 的 [IShape](../../com.aspose.slides/ishape)。 |

**傳回：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape).