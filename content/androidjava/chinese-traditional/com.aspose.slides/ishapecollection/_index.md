---
title: IShapeCollection
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示形狀的集合。
type: docs
url: /zh-hant/com.aspose.slides/ishapecollection/
---
**所有實作的介面：**  
com.aspose.slides.IGenericCollection  
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

表示形狀的集合。  
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getParentGroup()](#getParentGroup--) | 取得形狀集合的父群組形狀物件。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其新增至形狀集合的末端。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其新增至形狀集合的末端。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 建立一個 SmartArt 圖表並將其新增至形狀集合的末端。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其插入至指定索引的形狀集合中。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其插入至指定索引的形狀集合中。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立一個新的 OLE 物件框架並將其新增至形狀集合的末端。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 建立一個新的 OLE 物件框架並將其新增至形狀集合的末端。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立一個新的 OLE 物件框架並將其插入至指定索引的形狀集合中。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 建立一個新的 OLE 物件框架並將其插入至指定索引的形狀集合中。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 建立一個新的 Zoom 框架並將其新增至形狀集合的末端。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立一個新的 Zoom 框架並將其新增至形狀集合的末端。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 建立一個新的 Zoom 框架並將其插入至指定索引的形狀集合中。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立一個帶有預定義圖像的新 Zoom 框架，並將其插入至指定索引的形狀集合中。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 建立一個新的 Section Zoom 框架並將其新增至形狀集合的末端。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立一個帶有預定義圖像的 Section Zoom 框架並將其新增至形狀集合的末端。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 建立一個新的 Section Zoom 框架並將其插入至指定索引的形狀集合中。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立一個帶有預定義圖像的 Section Zoom 框架，並將其插入至指定索引的形狀集合中。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 建立一個新的 Summary Zoom 框架並將其新增至形狀集合的末端。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 建立一個新的 Summary Zoom 框架並將其插入至指定索引的形狀集合中。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 建立一個新的影片框架並將其新增至形狀集合的末端。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 建立一個新的影片框架並將其新增至形狀集合的末端。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 建立一個新的影片框架並將其插入至指定索引的形狀集合中。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 建立一個連結至 CD 曲目的音訊框架，並將其新增至形狀集合的末端。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 建立一個連結至 CD 曲目的音訊框架，並將其插入至指定索引的形狀集合中。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 建立一個連結至外部音訊檔案的音訊框架，並將其新增至形狀集合的末端。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 建立一個連結至外部音訊檔案的音訊框架，並將其插入至指定索引的形狀集合中。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 建立一個內嵌 WAV 檔案的音訊框架，並將其新增至形狀集合的末端。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中的既有音訊物件，建立音訊框架並將其新增至形狀集合的末端。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 建立一個內嵌 WAV 檔案的音訊框架，並將其插入至指定索引的形狀集合中。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中的既有音訊物件，於指定索引插入音訊框架。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 傳回指定形狀在集合中首次出現的零基索引。 |
| [toArray()](#toArray--) | 建立並傳回包含所有形狀的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並傳回包含指定範圍內所有形狀的陣列。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 將指定形狀移動至形狀集合中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 將指定的多個形狀在形狀集合中移動，從給定索引開始依序放置。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 建立一個預設格式的自動形狀，並將其新增至形狀集合的末端。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 建立一個自動形狀，並將其新增至形狀集合的末端，可選擇以預設範本格式初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 建立一個矩形自動形狀以承載數學內容，並將其新增至形狀集合的末端。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 建立一個自動形狀，並將其依指定索引插入形狀集合，套用預設範本格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 建立一個自動形狀，並將其依指定索引插入形狀集合，可選擇以預設範本樣式初始化。 |
| [addGroupShape()](#addGroupShape--) | 建立一個空的群組形狀，並將其新增至形狀集合的末端。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 建立一個群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 建立一個空的群組形狀，並將其依指定索引插入形狀集合。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 建立一個預設範本樣式的連接線形狀，並將其新增至形狀集合的末端。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 建立一個連接線形狀，並將其新增至形狀集合的末端，可選擇套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 建立一個連接線形狀，並將其依指定索引插入形狀集合，套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 建立一個連接線形狀，並將其依指定索引插入形狀集合，可選擇套用預設範本樣式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立一個包含指定圖像的圖片框架，並將其新增至形狀集合的末端。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立一個包含指定圖像的圖片框架，並將其依指定索引插入形狀集合。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 建立一個新表格並將其新增至形狀集合的末端。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 建立一個新表格，並將其插入至指定索引的形狀集合中。 |
| [removeAt(int index)](#removeAt-int-) | 從形狀集合中移除指定索引處的形狀。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 從形狀集合中移除首次出現的指定形狀。 |
| [clear()](#clear--) | 從形狀集合中移除全部形狀。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本，並將其新增至形狀集合的末端。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本，並將其新增至形狀集合的末端。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 建立指定形狀的副本，並將其新增至形狀集合的末端。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本，並將其依指定索引插入形狀集合。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本，並將其依指定索引插入形狀集合。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 建立指定形狀的副本，並將其依指定索引插入形狀集合。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

取得指定索引處的元素。唯讀 [IShape](../../com.aspose.slides/ishape)。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**  
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

取得形狀集合的父群組形狀物件。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | 要新增的圖表類型。 |
| x | float | 新圖表的 X 座標（點）。 |
| y | float | 新圖表的 Y 座標（點）。 |
| width | float | 圖表的寬度（點）。 |
| height | float | 圖表的高度（點）。 |

**返回值：**  
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | 要新增的圖表類型。 |
| x | float | 新圖表的 X 座標（點）。 |
| y | float | 新圖表的 Y 座標（點）。 |
| width | float | 圖表的寬度（點）。 |
| height | float | 圖表的高度（點）。 |
| initWithSample | boolean | true 表示使用樣本系列資料與設定初始化；false 表示不帶系列且僅使用最少設定，建立速度較快。 |

**返回值：**  
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

建立一個 SmartArt 圖表，並將其新增至形狀集合的末端。

--------------------

> ```
> 範例：
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
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 圖表框架的 X 座標（點）。 |
| y | float | 圖表框架的 Y 座標（點）。 |
| width | float | 圖表框架的寬度（點）。 |
| height | float | 圖表框架的高度（點）。 |
| layoutType | int | SmartArt 版面配置類型。 |

**返回值：**  
[ISmartArt](../../com.aspose.slides/ismartart) - 新建立的 [ISmartArt](../../com.aspose.slides/ismartart)。

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | 要建立的圖表類型。 |
| x | float | 新圖表的 X 座標（點）。 |
| y | float | 新圖表的 Y 座標（點）。 |
| width | float | 圖表的寬度（點）。 |
| height | float | 圖表的高度（點）。 |
| index | int | 插入新圖表的零基索引位置。 |

**返回值：**  
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

建立一個新圖表，使用樣本系列資料與設定進行初始化，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | 要建立的圖表類型。 |
| x | float | 新圖表的 X 座標（點）。 |
| y | float | 新圖表的 Y 座標（點）。 |
| width | float | 圖表的寬度（點）。 |
| height | float | 圖表的高度（點）。 |
| index | int | 插入新圖表的零基索引位置。 |
| initWithSample | boolean | true 表示使用樣本系列資料與設定初始化；false 表示不帶系列且僅使用最少設定，建立速度較快。 |

**返回值：**  
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 OLE 框架的 X 座標（點）。 |
| y | float | 新 OLE 框架的 Y 座標（點）。 |
| width | float | 新 OLE 框架的寬度（點）。 |
| height | float | 新 OLE 框架的高度（點）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 內嵌 OLE 資料資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值：**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 OLE 框架的 X 座標（點）。 |
| y | float | 新 OLE 框架的 Y 座標（點）。 |
| width | float | 新 OLE 框架的寬度（點）。 |
| height | float | 新 OLE 框架的高度（點）。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 連結檔案的路徑。

此路徑會以原樣儲存於簡報中。若指定相對路徑，於不同目錄開啟簡報時檔案將無法存取。 |

**返回值：**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框架，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 OLE 物件框架的零基索引位置。 |
| x | float | 新 OLE 框架的 X 座標（點）。 |
| y | float | 新 OLE 框架的 Y 座標（點）。 |
| width | float | 新 OLE 框架的寬度（點）。 |
| height | float | 新 OLE 框架的高度（點）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 內嵌 OLE 資料資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值：**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框架，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 OLE 物件框架的零基索引位置。 |
| x | float | 新 OLE 框架的 X 座標（點）。 |
| y | float | 新 OLE 框架的 Y 座標（點）。 |
| width | float | 新 OLE 框架的寬度（點）。 |
| height | float | 新 OLE 框架的高度（點）。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 連結檔案的路徑。

此路徑會以原樣儲存於簡報中。若指定相對路徑，於不同目錄開啟簡報時檔案將無法存取。 |

**返回值：**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框架，並將其新增至形狀集合的末端。

--------------------

> ```
> 此範例示範將 Zoom 物件新增至集合的末端
>  （假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 Zoom 框架的 X 座標（點）。 |
| y | float | 新 Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Zoom 框架的寬度（點）。 |
| height | float | 新 Zoom 框架的高度（點）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架參考的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |

**返回值：**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoom                 IZoomFrame addZoomFrame(float x, float y, float             width, float height, ISlide slide        , IPPImage image)
```

建立一個新的 Zoom 框架，並將其新增至形狀集合的末端。

--------------------

> ```
> 此範例示範將 Zoom 物件新增至集合的末端
>  （假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
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


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 Zoom 框架的 X 座標（點）。 |
| y | float | 新 Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Zoom 框架的寬度（點）。 |
| height | float | 新 Zoom 框架的高度（點）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架參考的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參考投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值：**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框架，並將其插入至指定索引的形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引建立並插入 Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 Zoom 框架的零基索引位置。 |
| x | float | 新 Zoom 框架的 X 座標（點）。 |
| y | float | 新 Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Zoom 框架的寬度（點）。 |
| height | float | 新 Zoom 框架的高度（點）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架參考的 [ISlide](../../com.aspose.slides/islide)。 |

**返回值：**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

建立一個帶有預定義圖像的 Zoom 框架，並將其插入至指定索引的形狀集合中。

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 Zoom 框架的零基索引位置。 |
| x | float | 新 Zoom 框架的 X 座標（點）。 |
| y | float | 新 Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Zoom 框架的寬度（點）。 |
| height | float | 新 Zoom 框架的高度（點）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom 框架參考的 [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參考投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值：**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框架，並將其新增至形狀集合的末端。

--------------------

> ```
> 此範例示範將 Section Zoom 物件新增至集合的末端
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 Section Zoom 框架的 X 座標（點）。 |
| y | float | 新 Section Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Section Zoom 框架的寬度（點）。 |
| height | float | 新 Section Zoom 框架的高度（點）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架參考的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值：**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶有預定義圖像的 Section Zoom 框架，並將其新增至形狀集合的末端。

--------------------

> ```
> 此範例示範將 Section Zoom 物件新增至集合的末端
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 Section Zoom 框架的 X 座標（點）。 |
| y | float | 新 Section Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Section Zoom 框架的寬度（點）。 |
| height | float | 新 Section Zoom 框架的高度（點）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架參考的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 在 Section Zoom 框架中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值：**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框架，並將其插入至指定索引的形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引建立並插入 Section Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 Section Zoom 框架的零基索引位置。 |
| x | float | 新 Section Zoom 框架的 X 座標（點）。 |
| y | float | 新 Section Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Section Zoom 框架的寬度（點）。 |
| height | float | 新 Section Zoom 框架的高度（點）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架參考的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值：**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶有預定義圖像的 Section Zoom 框架，並將其插入至指定索引的形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引建立並插入 Section Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 Section Zoom 框架的零基索引位置。 |
| x | float | 新 Section Zoom 框架的 X 座標（點）。 |
| y | float | 新 Section Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Section Zoom 框架的寬度（點）。 |
| height | float | 新 Section Zoom 框架的高度（點）。 |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom 框架參考的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 在 Section Zoom 框架中顯示的圖像。 |

**返回值：**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

建立一個新的 Summary Zoom 框架，並將其新增至形狀集合的末端。

--------------------

> ```
> 此範例示範將 Summary Zoom 物件新增至集合的末端
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新 Summary Zoom 框架的 X 座標（點）。 |
| y | float | 新 Summary Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Summary Zoom 框架的寬度（點）。 |
| height | float | 新 Summary Zoom 框架的高度（點）。 |

--------------------

此方法建立一個彙總所有章節連結的 Summary Zoom 框架。

**返回值：**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

建立一個新的 Summary Zoom 框架，並將其插入至指定索引的形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引建立並插入 Summary Zoom 物件
>  （假設在 "Presentation.pptx" 簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入 Summary Zoom 框架的零基索引位置。 |
| x | float | 新 Summary Zoom 框架的 X 座標（點）。 |
| y | float | 新 Summary Zoom 框架的 Y 座標（點）。 |
| width | float | 新 Summary Zoom 框架的寬度（點）。 |
| height | float | 新 Summary Zoom 框架的高度（點）。 |

--------------------

此方法建立一個彙總所有章節連結的 Summary Zoom 框架。

**返回值：**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

建立一個新的影片框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新影片框架的 X 座標（點）。 |
| y | float | 新影片框架的 Y 座標（點）。 |
| width | float | 影片框架的寬度（點）。 |
| height | float | 影片框架的高度（點）。 |
| fname | java.lang.String | 要嵌入的影片檔案路徑或名稱。 |

**返回值：**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

建立一個新的影片框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新影片框架的 X 座標（點）。 |
| y | float | 新影片框架的 Y 座標（點）。 |
| width | float | 影片框架的寬度（點）。 |
| height | float | 影片框架的高度（點）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要嵌入影片框架的 [IVideo](../../com.aspose.slides/ivideo)。 |

**返回值：**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

建立一個新的影片框架，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入影片框架的零基索引位置。 |
| x | float | 新影片框架的 X 座標（點）。 |
| y | float | 新影片框架的 Y 座標（點）。 |
| width | float | 影片框架的寬度（點）。 |
| height | float | 影片框架的高度（點）。 |
| fname | java.lang.String | 要嵌入的影片檔案路徑或名稱。 |

**返回值：**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

建立一個連結至 CD 曲目的音訊框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

建立一個連結至 CD 曲目的音訊框架，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入音訊框架的零基索引位置。 |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

建立一個連結至外部音訊檔案的音訊框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| fname | java.lang.String | 要連結的外部音訊檔案路徑或名稱。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

建立一個連結至外部音訊檔案的音訊框架，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入音訊框架的零基索引位置。 |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| fname | java.lang.String | 要連結的外部音訊檔案路徑或名稱。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

建立一個內嵌 WAV 檔案的音訊框架，並將其新增至形狀集合的末端。內嵌音訊會加入至 Presentation.Audios 集合。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| audio_stream | java.io.InputStream | 含有 WAV 音訊資料的輸入串流。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

建立一個音訊框架，使用 Presentation.Audios 清單中的既有音訊物件，將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 來自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 例項。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

建立一個內嵌 WAV 檔案的音訊框架，並將其插入至指定索引的形狀集合中。內嵌音訊會加入至 Presentation.Audios 集合。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入音訊框架的零基索引位置。 |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| audio_stream | java.io.InputStream | 含有 WAV 音訊資料的輸入串流。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

建立一個音訊框架，使用 Presentation.Audios 清單中的既有音訊物件，將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入音訊框架的零基索引位置。 |
| x | float | 新音訊框架的 X 座標（點）。 |
| y | float | 新音訊框架的 Y 座標（點）。 |
| width | float | 音訊框架的寬度（點）。 |
| height | float | 音訊框架的高度（點）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 來自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 例項。 |

**返回值：**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

傳回指定形狀在集合中首次出現的零基索引。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中定位的形狀。 |

**返回值：**  
int - 若在形狀集合中找到則傳回該形狀的零基索引；否則傳回 \-1。

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

建立並傳回包含所有形狀的陣列。

**返回值：**  
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 物件的陣列。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

建立並傳回指定範圍內所有形狀的陣列。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| startIndex | int | 要返回的第一個形狀的索引。 |
| count | int | 要返回的形狀數量。 |

**返回值：**  
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 物件的陣列。

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

將指定形狀移動至形狀集合中的新位置。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 形狀要放置的目標零基索引。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中移動的 [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

將指定的多個形狀在形狀集合中移動，從給定索引開始依序放置。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 第一個指定形狀要放置的目標零基索引；之後的形狀依提供的順序依次放置。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | 一或多個要在集合中移動的 [IShape](../../com.aspose.slides/ishape) 實例。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

建立一個預設格式的自動形狀，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeType | int | 要新增的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 X 座標（點）。 |
| y | float | 形狀框架的 Y 座標（點）。 |
| width | float | 形狀框架的寬度（點）。 |
| height | float | 形狀框架的高度（點）。 |

**返回值：**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個自動形狀，並將其新增至形狀集合的末端，可選擇以預設範本格式初始化。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeType | int | 要新增的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 X 座標（點）。 |
| y | float | 形狀框架的 Y 座標（點）。 |
| width | float | 形狀框架的寬度（點）。 |
| height | float | 形狀框架的高度（點）。 |
| createFromTemplate | boolean | true 表示套用預設範本樣式（簡易樣式、置中文字且名稱非空）；false 表示使用所有預設屬性建立形狀。 |

**返回值：**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

建立一個矩形自動形狀以承載數學內容，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 形狀框架的 X 座標（點）。 |
| y | float | 形狀框架的 Y 座標（點）。 |
| width | float | 形狀框架的寬度（點）。 |
| height | float | 形狀框架的高度（點）。 |

**返回值：**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

建立一個自動形狀，並將其依指定索引插入形狀集合，套用預設範本格式。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入新自動形狀的零基索引。 |
| shapeType | int | 要插入的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 X 座標（點）。 |
| y | float | 形狀框架的 Y 座標（點）。 |
| width | float | 形狀框架的寬度（點）。 |
| height | float | 形狀框架的高度（點）。 |

**返回值：**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個自動形狀，並將其依指定索引插入形狀集合，可選擇以預設範本樣式初始化。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入自動形狀的零基索引。 |
| shapeType | int | 要插入的自動形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 X 座標（點）。 |
| y | float | 形狀框架的 Y 座標（點）。 |
| width | float | 形狀框架的寬度（點）。 |
| height | float | 形狀框架的高度（點）。 |
| createFromTemplate | boolean | true 表示套用預設範本樣式（包括非空名稱、簡易樣式、置中文字）；false 表示使用所有預設屬性建立形狀。 |

**返回值：**  
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

建立一個空的群組形狀，並將其新增至形狀集合的末端。群組的框架會自動調整以容納加入的任何形狀。

**返回值：**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

建立一個群組形狀，將指定的 SVG 圖像轉換為個別形狀，並將產生的群組新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 含有向量內容的 [ISvgImage](../../com.aspose.slides/isvgimage)，將其轉換為形狀。 |
| x | float | 群組框架的 X 座標（點）。 |
| y | float | 群組框架的 Y 座標（點）。 |
| width | float | 群組框架的寬度（點）。 |
| height | float | 群組框架的高度（點）。 |

**返回值：**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

建立一個空的群組形狀，並將其依指定索引插入形狀集合。群組的框架會自動調整以容納加入的任何形狀。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入群組形狀的零基索引。 |

**返回值：**  
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

建立一個預設範本樣式的連接線形狀，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeType | int | 要新增的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 X 座標（點）。 |
| y | float | 連接線框架的 Y 座標（點）。 |
| width | float | 連接線框架的寬度（點）。 |
| height | float | 連接線框架的高度（點）。 |

**返回值：**  
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個連接線形狀，並將其新增至形狀集合的末端，可選擇套用預設範本樣式。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeType | int | 要建立的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 X 座標（點）。 |
| y | float | 連接線框架的 Y 座標（點）。 |
| width | float | 連接線框架的寬度（點）。 |
| height | float | 連接線框架的高度（點）。 |
| createFromTemplate | boolean | true 表示套用預設範本樣式（非空名稱、簡易樣式）；false 表示使用預設屬性建立連接線。 |

**返回值：**  
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

建立一個連接線形狀，並將其依指定索引插入形狀集合，套用預設範本樣式。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入連接線形狀的零基索引。 |
| shapeType | int | 要插入的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 X 座標（點）。 |
| y | float | 連接線框架的 Y 座標（點）。 |
| width | float | 連接線框架的寬度（點）。 |
| height | float | 連接線框架的高度（點）。 |

**返回值：**  
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個連接線形狀，並將其依指定索引插入形狀集合，可選擇套用預設範本樣式。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入連接線形狀的零基索引。 |
| shapeType | int | 要插入的連接線形狀的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接線框架的 X 座標（點）。 |
| y | float | 連接線框架的 Y 座標（點）。 |
| width | float | 連接線框架的寬度（點）。 |
| height | float | 連接線框架的高度（點）。 |
| createFromTemplate | boolean | true 表示套用預設範本樣式（非空名稱、簡易樣式）；false 表示使用預設屬性建立連接線。 |

**返回值：**  
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定圖像的圖片框架，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形狀類型，除所有線類型外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | 圖片框架的 X 座標（點）。 |
| y | float | 圖片框架的 Y 座標（點）。 |
| width | float | 圖片框架的寬度（點）。 |
| height | float | 圖片框架的高度（點）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框架中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值：**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定圖像的圖片框架，並將其依指定索引插入形狀集合。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入圖片框架的零基索引。 |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形狀類型，除所有線類型外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | 圖片框架的 X 座標（點）。 |
| y | float | 圖片框架的 Y 座標（點）。 |
| width | float | 圖片框架的寬度（點）。 |
| height | float | 圖片框架的高度（點）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框架中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值：**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

建立一個新表格，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| x | float | 表格的 X 座標（點）。 |
| y | float | 表格的 Y 座標（點）。 |
| columnWidths | double[] | 以點為單位的欄寬陣列。 |
| rowHeights | double[] | 以點為單位的列高陣列。 |

**返回值：**  
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

建立一個新表格，並將其插入至指定索引的形狀集合中。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入表格的零基索引。 |
| x | float | 表格的 X 座標（點）。 |
| y | float | 表格的 Y 座標（點）。 |
| columnWidths | double[] | 以點為單位的欄寬陣列。 |
| rowHeights | double[] | 以點為單位的列高陣列。 |

**返回值：**  
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable)。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除位於指定索引的形狀。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 要移除的形狀的零基索引。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

移除形狀集合中首次出現的指定形狀。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要移除的 [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除形狀集合中的全部形狀。

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

建立指定形狀的副本，並將其新增至形狀集合的末端。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的形狀。 |
| x | float | 複製形狀框架的 X 座標（點）。 |
| y | float | 複製形狀框架的 Y 座標（點）。 |
| width | float | 複製形狀框架的寬度（點）。 |
| height | float | 複製形狀框架的高度（點）。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

建立指定形狀的副本，並將其新增至形狀集合的末端。新形狀保留 sourceShape 的寬度與高度。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 複製形狀框架的 X 座標（點）。 |
| y | float | 複製形狀框架的 Y 座標（點）。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

建立指定形狀的副本，並將其新增至形狀集合的末端。複製的形狀保留原始位置與大小。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

建立指定形狀的副本，並將其插入至指定索引的形狀集合。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 複製形狀框架的 X 座標（點）。 |
| y | float | 複製形狀框架的 Y 座標（點）。 |
| width | float | 複製形狀框架的寬度（點）。 |
| height | float | 複製形狀框架的高度（點）。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

建立指定形狀的副本，並將其插入至指定索引的形狀集合。新形狀保留 sourceShape 的寬度與高度。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 複製形狀框架的 X 座標（點）。 |
| y | float | 複製形狀框架的 Y 座標（點）。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

建立指定形狀的副本，並將其插入至指定索引的形狀集合。複製的形狀保留原始位置與大小。

**參數：**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**  
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。