---
title: ShapeCollection
second_title: Aspose.Slides for Java API 參考
description: 表示形狀的集合。
type: docs
url: /zh-hant/com.aspose.slides/shapecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

表示形狀的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 建立新的圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 建立新的圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 建立 SmartArt 圖表並將其新增至形狀集合的末端。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 建立新的圖表，使用範例系列資料和設定進行初始化，並將其插入至形狀集合中指定的索引位置。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 建立新的圖表，使用範例系列資料和設定進行初始化，並將其插入至形狀集合中指定的索引位置。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 建立新的 Zoom 框架並將其新增至形狀集合的末端。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立新的 Zoom 框架並將其新增至形狀集合的末端。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 建立新的 Zoom 框架並將其插入形狀集合中指定的索引位置。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 建立帶有預定圖像的 Zoom 框架並將其插入形狀集合中指定的索引位置。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 建立新的 Section Zoom 框架並將其新增至形狀集合的末端。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立帶有預定圖像的 Section Zoom 框架並將其新增至形狀集合的末端。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 建立新的 Section Zoom 框架並將其插入至形狀集合中指定的索引位置。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 建立帶有預定圖像的 Section Zoom 框架並將其插入至形狀集合中指定的索引位置。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 建立新的 Summary Zoom 框架並將其新增至形狀集合的末端。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 建立新的 Summary Zoom 框架並將其插入形狀集合中指定的索引位置。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立新的 OLE 物件框架並將其新增至形狀集合的末端。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 建立新的 OLE 物件框架並將其新增至形狀集合的末端。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 建立新的 OLE 物件框架並將其插入形狀集合中指定的索引位置。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 建立新的 OLE 物件框架並將其插入形狀集合中指定的索引位置。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 建立新的影片框架並將其新增至形狀集合的末端。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 建立新的影片框架並將其新增至形狀集合的末端。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 建立新的影片框架並將其插入形狀集合中指定的索引位置。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 建立連結至 CD 曲目的音訊框架並將其新增至形狀集合的末端。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 建立連結至 CD 曲目的音訊框架並將其插入形狀集合中指定的索引位置。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 建立連結至外部音訊檔案的音訊框架並將其新增至形狀集合的末端。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 建立連結至外部音訊檔案的音訊框架並將其插入形狀集合中指定的索引位置。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 建立內嵌 WAV 檔案的音訊框架並將其新增至形狀集合的末端。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 建立內嵌 WAV 檔案的音訊框架並將其插入形狀集合中指定的索引位置。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中現有的音訊物件，建立新的音訊框架並將其新增至形狀集合的末端。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用 Presentation.Audios 清單中現有的音訊物件，建立新的音訊框架並將其插入形狀集合中指定的索引位置。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 返回指定形狀在集合中首次出現的零基索引。 |
| [toArray()](#toArray--) | 建立並返回包含所有形狀的陣列。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 建立並返回包含指定範圍內所有形狀的陣列。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 將指定形狀移動到形狀集合中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 將指定形狀在形狀集合中移動，從給定的索引開始放置它們。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 建立具有預設格式的新自動形狀並將其新增至形狀集合的末端。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 建立新自動形狀並將其新增至形狀集合的末端，可選地使用預設範本格式初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 建立用於容納數學內容的矩形自動形狀，並將其新增至形狀集合的末端。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 建立新自動形狀並將其插入形狀集合中指定的索引位置，套用預設範本格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 建立新自動形狀並將其插入形狀集合中指定的索引位置，可選地使用預設範本樣式初始化。 |
| [addGroupShape()](#addGroupShape--) | 建立新的空白群組形狀並將其新增至形狀集合的末端。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 建立新群組形狀，將指定的 SVG 圖像轉換為單獨的形狀，並將產生的群組新增至形狀集合的末端。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 建立新的空白群組形狀並將其插入形狀集合中指定的索引位置。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 建立具有預設範本樣式的新連接形狀並將其新增至形狀集合的末端。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 建立新連接形狀並將其新增至形狀集合的末端，可選地套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 建立新連接形狀並將其插入形狀集合中指定的索引位置，套用預設範本樣式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 建立新連接形狀並將其插入形狀集合中指定的索引位置，可選地套用預設範本樣式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立包含指定圖像的圖片框架並將其新增至形狀集合的末端。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 建立包含指定圖像的圖片框架並將其插入形狀集合中指定的索引位置。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 建立新表格並將其新增至形狀集合的末端。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 建立新表格並將其插入形狀集合中指定的索引位置。 |
| [removeAt(int index)](#removeAt-int-) | 從形狀集合中移除指定索引處的形狀。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 從形狀集合中移除指定形狀的首次出現。 |
| [clear()](#clear--) | 從形狀集合中移除所有形狀。 |
| [iterator()](#iterator--) | 返回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 Java 迭代器。 |
| [getParentGroup()](#getParentGroup--) | 取得形狀集合的父群組形狀物件。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本並將其新增至形狀集合的末端。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本並將其新增至形狀集合的末端。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 建立指定形狀的副本並將其新增至形狀集合的末端。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 建立指定形狀的副本並將其插入形狀集合中指定的索引位置。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 建立指定形狀的副本並將其插入形狀集合中指定的索引位置。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 建立指定形狀的副本並將其插入形狀集合中指定的索引位置。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合中實際包含的元素數量。唯讀  int .

**返回:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

取得指定索引處的元素。唯讀 [IShape](../../com.aspose.slides/ishape).

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

建立新的圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // 實例化代表 PPTX 檔案的 Presentation 類別
>  Presentation pres = new Presentation();
>  try {
>      // 存取第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 新增具有預設資料的圖表
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // 設定圖表標題
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // 設定第一系列顯示數值
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // 設定圖表資料工作表的索引
>      int defaultWorksheetIndex = 0;
>      // 取得圖表資料工作表
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // 刪除預設產生的系列與類別
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // 新增系列
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // 新增類別
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // 取得第一個圖表系列
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // 填充系列資料
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // 設定系列的填色
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // 取得第二個圖表系列
>      series = chart.getChartData().getSeries().get_Item(1);
>      // 填充系列資料
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // 設定系列的填色
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // 設定第一個標籤顯示類別名稱
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // 設定系列在第三個標籤顯示數值
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // 將 PPTX 檔案儲存至磁碟
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | int | 要新增的圖表類型。 |
| x | float | 新圖表的 x 座標（單位：點）。 |
| y | float | 新圖表的 y 座標（單位：點）。 |
| width | float | 圖表的寬度（單位：點）。 |
| height | float | 圖表的高度（單位：點）。 |

**返回:**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

建立新的圖表，使用範例系列資料和設定進行初始化，並將其新增至形狀集合的末端。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | int | 要新增的圖表類型。 |
| x | float | 新圖表的 x 座標（單位：點）。 |
| y | float | 新圖表的 y 座標（單位：點）。 |
| width | float | 圖表的寬度（單位：點）。 |
| height | float | 圖表的高度（單位：點）。 |
| initWithSample | boolean | true 表示以範例系列資料和設定初始化新圖表；false 表示建立不含系列且僅含最小設定的圖表，以加快建立速度。 |

**返回:**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

建立 SmartArt 圖表並將其新增至形狀集合的末端。

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 圖表框架的 x 座標（單位：點）。 |
| y | float | 圖表框架的 y 座標（單位：點）。 |
| width | float | 圖表框架的寬度（單位：點）。 |
| height | float | 圖表框架的高度（單位：點）。 |
| layoutType | int | SmartArt 版面配置類型。 |

**返回:**
[ISmartArt](../../com.aspose.slides/ismartart) - 新建立的 [ISmartArt](../../com.aspose.slides/ismartart)。
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

建立新的圖表，使用範例系列資料和設定進行初始化，並將其插入形狀集合中指定的索引位置。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | int | 要建立的圖表類型。 |
| x | float | 新圖表的 x 座標（單位：點）。 |
| y | float | 新圖表的 y 座標（單位：點）。 |
| width | float | 新圖表的寬度（單位：點）。 |
| height | float | 新圖表的高度（單位：點）。 |
| index | int | 要將新圖表插入至形狀集合的零基索引位置。 |

**返回:**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

建立新的圖表，使用範例系列資料和設定進行初始化，並將其插入形狀集合中指定的索引位置。
| x | float | 新圖表的 x 坐標，單位為點。 |
| y | float | 新圖表的 y 坐標，單位為點。 |
| width | float | 新圖表的寬度，單位為點。 |
| height | float | 新圖表的高度，單位為點。 |
| index | int | 在形狀集合中插入新圖表的零基索引。 |
| initWithSample | boolean | 若為 true，使用範例系列資料和設定初始化新圖表；若為 false，則在無系列且僅有最小設定的情況下建立圖表，這樣可加快建立速度。 |

**返回值:**
[IChart](../../com.aspose.slides/ichart) - 新建立的 [IChart](../../com.aspose.slides/ichart)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範將 Zoom 物件新增到集合的末端
>  （假設 "Presentation.pptx" 簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Zoom 框的寬度，單位為點。 |
| height | float | 新 Zoom 框的高度，單位為點。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 此 Zoom 框所參照的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

建立一個新的 Zoom 框，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範將 Zoom 物件新增到集合的末端
>  （假設「Presentation.pptx」簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Zoom 框的寬度，單位為點。 |
| height | float | 新 Zoom 框的高度，單位為點。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 此 Zoom 框所參照的 [ISlide](../../com.aspose.slides/islide)；必須屬於此簡報。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參照投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

建立一個新的 Zoom 框，並在指定索引處插入到形狀集合中。

--------------------

> ``` 
> 此範例示範在集合的指定索引處建立並插入 Zoom 物件
>  (假設在「Presentation.pptx」簡報中至少有兩張投影片)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Zoom 框的零基索引。 |
| x | float | 新 Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Zoom 框的寬度，單位為點。 |
| height | float | 新 Zoom 框的高度，單位為點。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 此 Zoom 框所參照的 [ISlide](../../com.aspose.slides/islide)。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

建立一個帶有預先定義圖像的 Zoom 框，並在指定索引處插入到形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Zoom 物件
>  （假設在「Presentation.pptx」簡報中至少有兩張投影片）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Zoom 框的零基索引。 |
| x | float | 新 Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Zoom 框的寬度，單位為點。 |
| height | float | 新 Zoom 框的高度，單位為點。 |
| slide | [ISlide](../../com.aspose.slides/islide) | 此 Zoom 框所參照的 [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 參照投影片 [IPPImage](../../com.aspose.slides/ippimage) 的圖像。 |

**返回值:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新建立的 [IZoomFrame](../../com.aspose.slides/izoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範將 Section Zoom 物件新增到集合的末端
>  （假設「Presentation.pptx」簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 Section Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Section Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Section Zoom 框的寬度，單位為點。 |
| height | float | 新 Section Zoom 框的高度，單位為點。 |
| section | [ISection](../../com.aspose.slides/isection) | 此 Section Zoom 框所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶有預先定義圖像的 Section Zoom 框，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範將 Section Zoom 物件新增到集合的末端
>  （假設「Presentation.pptx」簡報中至少有兩個章節）:
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
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 Section Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Section Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Section Zoom 框的寬度，單位為點。 |
| height | float | 新 Section Zoom 框的高度，單位為點。 |
| section | [ISection](../../com.aspose.slides/isection) | 此 Section Zoom 框所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在 Section Zoom 框內顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

建立一個新的 Section Zoom 框，並在指定索引處插入到形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Section Zoom 物件
>  （假設「Presentation.pptx」簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Section Zoom 框的零基索引。 |
| x | float | 新 Section Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Section Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Section Zoom 框的寬度，單位為點。 |
| height | float | 新 Section Zoom 框的高度，單位為點。 |
| section | [ISection](../../com.aspose.slides/isection) | 此 Section Zoom 框所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

建立一個帶有預先定義圖像的 Section Zoom 框，並在指定索引處插入到形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Section Zoom 物件
>  （假設「Presentation.pptx」簡報中至少有兩個章節）:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Section Zoom 框的零基索引。 |
| x | float | 新 Section Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Section Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Section Zoom 框的寬度，單位為點。 |
| height | float | 新 Section Zoom 框的高度，單位為點。 |
| section | [ISection](../../com.aspose.slides/isection) | 此 Section Zoom 框所參照的 [ISection](../../com.aspose.slides/isection)；必須屬於此簡報且至少包含一張投影片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在 Section Zoom 框內顯示的圖像。 |

**返回值:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新建立的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

建立一個新的 Summary Zoom 框，並將其加入形狀集合的末端。

--------------------

> ```
> 此範例示範將 Summary Zoom 物件新增到集合的末端
>  (假設「Presentation.pptx」簡報中至少有兩個章節):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 Summary Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Summary Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Summary Zoom 框的寬度，單位為點。 |
| height | float | 新 Summary Zoom 框的高度，單位為點。 |

此方法建立一個新的 Summary Zoom，並為此簡報中的所有章節放入一組物件。

**返回值:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

建立一個新的 Summary Zoom 框，並在指定索引處插入到形狀集合中。

--------------------

> ```
> 此範例示範在集合的指定索引處建立並插入 Summary Zoom 物件
>  （假設「Presentation.pptx」簡報中至少有兩個章節）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 Summary Zoom 框的零基索引。 |
| x | float | 新 Summary Zoom 框的 x 坐標，單位為點。 |
| y | float | 新 Summary Zoom 框的 y 坐標，單位為點。 |
| width | float | 新 Summary Zoom 框的寬度，單位為點。 |
| height | float | 新 Summary Zoom 框的高度，單位為點。 |

此方法建立一個匯總 Zoom 框，彙總此簡報中所有章節的摘要連結。

**返回值:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新建立的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框，並將其加入形狀集合的末端。

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // 實例化代表 PPTX 的 Presentation 類別
>  Presentation pres = new Presentation();
>  try
>  {
>      // 取得第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 載入 Excel 檔案至串流
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // 建立用於嵌入的資料物件
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // 新增 Ole 物件框架形狀
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // 將 PPTX 寫入磁碟
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 OLE 框的 x 坐標，單位為點。 |
| y | float | 新 OLE 框的 y 坐標，單位為點。 |
| width | float | 新 OLE 框的寬度，單位為點。 |
| height | float | 新 OLE 框的高度，單位為點。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 有關嵌入 OLE 資料的資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框，並將其加入形狀集合的末端。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | float | 新 OLE 框的 x 坐標，單位為點。 |
| y | float | 新 OLE 框的 y 坐標，單位為點。 |
| width | float | 新 OLE 框的寬度，單位為點。 |
| height | float | 新 OLE 框的高度，單位為點。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 連結檔案的路徑。此路徑會原樣儲存在簡報中。若指定相對路徑，則在從不同目錄開啟簡報時，檔案將無法存取。 |

**返回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

建立一個新的 OLE 物件框，並在指定索引處插入到形狀集合中。

--------------------

> ```
> 此範例示範在第二個索引處插入 OLE 物件：
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 插入 OLE 物件框的零基索引。 |
| x | float | 新 OLE 框的 x 座標（單位為點）。 |
| y | float | 新 OLE 框的 y 座標（單位為點）。 |
| width | float | 新 OLE 框的寬度（單位為點）。 |
| height | float | 新 OLE 框的高度（單位為點）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 資料資訊（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**傳回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

建立一個新的 OLE 物件框，並將其插入至指定索引的形狀集合中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入 OLE 物件框的零基索引。 |
| x | float | 新 OLE 框的 x 座標（單位為點）。 |
| y | float | 新 OLE 框的 y 座標（單位為點）。 |
| width | float | 新 OLE 框的寬度（單位為點）。 |
| height | float | 新 OLE 框的高度（單位為點）。 |
| className | java.lang.String | OLE 物件的類別名稱。 |
| path | java.lang.String | 指向連結檔案的路徑。此路徑會原樣儲存在簡報中。若指定相對路徑，則在從不同目錄開啟簡報時檔案將無法存取。 |

**傳回值:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新建立的 OLE 物件框。

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

建立一個新的影片框，並將其新增至形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新影片框的 x 座標（單位為點）。 |
| y | float | 新影片框的 y 座標（單位為點）。 |
| width | float | 新影片框的寬度（單位為點）。 |
| height | float | 新影片框的高度（單位為點）。 |
| fname | java.lang.String | 要嵌入之影片檔案的路徑或名稱。 |

**傳回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

建立一個新的影片框，並將其新增至形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新影片框的 x 座標（單位為點）。 |
| y | float | 新影片框的 y 座標（單位為點）。 |
| width | float | 新影片框的寬度（單位為點）。 |
| height | float | 新影片框的高度（單位為點）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要嵌入於影片框的 [IVideo](../../com.aspose.slides/ivideo)。 |

**傳回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

建立一個新的影片框，並將其插入至指定索引的形狀集合中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入影片框的零基索引。 |
| x | float | 新影片框的 x 座標（單位為點）。 |
| y | float | 新影片框的 y 座標（單位為點）。 |
| width | float | 新影片框的寬度（單位為點）。 |
| height | float | 新影片框的高度（單位為點）。 |
| fname | java.lang.String | 要嵌入之影片檔案的路徑或名稱。 |

**傳回值:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新建立的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

建立一個連結至 CD 軌道的新音訊框，並將其新增至形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

建立一個連結至 CD 軌道的新音訊框，並將其插入至指定索引的形狀集合中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音訊框的零基索引。 |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

建立一個連結至外部音訊檔的新音訊框，並將其新增至形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| fname | java.lang.String | 要連結之外部音訊檔案的路徑或名稱。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

建立一個連結至外部音訊檔的新音訊框，並將其插入至指定索引的形狀集合中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音訊框的零基索引。 |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| fname | java.lang.String | 要連結之外部音訊檔案的路徑或名稱。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

建立一個嵌入 WAV 檔案的新音訊框，並將其新增至形狀集合的末端。嵌入的音訊會加入至 Presentation.Audios 集合。

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Instantiates a presentation class that represents a presentation file
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Loads the the wav sound file to stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Adds the Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Sets the Play Mode and Volume of the Audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Writes the PowerPoint file to disk
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| audio_stream | java.io.InputStream | 包含要嵌入之 WAV 音訊資料的輸入串流。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

建立一個嵌入 WAV 檔案的新音訊框，並將其插入至指定索引的形狀集合中。嵌入的音訊會加入至 Presentation.Audios 集合。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音訊框的零基索引。 |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| audio_stream | java.io.InputStream | 包含要嵌入之 WAV 音訊資料的輸入串流。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

建立一個新的音訊框，並使用 Presentation.Audios 清單中的現有音訊物件將其新增至形狀集合的末端。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 來自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 實例。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

建立一個新的音訊框，並使用 Presentation.Audios 清單中的現有音訊物件將其插入至指定索引的形狀集合中。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要插入音訊框的零基索引。 |
| x | float | 新音訊框的 x 座標（單位為點）。 |
| y | float | 新音訊框的 y 座標（單位為點）。 |
| width | float | 新音訊框的寬度（單位為點）。 |
| height | float | 新音訊框的高度（單位為點）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 要嵌入的來自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 實例。 |

**傳回值:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新建立的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

傳回集合中指定形狀首次出現的零基索引。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中定位的形狀。 |

**傳回值:**
int - 若在形狀集合中找到形狀，則傳回它首次出現的零基索引；否則傳回 \u20131。

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

建立並傳回包含所有形狀的陣列。

**傳回值:**
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 物件的陣列。

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

建立並傳回包含指定範圍內所有形狀的陣列。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | 要傳回之第一個形狀的索引。 |
| count | int | 要傳回的形狀數量。 |

**傳回值:**
com.aspose.slides.IShape[] - 包含 [IShape](../../com.aspose.slides/ishape) 物件的陣列。

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

將指定的形狀移動至形狀集合中的新位置。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 形狀將被放置的零基目標索引。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中移動的 [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

將指定的形狀在形狀集合中移動，從給定的索引開始依序放置。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 第一個指定形狀將被放置的零基目標索引；其後的形狀將依照提供的順序依次放置。 |
| 形狀 | [IShape\[\]](../../com.aspose.slides/ishape) | 一個或多個 [IShape](../../com.aspose.slides/ishape) 實例，以在集合中移動。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

建立一個具有預設格式的新自動圖形，並將其新增至圖形集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要加入的自動圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標，單位為點。 |
| y | float | 形狀框架的 y 坐標，單位為點。 |
| width | float | 形狀框架的寬度，單位為點。 |
| height | float | 形狀框架的高度，單位為點。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新自動圖形，並將其新增至圖形集合的末端，必要時以預設範本格式初始化。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要加入的自動圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標，單位為點。 |
| y | float | 形狀框架的 y 坐標，單位為點。 |
| width | float | 形狀框架的寬度，單位為點。 |
| height | float | 形狀框架的高度，單位為點。 |
| createFromTemplate | boolean | true：將預設範本樣式（簡單樣式、置中文字且名稱非空）套用至新圖形；false：以所有屬性預設值建立圖形。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

建立一個矩形自動圖形以承載數學內容，並將其新增至圖形集合的末端。

--------------------

> ```
> The following example shows how to add Mathematical Equation in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 形狀框架的 x 坐標，單位為點。 |
| y | float | 形狀框架的 y 坐標，單位為點。 |
| width | float | 形狀框架的寬度，單位為點。 |
| height | float | 形狀框架的高度，單位為點。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

建立一個新自動圖形，並依指定索引插入圖形集合，同時套用預設範本格式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入新自動圖形的零基索引。 |
| shapeType | int | 要插入的自動圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標，單位為點。 |
| y | float | 形狀框架的 y 坐標，單位為點。 |
| width | float | 形狀框架的寬度，單位為點。 |
| height | float | 形狀框架的高度，單位為點。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新自動圖形，並依指定索引插入圖形集合，必要時以預設範本樣式初始化。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入自動圖形的零基索引。 |
| shapeType | int | 要插入的自動圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形狀框架的 x 坐標，單位為點。 |
| y | float | 形狀框架的 y 坐標，單位為點。 |
| width | float | 形狀框架的寬度，單位為點。 |
| height | float | 形狀框架的高度，單位為點。 |
| createFromTemplate | boolean | true：將預設範本樣式（包含非空名稱、簡單樣式、置中文字）套用至新圖形；false：以所有屬性預設值建立圖形。 |

**返回值:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新建立的 [IAutoShape](../../com.aspose.slides/iautoshape)。

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

建立一個空的群組圖形，並將其新增至圖形集合的末端。群組的框架會自動調整以容納加入的任何圖形。

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instantiate Presentation class
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accessing the shape collection of slides
>      IShapeCollection slideShapes = sld.getShapes();
>      // Adding a group shape to the slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Adding shapes inside added group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Adding group shape frame
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Write the PPTX file to disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

建立一個新群組圖形，將指定的 SVG 圖像轉換為個別圖形，並將產生的群組新增至圖形集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 包含要轉換為圖形之向量內容的 [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | 群組框架的 x 坐標，單位為點。 |
| y | float | 群組框架的 y 坐標，單位為點。 |
| width | float | 群組框架的寬度，單位為點。 |
| height | float | 群組框架的高度，單位為點。 |

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

建立一個空的群組圖形，並依指定索引插入圖形集合。群組的框架會自動調整以容納加入的任何圖形。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入群組圖形的零基索引。 |

**返回值:**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新建立的 [IGroupShape](../../com.aspose.slides/igroupshape)。

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

建立一個具有預設範本樣式的連接器圖形，並將其新增至圖形集合的末端。

--------------------

> ```
> 以下範例說明如何在 PowerPoint 簡報中於兩個形狀（橢圓與矩形）之間新增一個連接線（彎曲連接線）。
>  
>  // 實例化代表 PPTX 檔案的 Presentation 類別
>  Presentation pres = new Presentation();
>  try {
>      // 存取特定投影片的形狀集合
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // 新增一個橢圓自動形狀
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // 新增一個矩形自動形狀
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // 將連接線形狀新增至投影片的形狀集合
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // 使用連接線將形狀連接起來
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // 呼叫 reroute 以設定形狀之間的自動最短路徑
>      connector.reroute();
>      // 儲存簡報
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要加入的連接器圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接器框架的 x 坐標，單位為點。 |
| y | float | 連接器框架的 y 坐標，單位為點。 |
| width | float | 連接器框架的寬度，單位為點。 |
| height | float | 連接器框架的高度，單位為點。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新連接器圖形，並將其新增至圖形集合的末端，必要時套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 要建立的連接器圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接器框架的 x 坐標，單位為點。 |
| y | float | 連接器框架的 y 坐標，單位為點。 |
| width | float | 連接器框架的寬度，單位為點。 |
| height | float | 連接器框架的高度，單位為點。 |
| createFromTemplate | boolean | true：套用預設範本樣式（非空名稱、簡單樣式）；false：以預設屬性值建立連接器。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

建立一個新連接器圖形，並依指定索引插入圖形集合，同時套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入連接器圖形的零基索引。 |
| shapeType | int | 要插入的連接器圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接器框架的 x 坐標，單位為點。 |
| y | float | 連接器框架的 y 坐標，單位為點。 |
| width | float | 連接器框架的寬度，單位為點。 |
| height | float | 連接器框架的高度，單位為點。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

建立一個新連接器圖形，並依指定索引插入圖形集合，必要時套用預設範本樣式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入連接器圖形的零基索引。 |
| shapeType | int | 要插入的連接器圖形的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 連接器框架的 x 坐標，單位為點。 |
| y | float | 連接器框架的 y 坐標，單位為點。 |
| width | float | 連接器框架的寬度，單位為點。 |
| height | float | 連接器框架的高度，單位為點。 |
| createFromTemplate | boolean | true：套用預設範本樣式（非空名稱、簡單樣式）；false：以預設屬性值建立連接器。 |

**返回值:**
[IConnector](../../com.aspose.slides/iconnector) - 新建立的 [IConnector](../../com.aspose.slides/iconnector)。

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定圖像的圖片框架，並將其新增至圖形集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中的圖形類型，除所有線條類型外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 圖片框架的 x 坐標，單位為點。 |
| y | float | 圖片框架的 y 坐標，單位為點。 |
| width | float | 圖片框架的寬度，單位為點。 |
| height | float | 圖片框架的高度，單位為點。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框架中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

建立一個包含指定圖像的圖片框架，並依指定索引插入圖形集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入圖片框架的零基索引。 |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中的圖形類型，除所有線條類型外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 圖片框架的 x 坐標，單位為點。 |
| y | float | 圖片框架的 y 坐標，單位為點。 |
| width | float | 圖片框架的寬度，單位為點。 |
| height | float | 圖片框架的高度，單位為點。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在圖片框架中顯示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回值:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新建立的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

建立一個新表格，並將其新增至圖形集合的末端。

--------------------

> ```
> 以下範例說明如何在 PowerPoint 簡報中新增表格。
>  
>  // 實例化代表 PPTX 檔案的 Presentation 類別
>  Presentation pres = new Presentation();
>  try
>  {
>      // 存取第一張投影片
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 定義欄寬與列高
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // 將表格形狀新增至投影片
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // 設定每個儲存格的邊框格式
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // 合併第 1 列的第 1 與第 2 個儲存格
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // 在合併儲存格中加入文字
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // 將 PPTX 儲存至磁碟
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | float | 表格的 x 坐標，以點為單位。 |
| y | float | 表格的 y 坐標，以點為單位。 |
| columnWidths | double[] | 一個雙精度陣列，表示表格欄位的寬度，以點為單位。 |
| rowHeights | double[] | 一個雙精度陣列，表示表格列的高度，以點為單位。 |

**返回值：**
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable)。

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

建立一個新表格，並將其插入至指定索引的形狀集合中。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入表格的零基索引。 |
| x | float | 表格的 x 坐標，以點為單位。 |
| y | float | 表格的 y 坐標，以點為單位。 |
| columnWidths | double[] | 一個雙精度陣列，表示表格欄位的寬度，以點為單位。 |
| rowHeights | double[] | 一個雙精度陣列，表示表格列的高度，以點為單位。 |

**返回值：**
[ITable](../../com.aspose.slides/itable) - 新建立的 [ITable](../../com.aspose.slides/itable)。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從形狀集合中移除指定索引位置的形狀。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的形狀之零基索引。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

從形狀集合中移除第一個出現的指定形狀。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要移除的 [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public final void clear()
```

從形狀集合中移除所有形狀。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

傳回一個列舉器，用於遍歷集合。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 整個集合的 java.util.Iterator。

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

取得形狀集合的父群組形狀物件。唯讀 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回值：**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

建立指定形狀的副本，並將其加入形狀集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的形狀。 |
| x | float | 新形狀框架的 x 坐標，以點為單位。 |
| y | float | 新形狀框架的 y 坐標，以點為單位。 |
| width | float | 新形狀框架的寬度，以點為單位。 |
| height | float | 新形狀框架的高度，以點為單位。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

建立指定形狀的副本，並將其加入形狀集合的末端。新形狀保留 sourceShape 的寬度與高度。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的形狀。 |
| x | float | 新形狀框架的 x 坐標，以點為單位。 |
| y | float | 新形狀框架的 y 坐標，以點為單位。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

建立指定形狀的副本，並將其加入形狀集合的末端。複製的形狀保留原始的定位與尺寸。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 複製形狀框架的 x 坐標，以點為單位。 |
| y | float | 複製形狀框架的 y 坐標，以點為單位。 |
| width | float | 複製形狀框架的寬度，以點為單位。 |
| height | float | 複製形狀框架的高度，以點為單位。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。新形狀保留 sourceShape 的寬度與高度。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 複製形狀框架的 x 坐標，以點為單位。 |
| y | float | 複製形狀框架的 y 坐標，以點為單位。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

建立指定形狀的副本，並將其插入至形狀集合中指定的索引位置。複製的形狀保留原始的定位與尺寸。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入複製形狀的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要複製的 [IShape](../../com.aspose.slides/ishape)。 |

**返回值：**
[IShape](../../com.aspose.slides/ishape) - 新建立的 [IShape](../../com.aspose.slides/ishape)。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean 。

**返回值：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object 。

**返回值：**
java.lang.Object