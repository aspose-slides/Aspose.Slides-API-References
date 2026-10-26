---
title: ShapeCollection
second_title: Aspose.Slides لـ Android عبر دليل API للجاڤا
description: يمثل مجموعة من الأشكال.
type: docs
url: /ar/com.aspose.slides/shapecollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

يمثل مجموعة من الأشكال.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار تكبير جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير جديد بصورة مُعرَّفة مسبقًا ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير قسم جديد بصورة مُعرَّفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار تكبير قسم جديد ويدخله إلى مجموعة الأشكال في الفهرس المحدد. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير قسم جديد بصورة مُعرَّفة مسبقًا ويدخله إلى مجموعة الأشكال في الفهرس المحدد. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | ينشئ إطار تكبير ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | ينشئ إطار تكبير ملخص جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويدخله في مجموعة الأشكال في الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | يرجع الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | ينقل الأشكال المحددة داخل مجموعة الأشكال، بوضعها بدءًا من الفهرس المعطى. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق قالب افتراضي. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | ينشئ شكلًا مستطيلًا تلقائيًا لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق القالب الافتراضي. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بنمط قالب افتراضي. |
| [addGroupShape()](#addGroupShape--) | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | ينشئ مجموعة أشكال فارغة جديدة ويدخلها إلى مجموعة الأشكال في الفهرس المحدد. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | ينشئ شكل موصل جديد بتنسيق قالب افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق قالب افتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق قالب افتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق تنسيق قالب افتراضي. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | ينشئ جدولًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل الشكل في الفهرس المحدد من مجموعة الأشكال. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | يزيل أول ظهور للشكل المحدد من مجموعة الأشكال. |
| [clear()](#clear--) | يزيل جميع الأشكال من مجموعة الأشكال. |
| [iterator()](#iterator--) | يرجع مكررًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكررًا جافا للمجموعة بأكملها. |
| [getParentGroup()](#getParentGroup--) | يحصل على كائن مجموعة الأشكال الأم لمجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال في الفهرس المحدد. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط  int .

**الإرجاع:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [IShape](../../com.aspose.slides/ishape).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // ينشئ كائن من الفئة Presentation التي تمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // يصل إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يضيف مخططًا ببياناته الافتراضية
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // يضبط عنوان المخطط
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // يضبط السلسلة الأولى لعرض القيم
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // يضبط الفهرس لورقة بيانات المخطط
>      int defaultWorksheetIndex = 0;
>      // يحصل على ورقة عمل بيانات المخطط
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // يحذف السلاسل والفئات المُنشأة افتراضيًا
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // يضيف سلاسل جديدة
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // يضيف فئات جديدة
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // يأخذ السلسلة الأولى للمخطط
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // يملأ بيانات السلسلة
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // يضبط لون التعبئة للسلسلة
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // يأخذ السلسلة الثانية للمخطط
>      series = chart.getChartData().getSeries().get_Item(1);
>      // يملأ بيانات السلسلة
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // يضبط لون التعبئة للسلسلة
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // يضبط التسمية الأولى لعرض اسم الفئة
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // يضبط السلسلة لعرض القيمة للتسمية الثالثة
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // يحفظ ملف PPTX إلى القرص
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إضافته. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إضافته. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |
| initWithSample | boolean | true لتهيئة المخطط الجديد ببيانات وإعدادات عينات؛ false لإنشاء المخطط بدون سلسلة وإعدادات أساسية فقط، مما يجعل الإنشاء أسرع. |

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> المثال التالي يوضح كيفية إضافة شكل ذكي في عرض PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار المخطط، بالنقاط. |
| y | float | إحداثي y لإطار المخطط، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |
| layoutType | int | نوع تخطيط SmartArt. |

**الإرجاع:**  
[ISmartArt](../../com.aspose.slides/ismartart) - الـ [ISmartArt](../../com.aspose.slides/ismartart) الذي تم إنشاؤه حديثًا.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إنشاؤه. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري الذي سيتم إدخال المخطط الجديد فيه داخل مجموعة الأشكال. |

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات وسلسلة إعدادات عينات، ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إنشاؤه. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري الذي سيتم إدخال المخطط الجديد فيه داخل مجموعة الأشكال. |
| initWithSample | boolean | true لتهيئة المخطط الجديد ببيانات وإعدادات عينات؛ false لإنشاء المخطط بدون سلسلة وإعدادات أساسية فقط، مما يجعل الإنشاء أسرع. |

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة
>  (افترض أنه يوجد على الأقل شريحتان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار التكبير؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |

**الإرجاع:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الـ [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار التكبير؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه بالشرائح. |

**الإرجاع:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الـ [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار تكبير جديد ويدخله في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة
>  (افترض أنه يوجد على الأقل شريحتان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار التكبير فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار التكبير. |

**الإرجاع:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الـ [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار تكبير جديد بصورة مُعرَّفة مسبقًا ويدخله في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة
>  (افترض أنه يوجد على الأقل شريحتان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار التكبير فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار التكبير. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه بالشرائح. |

**الإرجاع:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الـ [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**الإرجاع:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الـ [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار تكبير قسم جديد بصورة مُعرَّفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
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


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) للعرض داخل إطار تكبير القسم. |

**الإرجاع:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الـ [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

ينشئ إطار تكبير قسم جديد ويدخله إلى مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار تكبير القسم فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**الإرجاع:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الـ [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار تكبير قسم جديد بصورة مُعرَّفة مسبقًا ويدخله إلى مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> هذا المثال يوضح إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
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


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار تكبير القسم فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للعرض داخل إطار تكبير القسم. |

**الإرجاع:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الـ [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

ينشئ إطار تكبير ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> هذا المثال يوضح إضافة كائن Summary Zoom إلى نهاية مجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |

--------------------

هذه الطريقة تنشئ تكبير ملخص جديد وتضع مجموعة من الكائنات فيه لجميع الأقسام في هذا العرض التقديمي.

**الإرجاع:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - الـ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

ينشئ إطار تكبير ملخص جديد ويدخله في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> هذا المثال يوضح إنشاء وإدراج كائن Summary Zoom في الفهرس المحدد لمجموعة
>  (افترض أنه يوجد على الأقل قسمان في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار التكبير الملخص فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |

--------------------

هذه الطريقة تنشئ إطار تكبير ملخص يجمع روابط ملخص لجميع الأقسام في العرض التقديمي.

**الإرجاع:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - الـ [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يظهر المثال التالي كيفية إضافة إطارات كائن OLE إلى شرائح عرض PowerPoint.
>  
>  // ينشئ كائن من فئة Presentation التي تمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // الوصول إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // تحميل ملف cel إلى تدفق
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
>      // إنشاء كائن بيانات للتضمين
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // إضافة شكل إطار كائن Ole
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // كتابة ملف PPTX إلى القرص
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات حول بيانات OLE المدمجة ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**الإرجاع:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الـ [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط.

هذا المسار يُخزن كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فإن الملف سيصبح غير قابل للوصول عند فتح العرض من دليل مختلف. |

**الإرجاع:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الـ [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> هذا المثال يوضح إدراج كائن OLE في الفهرس الثاني:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار OLE فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات البيانات المدمجة لـ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**الإرجاع:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الـ [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار OLE فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط.

هذا المسار يُخزن كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فإن الملف سيصبح غير قابل للوصول عند فتح العرض من دليل مختلف. |

**الإرجاع:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - إطار OLE الذي تم إنشاؤه حديثًا.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو المراد تضمينه. |

**الإرجاع:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| video | [IVideo](../../com.aspose.slides/ivideo) | الـ [IVideo](../../com.aspose.slides/ivideo) لتضمينه في إطار الفيديو. |

**الإرجاع:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار الفيديو فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو المراد تضمينه. |

**الإرجاع:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار الصوت فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي للربط به. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار الصوت فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي للربط به. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يُضاف الصوت المدمج إلى مجموعة Presentation.Audios.

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

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مدمج ويدخله في مجموعة الأشكال في الفهرس المحدد. يُضاف الصوت المدمج إلى مجموعة Presentation.Audios.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار الصوت فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مثال [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويدخله في مجموعة الأشكال في الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي سيتم إدخال إطار الصوت فيه. |
| x | float | إحداثي x للإطار الجديد، بالنقاط. |
| y | float | إحداثي y للإطار الجديد، بالنقاط. |
| width | float | عرض الإطار الجديد، بالنقاط. |
| height | float | ارتفاع الإطار الجديد، بالنقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مثال [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios لتضمينه. |

**الإرجاع:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

يرجع الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل المراد تحديد موقعه في المجموعة. |

**الإرجاع:**  
int - الفهرس الصفري للظهور الأول للشكل في مجموعة الأشكال إذا وُجد؛ وإلا، \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال.

**الإرجاع:**  
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول شكل للرجوع إليه. |
| count | int | عدد الأشكال للرجوع إليها. |

**الإرجاع:**  
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري المستهدف حيث سيُوضع الشكل. |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُنقل داخل المجموعة. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

ينقل الأشكال المحددة داخل مجموعة الأشكال، بوضعها بدءًا من الفهرس المعطى.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري المستهدف حيث سيُوضع أول شكل محدد؛ تتبع الأشكال اللاحقة الترتيب المحدد. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | أحد أو أكثر من مثال [IShape](../../com.aspose.slides/ishape) للانتقال داخل المجموعة. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) لل形自动形要添加的. |
| x | float | إحداثي x لإطار الشكل، بالنقاط. |
| y | float | إحداثي y لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**الإرجاع:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - الـ [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) لل形自动形要添加的. |
| x | float | إحداثي x لإطار الشكل، بالنقاط. |
| y | float | إحداثي y لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق تنسيق قالب افتراضي (نمط بسيط، نص مركزي، واسم غير فارغ) على الشكل الجديد؛ false لإنشاء الشكل بجميع الخصائص الافتراضية. |

**الإرجاع:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - الـ [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

ينشئ شكلًا مستطيلًا تلقائيًا لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة معادلة رياضية في عرض PowerPoint.
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


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار الشكل، بالنقاط. |
| y | float | إحداثي y لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**الإرجاع:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - الـ [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الشكل الجديد. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) لل形自动形要插入的. |
| x | float | إحداثي x لإطار الشكل، بالنقاط. |
| y | float | إحداثي y لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**الإرجاع:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - الـ [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بتنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الشكل التلقائي. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) لل形自动形要插入的. |
| x | float | إحداثي x لإطار الشكل، بالنقاط. |
| y | float | إحداثي y لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق تنسيق قالب افتراضي (يتضمن اسم غير فارغ، نمط بسيط، نص مركزي)؛ false لإنشاء الشكل بجميع الخصائص الافتراضية. |

**الإرجاع:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - الـ [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا لتناسب أي أشكال تُضاف إليها.

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

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - الـ [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | الـ [ISvgImage](../../com.aspose.slides/isvgimage) الذي يحتوي على محتوى متجهي للتحويل إلى أشكال. |
| x | float | إحداثي x لإطار المجموعة، بالنقاط. |
| y | float | إحداثي y لإطار المجموعة، بالنقاط. |
| width | float | عرض إطار المجموعة، بالنقاط. |
| height | float | ارتفاع إطار المجموعة، بالنقاط. |

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - الـ [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

ينشئ مجموعة أشكال فارغة جديدة ويدخلها إلى مجموعة الأشكال في الفهرس المحدد. سيتكيف إطار المجموعة تلقائيًا لتناسب أي أشكال تُضاف إليها.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال مجموعة الأشكال. |

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - الـ [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد بتنسيق قالب افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل الذي سيُضاف. |
| x | float | إحداثي x لإطار الموصل، بالنقاط. |
| y | float | إحداثي y لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**الإرجاع:**  
[IConnector](../../com.aspose.slides/iconnector) - الـ [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل الذي سيُنشأ. |
| x | float | إحداثي x لإطار الموصل، بالنقاط. |
| y | float | إحداثي y لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق تنسيق قالب افتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بالقيم الافتراضية. |

**الإرجاع:**  
[IConnector](../../com.aspose.slides/iconnector) - الـ [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مطبقًا تنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الموصل. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل الذي سيُدخل. |
| x | float | إحداثي x لإطار الموصل، بالنقاط. |
| y | float | إحداثي y لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**الإرجاع:**  
[IConnector](../../com.aspose.slides/iconnector) - الـ [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق تنسيق قالب افتراضي.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الموصل. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل الذي سيُدخل. |
| x | float | إحداثي x لإطار الموصل، بالنقاط. |
| y | float | إحداثي y لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق تنسيق قالب افتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بالقيم الافتراضية. |

**الإرجاع:**  
[IConnector](../../com.aspose.slides/iconnector) - الـ [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | يحدد نوع الشكل المحتوي في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع الأنواع من الخطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | إحداثي x لإطار الصورة، بالنقاط. |
| y | float | إحداثي y لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) الذي سيُعرض في إطار الصورة. |

**الإرجاع:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - الـ [IPictureFrame](../../com.aspose.slides/ipictureframe) الذي تم إنشاؤه حديثًا.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال إطار الصورة. |
| shapeType | int | يحدد نوع الشكل المحتوي في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع الأنواع من الخطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | إحداثي x لإطار الصورة، بالنقاط. |
| y | float | إحداثي y لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) الذي سيُعرض في إطار الصورة. |

**الإرجاع:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - الـ [IPictureFrame](../../com.aspose.slides/ipictureframe) الذي تم إنشاؤه حديثًا.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents PPTX file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define columns with widths and rows with heights
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Add table shape to slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Set border format for each cell
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
>      // Merge cells 1 & 2 of row 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Add text to the merged cell
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Save PPTX to Disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للجدول، بالنقاط. |
| y | float | إحداثي y للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة تمثل أعرض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة تمثل ارتفاعات صفوف الجدول، بالنقاط. |

**الإرجاع:**  
[ITable](../../com.aspose.slides/itable) - الـ [ITable](../../com.aspose.slides/itable) الذي تم إنشاؤه حديثًا.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الجدول. |
| x | float | إحداثي x للجدول، بالنقاط. |
| y | float | إحداثي y للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة تمثل أعرض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة تمثل ارتفاعات صفوف الجدول، بالنقاط. |

**الإرجاع:**  
[ITable](../../com.aspose.slides/itable) - الـ [ITable](../../com.aspose.slides/itable) الذي تم إنشاؤه حديثًا.

### removeAt(int index) {#removeAt-int-}
```
public    



```

يزيل الشكل في الفهرس المحدد من مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للشكل الذي سيُزال. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

يزيل أول ظهور للشكل المحدد من مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُزال. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الأشكال من مجموعة الأشكال.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

يرجع مكررًا يتنقل عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

يرجع مكررًا جافا للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator للمجموعة بأكملها.

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

يحصل على كائن مجموعة الأشكال الأم لمجموعة الأشكال. قراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي سيُستنسخ. |
| x | float | إحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | float | إحداثي y لإطار الشكل الجديد، بالنقاط. |
| width | float | عرض إطار الشكل الجديد، بالنقاط. |
| height | float | ارتفاع إطار الشكل الجديد، بالنقاط. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع الـ sourceShape.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي سيُستنسخ. |
| x | float | إحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | float | إحداثي y لإطار الشكل الجديد، بالنقاط. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. تحتفظ النسخة بموقع وحجم الأصل.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُستنسخ. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقاط. |
| width | float | عرض إطار الشكل المستنسخ، بالنقاط. |
| height | float | ارتفاع إطار الشكل المستنسخ، بالنقاط. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع الـ sourceShape.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقاط. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد. تحتفظ النسخة بموقع وحجم الأصل.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري حيث سيتم إدخال الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي سيُستنسخ. |

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس البدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). قراءة فقط  boolean .

**الإرجاع:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. قراءة فقط  Object .

**الإرجاع:**  
java.lang.Object