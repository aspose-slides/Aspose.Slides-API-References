---
title: ShapeCollection
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 表示形状的集合。
type: docs
url: /zh/com.aspose.slides/shapecollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已实现的接口：**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

表示形状的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | 创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | 创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。 |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | 创建一个SmartArt图表并将其添加到形状集合的末尾。 |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | 创建一个新的图表，使用示例系列数据和设置进行初始化，并在指定索引处插入到形状集合中。 |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | 创建一个新的图表，使用示例系列数据和设置进行初始化，并在指定索引处插入到形状集合中。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的Zoom帧并将其添加到形状集合的末尾。 |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 创建一个新的Zoom帧并将其添加到形状集合的末尾。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | 创建一个新的Zoom帧并在指定索引处插入到形状集合中。 |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | 使用预定义图像创建一个新的Zoom帧并在指定索引处插入到形状集合中。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的章节Zoom帧并将其添加到形状集合的末尾。 |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 使用预定义图像创建一个新的章节Zoom帧并将其添加到形状集合的末尾。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | 创建一个新的章节Zoom帧并在指定索引处插入到形状集合中。 |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | 使用预定义图像创建一个新的章节Zoom帧并在指定索引处插入到形状集合中。 |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | 创建一个新的摘要Zoom帧并将其添加到形状集合的末尾。 |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | 创建一个新的摘要Zoom帧并在指定索引处插入到形状集合中。 |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的OLE对象帧并将其添加到形状集合的末尾。 |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的OLE对象帧并将其添加到形状集合的末尾。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | 创建一个新的OLE对象帧并在指定索引处插入到形状集合中。 |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | 创建一个新的OLE对象帧并在指定索引处插入到形状集合中。 |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | 创建一个新的视频帧并将其添加到形状集合的末尾。 |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | 创建一个新的视频帧并将其添加到形状集合的末尾。 |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | 创建一个新的视频帧并在指定索引处插入到形状集合中。 |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | 创建一个链接到CD轨道的音频帧并将其添加到形状集合的末尾。 |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | 创建一个链接到CD轨道的音频帧并在指定索引处插入到形状集合中。 |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的音频帧并将其添加到形状集合的末尾。 |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | 创建一个链接到外部音频文件的音频帧并在指定索引处插入到形状集合中。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | 创建一个包含嵌入WAV文件的音频帧并将其添加到形状集合的末尾。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | 创建一个包含嵌入WAV文件的音频帧并在指定索引处插入到形状集合中。 |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | 使用Presentation.Audios列表中的现有音频对象创建一个新的音频帧并将其添加到形状集合的末尾。 |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | 使用Presentation.Audios列表中的现有音频对象创建一个新的音频帧并在指定索引处插入到形状集合中。 |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | 返回集合中指定形状第一次出现的零基索引。 |
| [toArray()](#toArray--) | 创建并返回包含所有形状的数组。 |
| [toArray(int startIndex, int count)](#toArray-int-int-) | 创建并返回包含指定范围内所有形状的数组。 |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | 将指定形状移动到形状集合中的新位置。 |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | 在形状集合中移动指定的形状，从给定索引开始放置它们。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | 使用默认格式创建一个新的自动形状并将其添加到形状集合的末尾。 |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | 创建一个新的自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。 |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | 创建一个用于承载数学内容的矩形自动形状并将其添加到形状集合的末尾。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | 创建一个新的自动形状并在指定索引处插入到形状集合中，应用默认模板格式。 |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | 创建一个新的自动形状并在指定索引处插入到形状集合中，可选择使用默认模板样式进行初始化。 |
| [addGroupShape()](#addGroupShape--) | 创建一个新的空组形状并将其添加到形状集合的末尾。 |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | 创建一个新的组形状，将指定的SVG图像转换为单独的形状，并将生成的组添加到形状集合的末尾。 |
| [insertGroupShape(int index)](#insertGroupShape-int-) | 创建一个新的空组形状并在指定索引处插入到形状集合中。 |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | 使用默认模板样式创建一个新的连接器形状并将其添加到形状集合的末尾。 |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | 创建一个新的连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | 创建一个新的连接器形状并在指定索引处插入到形状集合中，应用默认模板样式。 |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | 创建一个新的连接器形状并在指定索引处插入到形状集合中，可选择应用默认模板样式。 |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的图片框并将其添加到形状集合的末尾。 |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | 创建一个包含指定图像的图片框并在指定索引处插入到形状集合中。 |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | 创建一个新表格并将其添加到形状集合的末尾。 |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | 创建一个新表格并在指定索引处插入到形状集合中。 |
| [removeAt(int index)](#removeAt-int-) | 从形状集合中移除指定索引处的形状。 |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | 从形状集合中移除指定形状的第一次出现。 |
| [clear()](#clear--) | 从形状集合中移除所有形状。 |
| [iterator()](#iterator--) | 返回一个遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的java迭代器。 |
| [getParentGroup()](#getParentGroup--) | 获取形状集合的父组形状对象。 |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | 创建指定形状的副本并将其添加到形状集合的末尾。 |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | 创建指定形状的副本并在指定索引处插入到形状集合中。 |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | 创建指定形状的副本并在指定索引处插入到形状集合中。 |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | 创建指定形状的副本并在指定索引处插入到形状集合中。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个值，指示对集合的访问是否同步（线程安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根对象。 |
### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int 。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

获取指定索引处的元素。只读 [IShape](../../com.aspose.slides/ishape)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // 实例化表示 PPTX 文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 添加具有默认数据的图表
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // 设置图表标题
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // 设置第一系列显示数值
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // 设置图表数据工作表的索引
>      int defaultWorksheetIndex = 0;
>      // 获取图表数据工作表
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // 删除默认生成的系列和类别
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // 添加新系列
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // 添加新类别
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // 获取第一条图表系列
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // 填充系列数据
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // 设置系列的填充颜色
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // 获取第二条图表系列
>      series = chart.getChartData().getSeries().get_Item(1);
>      // 填充系列数据
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // 设置系列的填充颜色
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // 设置第一个标签显示类别名称
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // 设置系列在第三个标签上显示数值
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // 将 PPTX 文件保存到磁盘
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 x 坐标（单位：点）。 |
| y | float | 新图表的 y 坐标（单位：点）。 |
| width | float | 图表的宽度（单位：点）。 |
| height | float | 图表的高度（单位：点）。 |

**返回：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

创建一个新的图表，使用示例系列数据和设置进行初始化，并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要添加的图表类型。 |
| x | float | 新图表的 x 坐标（单位：点）。 |
| y | float | 新图表的 y 坐标（单位：点）。 |
| width | float | 图表的宽度（单位：点）。 |
| height | float | 图表的高度（单位：点）。 |
| initWithSample | boolean | true：使用示例系列数据和设置初始化新图表；false：创建没有系列且仅具备最小设置的图表，以加快创建速度。 |

**返回：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

创建一个SmartArt图表并将其添加到形状集合的末尾。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 图表框架的 x 坐标（单位：点）。 |
| y | float | 图表框架的 y 坐标（单位：点）。 |
| width | float | 图表框架的宽度（单位：点）。 |
| height | float | 图表框架的高度（单位：点）。 |
| layoutType | int | SmartArt 布局类型。 |

**返回：**
[ISmartArt](../../com.aspose.slides/ismartart) - 新创建的 [ISmartArt](../../com.aspose.slides/ismartart)。
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

创建一个新的图表，使用示例系列数据和设置进行初始化，并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要创建的图表类型。 |
| x | float | 新图表的 x 坐标（单位：点）。 |
| y | float | 新图表的 y 坐标（单位：点）。 |
| width | float | 新图表的宽度（单位：点）。 |
| height | float | 新图表的高度（单位：点）。 |
| index | int | 在形状集合中插入新图表的零基索引。 |

**返回：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

创建一个新的图表，使用示例系列数据和设置进行初始化，并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要创建的图表类型。 |
| x | float | 新图表的 x 坐标（单位：点）。 |
| y | float | 新图表的 y 坐标（单位：点）。 |
| width | float | 新图表的宽度（单位：点）。 |
| height | float | 新图表的高度（单位：点）。 |
| index | int | 在形状集合中插入新图表的零基索引。 |
| initWithSample | boolean | true：使用示例系列数据和设置初始化新图表；false：创建没有系列且仅具备最小设置的图表，以加快创建速度。 |

**返回：**
[IChart](../../com.aspose.slides/ichart) - 新创建的 [IChart](../../com.aspose.slides/ichart)。
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

创建一个新的Zoom帧并将其添加到形状集合的末尾。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新Zoom帧的宽度（单位：点）。 |
| height | float | 新Zoom帧的高度（单位：点）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom帧引用的 [ISlide](../../com.aspose.slides/islide)；必须属于此演示文稿。 |

**返回：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

创建一个新的Zoom帧并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示向集合末尾添加 Zoom 对象
>  (假设在 "Presentation.pptx" 演示文稿中至少有两张幻灯片)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新Zoom帧的宽度（单位：点）。 |
| height | float | 新Zoom帧的高度（单位：点）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom帧引用的 [ISlide](../../com.aspose.slides/islide)；必须属于此演示文稿。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 引用幻灯片 [IPPImage](../../com.aspose.slides/ippimage) 的图像。 |

**返回：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

创建一个新的Zoom帧并在指定索引处插入到形状集合中。

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入Zoom帧的零基索引。 |
| x | float | 新Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新Zoom帧的宽度（单位：点）。 |
| height | float | 新Zoom帧的高度（单位：点）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom帧引用的 [ISlide](../../com.aspose.slides/islide)。 |

**返回：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

创建一个预定义图像的Zoom帧并在指定索引处插入到形状集合中。

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入Zoom帧的零基索引。 |
| x | float | 新Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新Zoom帧的宽度（单位：点）。 |
| height | float | 新Zoom帧的高度（单位：点）。 |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom帧引用的 [ISlide](../../com.aspose.slides/islide)。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 引用幻灯片 [IPPImage](../../com.aspose.slides/ippimage) 的图像。 |

**返回：**
[IZoomFrame](../../com.aspose.slides/izoomframe) - 新创建的 [IZoomFrame](../../com.aspose.slides/izoomframe)。
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

创建一个新的章节Zoom帧并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示将 Section Zoom 对象添加到集合的末尾
>  (假设在 "Presentation.pptx" 演示文稿中至少有两个章节)：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新章节Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新章节Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新章节Zoom帧的宽度（单位：点）。 |
| height | float | 新章节Zoom帧的高度（单位：点）。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节Zoom帧引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |

**返回：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

创建一个预定义图像的章节Zoom帧并将其添加到形状集合的末尾。

--------------------

> ```
> 此示例演示将 Section Zoom 对象添加到集合的末尾
>  (假设在 "Presentation.pptx" 演示文稿中至少有两个章节)：
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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新章节Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新章节Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新章节Zoom帧的宽度（单位：点）。 |
| height | float | 新章节Zoom帧的高度（单位：点）。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节Zoom帧引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 在章节Zoom帧内显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

创建一个新的章节Zoom帧并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入章节Zoom帧的零基索引。 |
| x | float | 新章节Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新章节Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新章节Zoom帧的宽度（单位：点）。 |
| height | float | 新章节Zoom帧的高度（单位：点）。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节Zoom帧引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |

**返回：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

创建一个预定义图像的章节Zoom帧并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Section Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
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
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入章节Zoom帧的零基索引。 |
| x | float | 新章节Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新章节Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新章节Zoom帧的宽度（单位：点）。 |
| height | float | 新章节Zoom帧的高度（单位：点）。 |
| section | [ISection](../../com.aspose.slides/isection) | 章节Zoom帧引用的 [ISection](../../com.aspose.slides/isection)；必须属于此演示文稿且至少包含一张幻灯片。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 显示在章节Zoom帧中的图像。 |

**返回：**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - 新创建的 [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)。
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

创建一个新的摘要Zoom帧并将其添加到形状集合的末尾。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新摘要Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新摘要Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新摘要Zoom帧的宽度（单位：点）。 |
| height | float | 新摘要Zoom帧的高度（单位：点）。 |

--------------------

此方法创建一个新的摘要Zoom，并将所有章节的对象集合放入其中。

**返回：**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新创建的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

创建一个新的摘要Zoom帧并在指定索引处插入到形状集合中。

--------------------

> ```
> 此示例演示在集合的指定索引处创建并插入 Summary Zoom 对象
>  （假设在 "Presentation.pptx" 演示文稿中至少有两个章节）：
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入摘要Zoom帧的零基索引。 |
| x | float | 新摘要Zoom帧的 x 坐标（单位：点）。 |
| y | float | 新摘要Zoom帧的 y 坐标（单位：点）。 |
| width | float | 新摘要Zoom帧的宽度（单位：点）。 |
| height | float | 新摘要Zoom帧的高度（单位：点）。 |

--------------------

此方法创建一个聚合所有章节摘要链接的摘要Zoom帧。

**返回：**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - 新创建的 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)。
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

创建一个新的OLE对象帧并将其添加到形状集合的末尾。

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // 实例化表示 PPTX 的 Presentation 类
>  Presentation pres = new Presentation();
>  try
>  {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 将 cel 文件加载到流
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
>      // 创建用于嵌入的数据对象
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // 添加 Ole 对象帧形状
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // 将 PPTX 写入磁盘
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新OLE帧的 x 坐标（单位：点）。 |
| y | float | 新OLE帧的 y 坐标（单位：点）。 |
| width | float | 新OLE帧的宽度（单位：点）。 |
| height | float | 新OLE帧的高度（单位：点）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 关于嵌入OLE数据（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）的信息。 |

**返回：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

创建一个新的OLE对象帧并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新OLE帧的 x 坐标（单位：点）。 |
| y | float | 新OLE帧的 y 坐标（单位：点）。 |
| width | float | 新OLE帧的宽度（单位：点）。 |
| height | float | 新OLE帧的高度（单位：点）。 |
| className | java.lang.String | OLE对象的类名。 |
| path | java.lang.String | 链接文件的路径。

此路径会原样存储在演示文稿中。如果指定相对路径，则在从不同目录打开演示文稿时文件将无法访问。 |

**返回：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

创建一个新的OLE对象帧并在指定索引处插入到形状集合中。

--------------------

> ```
> This example demonstrates inserting an OLE object at the second index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入OLE对象帧的零基索引。 |
| x | float | 新OLE帧的 x 坐标（单位：点）。 |
| y | float | 新OLE帧的 y 坐标（单位：点）。 |
| width | float | 新OLE帧的宽度（单位：点）。 |
| height | float | 新OLE帧的高度（单位：点）。 |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | 嵌入OLE数据的信息（[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)）。 |

**返回：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)。
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

创建一个新的OLE对象帧并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入OLE对象帧的零基索引。 |
| x | float | 新OLE帧的 x 坐标（单位：点）。 |
| y | float | 新OLE帧的 y 坐标（单位：点）。 |
| width | float | 新OLE帧的宽度（单位：点）。 |
| height | float | 新OLE帧的高度（单位：点）。 |
| className | java.lang.String | OLE对象的类名。 |
| path | java.lang.String | 链接文件的路径。

此路径会原样存储在演示文稿中。如果指定相对路径，则在从不同目录打开演示文稿时文件将无法访问。 |

**返回：**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - 新创建的 OLE 对象帧。
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

创建一个新的视频帧并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新视频帧的 x 坐标（单位：点）。 |
| y | float | 新视频帧的 y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| fname | java.lang.String | 要嵌入的视频文件的路径或名称。 |

**返回：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

创建一个新的视频帧并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新视频帧的 x 坐标（单位：点）。 |
| y | float | 新视频帧的 y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| video | [IVideo](../../com.aspose.slides/ivideo) | 要嵌入视频帧的 [IVideo](../../com.aspose.slides/ivideo)。 |

**返回：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

创建一个新的视频帧并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入视频帧的零基索引。 |
| x | float | 新视频帧的 x 坐标（单位：点）。 |
| y | float | 新视频帧的 y 坐标（单位：点）。 |
| width | float | 新视频帧的宽度（单位：点）。 |
| height | float | 新视频帧的高度（单位：点）。 |
| fname | java.lang.String | 要嵌入的视频文件的路径或名称。 |

**返回：**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - 新创建的 [IVideoFrame](../../com.aspose.slides/ivideoframe)。
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

创建一个链接到CD轨道的音频帧并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

创建一个链接到CD轨道的音频帧并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

创建一个链接到外部音频文件的音频帧并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| fname | java.lang.String | 要链接的外部音频文件的路径或名称。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

创建一个链接到外部音频文件的音频帧并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| fname | java.lang.String | 要链接的外部音频文件的路径或名称。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

创建一个包含嵌入WAV文件的音频帧并将其添加到形状集合的末尾。嵌入的音频将添加到 Presentation.Audios 集合。

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // 实例化表示演示文稿文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 获取第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 将 wav 音频文件加载到流
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // 添加音频帧
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // 设置音频的播放模式和音量
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // 将 PowerPoint 文件写入磁盘
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio_stream | java.io.InputStream | 包含 WAV 音频数据的输入流，用于嵌入。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

创建一个包含嵌入WAV文件的音频帧并在指定索引处插入到形状集合中。嵌入的音频将添加到 Presentation.Audios 集合。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio_stream | java.io.InputStream | 包含 WAV 音频数据的输入流，用于嵌入。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

创建一个新的音频帧，并使用 Presentation.Audios 列表中的现有音频对象将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 来自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 实例。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

创建一个新的音频帧，并在指定索引处使用 Presentation.Audios 列表中的现有音频对象将其插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入音频帧的零基索引。 |
| x | float | 新音频帧的 x 坐标（单位：点）。 |
| y | float | 新音频帧的 y 坐标（单位：点）。 |
| width | float | 新音频帧的宽度（单位：点）。 |
| height | float | 新音频帧的高度（单位：点）。 |
| audio | [IAudio](../../com.aspose.slides/iaudio) | 来自 Presentation.Audios 集合的 [IAudio](../../com.aspose.slides/iaudio) 实例，用于嵌入。 |

**返回：**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - 新创建的 [IAudioFrame](../../com.aspose.slides/iaudioframe)。
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

返回集合中指定形状第一次出现的零基索引。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中定位的形状。 |

**返回：**
int - 若在形状集合中找到该形状，则返回其零基索引；否则返回 \\u20131。
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

创建并返回包含所有形状的数组。

**返回：**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 对象数组。
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

创建并返回包含指定范围内所有形状的数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startIndex | int | 要返回的第一个形状的索引。 |
| count | int | 要返回的形状数量。 |

**返回：**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) 对象数组。
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

将指定形状移动到形状集合中的新位置。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要放置形状的零基目标索引。 |
| shape | [IShape](../../com.aspose.slides/ishape) | 要在集合中移动的 [IShape](../../com.aspose.slides/ishape)。 |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

在形状集合中移动指定的形状，从给定索引开始放置它们。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 首个指定形状将被放置的零基目标索引；随后形状按照提供的顺序依次放置。 |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | 一个或多个要在集合中移动的 [IShape](../../com.aspose.slides/ishape) 实例。 |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

使用默认格式创建一个新的自动形状并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标（单位：点）。 |
| y | float | 形状框架的 y 坐标（单位：点）。 |
| width | float | 形状框架的宽度（单位：点）。 |
| height | float | 形状框架的高度（单位：点）。 |

**返回：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的自动形状并将其添加到形状集合的末尾，可选择使用默认模板格式进行初始化。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标（单位：点）。 |
| y | float | 形状框架的 y 坐标（单位：点）。 |
| width | float | 形状框架的宽度（单位：点）。 |
| height | float | 形状框架的高度（单位：点）。 |
| createFromTemplate | boolean | true：将默认模板样式（简单样式、居中文本、非空名称）应用于新形状；false：创建所有属性均为默认值的形状。 |

**返回：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

使用默认格式创建一个用于承载数学内容的矩形自动形状并将其添加到形状集合的末尾。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 形状框架的 x 坐标（单位：点）。 |
| y | float | 形状框架的 y 坐标（单位：点）。 |
| width | float | 形状框架的宽度（单位：点）。 |
| height | float | 形状框架的高度（单位：点）。 |

**返回：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

创建一个新的自动形状并在指定索引处插入到形状集合中，应用默认模板格式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入新自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标（单位：点）。 |
| y | float | 形状框架的 y 坐标（单位：点）。 |
| width | float | 形状框架的宽度（单位：点）。 |
| height | float | 形状框架的高度（单位：点）。 |

**返回：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的自动形状并在指定索引处插入到形状集合中，可选择使用默认模板样式进行初始化。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入自动形状的零基索引。 |
| shapeType | int | 要插入的自动形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 形状框架的 x 坐标（单位：点）。 |
| y | float | 形状框架的 y 坐标（单位：点）。 |
| width | float | 形状框架的宽度（单位：点）。 |
| height | float | 形状框架的高度（单位：点）。 |
| createFromTemplate | boolean | true：将默认模板样式（包括非空名称、简单样式、居中文本）应用于新形状；false：创建所有属性均为默认值的形状。 |

**返回：**
[IAutoShape](../../com.aspose.slides/iautoshape) - 新创建的 [IAutoShape](../../com.aspose.slides/iautoshape)。
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

创建一个新的空组形状并将其添加到形状集合的末尾。组的框架会自动调整以适应添加的任何形状。

--------------------

> ```
> 以下示例演示如何在 PowerPoint 演示文稿的幻灯片中添加组形状。
>  
>  // 实例化 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 获取第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 访问幻灯片的形状集合
>      IShapeCollection slideShapes = sld.getShapes();
>      // 向幻灯片添加组形状
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // 向添加的组形状中添加形状
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // 添加组形状框架
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // 将 PPTX 文件写入磁盘
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

创建一个新的组形状，将指定的 SVG 图像转换为单独的形状，并将生成的组添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 包含要转换为形状的矢量内容的 [ISvgImage](../../com.aspose.slides/isvgimage)。 |
| x | float | 组框架的 x 坐标（单位：点）。 |
| y | float | 组框架的 y 坐标（单位：点）。 |
| width | float | 组框架的宽度（单位：点）。 |
| height | float | 组框架的高度（单位：点）。 |

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public



```

创建一个新的空组形状并在指定索引处插入到形状集合中。组的框架会自动调整以适应添加的任何形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入组形状的零基索引。 |

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape) - 新创建的 [IGroupShape](../../com.aspose.slides/igroupshape)。
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

使用默认模板样式创建一个新的连接器形状并将其添加到形状集合的末尾。

--------------------

> ```
> 以下示例演示如何在 PowerPoint 演示文稿中在两个形状（椭圆和矩形）之间添加连接器（弯曲连接器）。
>  
>  // 实例化一个表示 PPTX 文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try {
>      // 访问特定幻灯片的形状集合
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // 添加一个椭圆自动形状
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // 添加一个矩形自动形状
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // 向幻灯片形状集合添加一个连接器形状
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // 使用连接器连接形状
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // 调用 reroute 方法，设置形状之间的自动最短路径
>      connector.reroute();
>      // 保存演示文稿
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要添加的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标（单位：点）。 |
| y | float | 连接器框架的 y 坐标（单位：点）。 |
| width | float | 连接器框架的宽度（单位：点）。 |
| height | float | 连接器框架的高度（单位：点）。 |

**返回：**
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的连接器形状并将其添加到形状集合的末尾，可选择应用默认模板样式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 要创建的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标（单位：点）。 |
| y | float | 连接器框架的 y 坐标（单位：点）。 |
| width | float | 连接器框架的宽度（单位：点）。 |
| height | float | 连接器框架的高度（单位：点）。 |
| createFromTemplate | boolean | true：将默认模板样式（非空名称、简单样式）应用于新连接器；false：使用默认属性值创建连接器。 |

**返回：**
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

创建一个新的连接器形状并在指定索引处插入到形状集合中，应用默认模板样式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标（单位：点）。 |
| y | float | 连接器框架的 y 坐标（单位：点）。 |
| width | float | 连接器框架的宽度（单位：点）。 |
| height | float | 连接器框架的高度（单位：点）。 |

**返回：**
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

创建一个新的连接器形状并在指定索引处插入到形状集合中，可选择应用默认模板样式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入连接器形状的零基索引。 |
| shapeType | int | 要插入的连接器形状的 [ShapeType](../../com.aspose.slides/shapetype)。 |
| x | float | 连接器框架的 x 坐标（单位：点）。 |
| y | float | 连接器框架的 y 坐标（单位：点）。 |
| width | float | 连接器框架的宽度（单位：点）。 |
| height | float | 连接器框架的高度（单位：点）。 |
| createFromTemplate | boolean | true：将默认模板样式（非空名称、简单样式）应用于新连接器；false：使用默认属性值创建连接器。 |

**返回：**
[IConnector](../../com.aspose.slides/iconnector) - 新创建的 [IConnector](../../com.aspose.slides/iconnector)。
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

创建一个包含指定图像的图片框并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形状类型，除所有线类之外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 图片框的 x 坐标（单位：点）。 |
| y | float | 图片框的 y 坐标（单位：点）。 |
| width | float | 图片框的宽度（单位：点）。 |
| height | float | 图片框的高度（单位：点）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在图片框中显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回：**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新创建的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

创建一个包含指定图像的图片框并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入图片框的零基索引。 |
| shapeType | int | 指定 [ShapeType](../../com.aspose.slides/shapetype) 中包含的形状类型，除所有线类之外：<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5。 |
| x | float | 图片框的 x 坐标（单位：点）。 |
| y | float | 图片框的 y 坐标（单位：点）。 |
| width | float | 图片框的宽度（单位：点）。 |
| height | float | 图片框的高度（单位：点）。 |
| image | [IPPImage](../../com.aspose.slides/ippimage) | 要在图片框中显示的 [IPPImage](../../com.aspose.slides/ippimage)。 |

**返回：**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - 新创建的 [IPictureFrame](../../com.aspose.slides/ipictureframe)。
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

创建一个新表格并将其添加到形状集合的末尾。

--------------------

> ```
> 以下示例演示如何在 PowerPoint 演示文稿中添加表格。
>  
>  // 实例化表示 PPTX 文件的 Presentation 类
>  Presentation pres = new Presentation();
>  try
>  {
>      // 访问第一张幻灯片
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // 定义列宽和行高
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // 向幻灯片添加表格形状
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // 为每个单元格设置边框格式
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
>      // 合并第1行的第1和第2个单元格
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // 向合并后的单元格添加文本
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
+ 
>      // 将 PPTX 保存到磁盘
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 表格的 x 坐标（单位：点）。 |
| y | float | 表格的 y 坐标（单位：点）。 |
| columnWidths | double[] | 表示表格列宽（单位：点）的双精度数组。 |
| rowHeights | double[] | 表示表格行高（单位：点）的双精度数组。 |

**返回：**
[ITable](../../com.aspose.slides/itable) - 新创建的 [ITable](../../com.aspose.slides/itable)。
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

创建一个新表格并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入表格的零基索引。 |
| x | float | 表格的 x 坐标（单位：点）。 |
| y | float | 表格的 y 坐标（单位：点）。 |
| columnWidths | double[] | 表示表格列宽（单位：点）的双精度数组。 |
| rowHeights | double[] | 表示表格行高（单位：点）的双精度数组。 |

**返回：**
[ITable](../../com.aspose.slides/itable) - 新创建的 [ITable](../../com.aspose.slides/itable)。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除形状集合中指定索引处的形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的形状的零基索引。 |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

移除形状集合中指定形状的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | 要移除的 [IShape](../../com.aspose.slides/ishape)。 |

### clear() {#clear--}
```
public final void clear()
```

移除形状集合中的所有形状。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

返回一个遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - 整个集合的 java.util.Iterator。
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

获取形状集合的父组形状对象。只读 [IGroupShape](../../com.aspose.slides/igroupshape)。

**返回：**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

创建指定形状的副本并将其添加到形状集合的末尾。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位：点）。 |
| y | float | 新形状框架的 y 坐标（单位：点）。 |
| width | float | 新形状框架的宽度（单位：点）。 |
| height | float | 新形状框架的高度（单位：点）。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

创建指定形状的副本并将其添加到形状集合的末尾。新形状保留 sourceShape 的宽度和高度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的形状。 |
| x | float | 新形状框架的 x 坐标（单位：点）。 |
| y | float | 新形状框架的 y 坐标（单位：点）。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

创建指定形状的副本并将其添加到形状集合的末尾。克隆的形状保留原始的位置和大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

创建指定形状的副本并在指定索引处插入到形状集合中。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |
| width | float | 克隆形状框架的宽度（单位：点）。 |
| height | float | 克隆形状框架的高度（单位：点）。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

创建指定形状的副本并在指定索引处插入到形状集合中。新形状保留 sourceShape 的宽度和高度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |
| x | float | 克隆形状框架的 x 坐标（单位：点）。 |
| y | float | 克隆形状框架的 y 坐标（单位：点）。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

创建指定形状的副本并在指定索引处插入到形状集合中。克隆的形状保留原始的位置和大小。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 在形状集合中插入克隆形状的零基索引。 |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | 要克隆的 [IShape](../../com.aspose.slides/ishape)。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 新创建的 [IShape](../../com.aspose.slides/ishape)。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个值，指示对集合的访问是否同步（线程安全）。只读 boolean 。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根对象。只读 Object 。

**返回：**
java.lang.Object