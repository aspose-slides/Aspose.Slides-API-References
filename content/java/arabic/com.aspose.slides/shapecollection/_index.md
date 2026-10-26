---
title: ShapeCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار Zoom جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار Zoom جديد بصورة محددة مسبقًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار Section Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار Section Zoom جديد بصورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار Section Zoom جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار Section Zoom جديد بصورة محددة مسبقًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | ينشئ إطار Summary Zoom جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | يرجع الفهرس الصفري لأول حدوث للشكل المحدد في المجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | ينقل الأشكال المحددة داخل مجموعة الأشكال، ويضعها بدءًا من الفهرس المحدد. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | ينشئ شكلًا تلقائيًا مستطيلاً جديدًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تهيئته بنمط القالب الافتراضي. |
| [addGroupShape()](#addGroupShape--) | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | ينشئ مجموعة أشكال فارغة جديدة ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | ينشئ شكل موصل جديد بنمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | ينشئ شكل موصل جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق نمط القالب الافتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | ينشئ جدولًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل الشكل عند الفهرس المحدد من مجموعة الأشكال. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | يزيل أول حدوث للشكل المحدد من مجموعة الأشكال. |
| [clear()](#clear--) | يزيل جميع الأشكال من مجموعة الأشكال. |
| [iterator()](#iterator--) | يرجع مُكرِّرًا يعبر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرر Java للمجموعة بأكملها. |
| [getParentGroup()](#getParentGroup--) | يحصل على كائن مجموعة الشكل الأب لمجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويُدخله في مجموعة الأشكال عند الفهرس المحدد. |
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

يحصل على العنصر عند الفهرس المحدد. قراءة فقط [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // ينشئ كائن من فئة Presentation التي تمثل ملف PPTX
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
>      // يضبط السلسلة الأولى لإظهار القيم
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // يحدد الفهرس لورقة بيانات المخطط
>      int defaultWorksheetIndex = 0;
>      // يحصل على ورقة عمل بيانات المخطط
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // يحذف السلسلة والفئات المولدة افتراضيًا
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
>      // يملء بيانات السلسلة
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // يضبط لون التعبئة للسلسلة
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // يأخذ السلسلة الثانية للمخطط
>      series = chart.getChartData().getSeries().get_Item(1);
>      // يملء بيانات السلسلة
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // يضبط لون التعبئة للسلسلة
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // يضبط التسمية الأولى لإظهار اسم الفئة
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // يضبط السلسلة لإظهار القيمة للتسمية الثالثة
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // يحفظ ملف PPTX على القرص
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط لإضافته. |
| x | float | الإحداثي X للمخطط الجديد، بنقاط. |
| y | float | الإحداثي Y للمخطط الجديد، بنقاط. |
| width | float | عرض المخطط، بنقاط. |
| height | float | ارتفاع المخطط، بنقاط. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - العنصر المنشأ حديثًا [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط لإضافته. |
| x | float | الإحداثي X للمخطط الجديد، بنقاط. |
| y | float | الإحداثي Y للمخطط الجديد، بنقاط. |
| width | float | عرض المخطط، بنقاط. |
| height | float | ارتفاع المخطط، بنقاط. |
| initWithSample | boolean | True لتهيئة المخطط الجديد ببيانات سلسلة عينة وإعدادات؛ false لإنشاء المخطط بدون سلاسل ومع إعدادات قليلة فقط، مما يجعل الإنشاء أسرع. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - العنصر المنشأ حديثًا [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يعرض المثال التالي كيفية إضافة شكل ذكي في عرض تقديمي لبرنامج PowerPoint.
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي X لإطار المخطط، بنقاط. |
| y | float | الإحداثي Y لإطار المخطط، بنقاط. |
| width | float | عرض إطار المخطط، بنقاط. |
| height | float | ارتفاع إطار المخطط، بنقاط. |
| layoutType | int | نوع تخطيط SmartArt. |

**الإرجاع:**
[ISmartArt](../../com.aspose.slides/ismartart) - العنصر المنشأ حديثًا [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط لإنشائه. |
| x | float | الإحداثي X للمخطط الجديد، بنقاط. |
| y | float | الإحداثي Y للمخطط الجديد، بنقاط. |
| width | float | عرض المخطط الجديد، بنقاط. |
| height | float | ارتفاع المخطط الجديد، بنقاط. |
| index | int | الفهرس الصفري الذي يُدرج فيه المخطط الجديد داخل مجموعة الأشكال. |

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart) - العنصر المنشأ حديثًا [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يتهيئه ببيانات سلسلة عينة وإعدادات، ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط لإنشائه. |

| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري الذي يتم عنده إدراج المخطط الجديد في مجموعة الأشكال. |
| initWithSample | boolean | True لتهيئة المخطط الجديد ببيانات وإعدادات عينة السلسلة؛ false لإنشاء المخطط دون سلاسل ومع إعدادات حد أدنى فقط، مما يجعل الإنشاء أسرع. |

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض الإطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع الإطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) المشار إليه بإطار Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض الإطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع الإطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) المشار إليه بإطار Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للشرائح [IPPImage](../../com.aspose.slides/ippimage) المشار إليها. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوّضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة
>  (يفترض وجود شريحتين على الأقل في عرض تقديمي "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom. |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض الإطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع الإطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) المشار إليه بإطار Zoom. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديدًا بصورة محددة مسبقًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة
>  (يفترض وجود شريحتين على الأقل في عرض تقديمي "Presentation.pptx"):
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار Zoom. |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض الإطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع الإطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) المشار إليه بإطار Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للشرائح [IPPImage](../../com.aspose.slides/ippimage) المشار إليها. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوّضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (يفترض أن هناك قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) المشار إليه بإطار Section Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديدًا بصورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض أن هناك قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) المشار إليه بإطار Section Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) لعرضه داخل إطار Section Zoom. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوّضح هذا المثال إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (افترض وجود قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار Section Zoom. |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) المشار إليه بإطار Section Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديدًا بصورة محددة مسبقًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوّضح هذا المثال إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (افترض وجود قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار Section Zoom. |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) المشار إليه بإطار Section Zoom؛ يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة لعرضها داخل إطار Section Zoom. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

ينشئ إطار Summary Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Summary Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Summary Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Summary Zoom الجديد، بالنقاط. |

--------------------

هذه الطريقة تنشئ Summary Zoom جديدًا وتضع مجموعة من الكائنات فيه لجميع الأقسام في هذا العرض التقديمي. |

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

ينشئ إطار Summary Zoom جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Summary Zoom في الفهرس المحدد لمجموعة
>  (يفترض وجود قسمين على الأقل في عرض تقديمي "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار Summary Zoom. |
| x | float | إحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | float | إحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Summary Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Summary Zoom الجديد، بالنقاط. |

--------------------

هذه الطريقة تنشئ إطار Summary Zoom يجمع روابط الملخص لجميع الأقسام في العرض التقديمي. |

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة إطارات كائن OLE إلى شرائح عرض PowerPoint.
>  
>  // إنشاء كائن من فئة Presentation التي تمثل ملف PPTX
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | المعلومات حول بيانات OLE المدمجة ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | مسار الملف المرتبط.

يتم تخزين هذا المسار حرفيًا في العرض التقديمي. إذا تم تحديد مسار نسبي، فلن يكون الملف قابلًا للوصول عند فتح العرض التقديمي من دليل مختلف. |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إدراج كائن OLE في الفهرس الثاني:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار كائن OLE. |
| x | float | الإحداثي السيني للإطار OLE الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي للإطار OLE الجديد، بوحدات النقاط. |
| width | float | عرض الإطار OLE الجديد، بوحدات النقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بوحدات النقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المضمنة ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - العنصر [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار كائن OLE. |
| x | float | الإحداثي السيني للإطار OLE الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي للإطار OLE الجديد، بوحدات النقاط. |
| width | float | عرض الإطار OLE الجديد، بوحدات النقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بوحدات النقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط. |

يتم تخزين هذا المسار كما هو في العرض. إذا تم تحديد مسار نسبي، لن يكون الملف قابلًا للوصول عند فتح العرض من دليل مختلف.

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - إطار كائن OLE الذي تم إنشاؤه حديثًا.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بوحدات النقاط. |
| width | float | عرض إطار الفيديو الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الفيديو الجديد، بوحدات النقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو لتضمينه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

ينشئ إطار فيديو جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بوحدات النقاط. |
| width | float | عرض إطار الفيديو الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الفيديو الجديد، بوحدات النقاط. |
| video | [IVideo](../../com.aspose.slides/ivideo) | الـ[IVideo](../../com.aspose.slides/ivideo) الذي يُضمن في إطار الفيديو. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار الفيديو. |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بوحدات النقاط. |
| width | float | عرض إطار الفيديو الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الفيديو الجديد، بوحدات النقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو لتضمينه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار قرص CD ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار قرص CD ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي للربط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي للربط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مضمّن ويضيفه إلى نهاية مجموعة الأشكال. يُضاف الصوت المضمّن إلى مجموعة Presentation.Audios.

--------------------

> ```
> يوضح المثال التالي كيفية إنشاء إطار صوت.
>  
>  // ينشئ كائنًا من فئة Presentation التي تمثل ملف عرض تقديمي
>  Presentation pres = new Presentation();
>  try {
>      // يحصل على الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يحمل ملف الصوت wav إلى تدفق
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // يضيف إطار الصوت
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // يضبط وضع التشغيل ومستوى الصوت
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // يكتب ملف PowerPoint إلى القرص
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مضمّن ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يُضاف الصوت المضمّن إلى مجموعة Presentation.Audios.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | كائن [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الذي يُدرج عنده إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بوحدات النقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بوحدات النقاط. |
| width | float | عرض إطار الصوت الجديد، بوحدات النقاط. |
| height | float | ارتفاع إطار الصوت الجديد، بوحدات النقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | كائن [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

يرجع الفهرس الصفري-الأساس لأول ظهور للشكل المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل للبحث عنه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس الصفري-الأساس لأول ظهور للشكل في مجموعة الأشكال إذا وُجد؛ وإلا، \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال.

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس الشكل الأول الذي يُعاد. |
| count | int | عدد الأشكال التي تُعاد. |

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الهدف حيث سيتم وضع الشكل. |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) الذي يُنقل داخل المجموعة. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري-الأساس الهدف حيث سيُوضع أول شكل محدد؛ تليه الأشكال الأخرى بالترتيب المذكور. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | واحد أو أكثر من كائنات [IShape](../../com.aspose.slides/ishape) للتحريك داخل المجموعة. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

ينشئ شكلاً تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك التلقائي المراد إضافته. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الكائن [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلاً تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك التلقائي المراد إضافته. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | True لتطبيق نمط القالب الافتراضي (نمط بسيط، نص متمركز، واسم غير فارغ) على الشكل الجديد؛ false لإنشاء الشكل بجميع الخصائص مضبوطة على قيمها الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الكائن [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

ينشئ شكلاً تلقائيًا مستطيلًا جديدًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال كيفية إضافة معادلة رياضية في عرض تقديمي لبرنامج PowerPoint.
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
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الكائن [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكلاً تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده الشكل التلقائي الجديد. |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك التلقائي المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الكائن [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلاً تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تهيئته بنمط القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده الشكل التلقائي. |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك التلقائي المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | True لتطبيق نمط القالب الافتراضي (بما في ذلك اسم غير فارغ، نمط بسيط، ونص متمركز)؛ false لإنشاء الشكل بجميع الخصائص مضبوطة على القيم الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الكائن [IAutoShape](../../com.aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيضبط إطار المجموعة تلقائيًا ليلائم أي أشكال تُضاف إليه.

--------------------

> ```
> المثال التالي يوضح كيفية إضافة شكل مجموعة إلى شريحة من عرض PowerPoint.
>  
>  // إنشاء فئة Presentation
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // الوصول إلى مجموعة الأشكال في الشرائح
>      IShapeCollection slideShapes = sld.getShapes();
>      // إضافة شكل مجموعة إلى الشريحة
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // إضافة أشكال داخل الشكل المجموعة المضاف
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // إضافة إطار شكل المجموعة
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // كتابة ملف PPTX إلى القرص
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - الكائن [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | ال[ISvgImage](../../com.aspose.slides/isvgimage) التي تحتوي على محتوى متجكتور لتحويله إلى أشكال. |
| x | float | الإحداثي السيني لإطار المجموعة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار المجموعة، بالنقاط. |
| width | float | عرض إطار المجموعة، بالنقاط. |
| height | float | ارتفاع إطار المجموعة، بالنقاط. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - الكائن [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

ينشئ مجموعة أشكال فارغة جديدة ويدخلها في مجموعة الأشكال عند الفهرس المحدد. سيضبط إطار المجموعة تلقائيًا ليلائم أي أشكال تُضاف إليه.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده مجموعة الأشكال. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - الكائن [IGroupShape](../../com.aspose.slides/igroupshape) الذي تم إنشاؤه حديثًا.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

ينشئ شكلاً موصِلًا جديدًا بنمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح المثال التالي كيفية إضافة موصل (موصل منحني) بين شكلين (إهليلج ومستطيل) في عرض PowerPoint.
>  
>  // ينشئ كائنًا من فئة Presentation التي تمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // يحصل على مجموعة الأشكال لشريحة معينة
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // يضيف الشكل التلقائي Ellipse
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // يضيف الشكل التلقائي Rectangle
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // يضيف شكل موصل إلى مجموعة أشكال الشريحة
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // يربط الأشكال باستخدام الموصل
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // يستدعي الدالة reroute التي تحدد أقصر مسار تلقائي بين الأشكال
>      connector.reroute();
>      // يحفظ العرض
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك الموصل المراد إضافته. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الكائن [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلاً موصِلًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك الموصل المراد إنشاؤه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | True لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الكائن [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكلاً موصِلًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده شك الموصل. |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك الموصل المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الكائن [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلاً موصِلًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده شك الموصل. |
| shapeType | int | قيمة [ShapeType](../../com.aspose.slides/shapetype) للشك الموصل المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | True لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الكائن [IConnector](../../com.aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | يحدد نوع الشكل الموجود في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ال[IPPImage](../../com.aspose.slides/ippimage) لعرضه في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - الكائن [IPictureFrame](../../com.aspose.slides/ipictureframe) الذي تم إنشاؤه حديثًا.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويدخله في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدخل عنده إطار الصورة. |
| shapeType | int | يحدد نوع الشكل الموجود في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | ال[IPPImage](../../com.aspose.slides/ippimage) لعرضه في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - الكائن [IPictureFrame](../../com.aspose.slides/ipictureframe) الذي تم إنشاؤه حديثًا.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> المثال التالي يُظهر كيفية إضافة جدول في عرض تقديمي لبرنامج PowerPoint.
>  
  
>  // إنشاء كائن من فئة Presentation التي تمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // الوصول إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // تحديد الأعمدة بأعرضها والصفوف بأارتفاعاتها
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // إضافة شكل جدول إلى الشريحة
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // ضبط تنسيق الحدود لكل خلية
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
>      // دمج الخلايا 1 و 2 من الصف 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // إضافة نص إلى الخلية المدمجة
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // حفظ ملف PPTX إلى القرص
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي x للجدول، بالنقاط. |
| y | float | الإحداثي y للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة من القيم المزدوجة تمثل عرض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بالنقاط. |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الـ[ITable](../../com.aspose.slides/itable) المُنشأ حديثًا.
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدرج عنده الجدول. |
| x | float | الإحداثي x للجدول، بالنقاط. |
| y | float | الإحداثي y للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة من القيم المزدوجة تمثل عرض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بالنقاط. |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الـ[ITable](../../com.aspose.slides/itable) المُنشأ حديثًا.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل الشكل عند الفهرس المحدد من مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للشكل الذي تريد إزالته. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

يزيل أول ظهور للشكل المحدد من مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لإزالته. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الأشكال من مجموعة الأشكال.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - عداد IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

يرجع مكرِّر Java للمجموعة كاملة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator للمجموعة كاملة.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

يحصل على كائن مجموعة الأشكال الأصلية لمجموعة الأشكال. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**الإرجاع:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل لاستنساخه. |
| x | float | الإحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار الشكل الجديد، بالنقاط. |
| width | float | عرض إطار الشكل الجديد، بالنقاط. |
| height | float | ارتفاع إطار الشكل الجديد، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع sourceShape.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل لاستنساخه. |
| x | float | الإحداثي x لإطار الشكل الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار الشكل الجديد، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل المستنسخ بموضعه وحجمه الأصلي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لاستنساخه. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويدرجها في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدرج عنده الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لاستنساخه. |
| x | float | الإحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | float | الإحداثي y لإطار الشكل المستنسخ، بالنقاط. |
| width | float | عرض إطار الشكل المستنسخ، بالنقاط. |
| height | float | ارتفاع إطار الشكل المستنسخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويدرجها في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع sourceShape.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدرج عنده الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لاستنساخه. |
| x | float | الإحداثي x لإطار الشكل المستنسخ، بالنقاط. |
| y | float | الإحداثي y لإطار الشكل المستنسخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد וيدرجها في مجموعة الأشكال عند الفهرس المحدد. يحتفظ الشكل المستنسخ بموضعه وحجمه الأصلي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يُدرج عنده الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لاستنساخه. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ[IShape](../../com.aspose.slides/ishape) المُنشأ حديثًا.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للثريد). للقراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. للقراءة فقط Object.

**الإرجاع:**
java.lang.Object