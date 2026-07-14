---
title: IShapeCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأشكال.
type: docs
url: /ar/com.aspose.slides/ishapecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

يمثل مجموعة من الأشكال.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getParentGroup()](#getParentGroup--) | يحصل على كائن مجموعة الشكل الأب لمجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار Zoom جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار Section Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار Section Zoom جديد بصورة معرفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار Section Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار Section Zoom جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | ينشئ إطار Summary Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار CD ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد بملف WAV مدمج ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | يعيد الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المعطى. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | ينشئ شكلًا تلقائيًا مستطيلًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [addGroupShape()](#addGroupShape--) | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | ينشئ مجموعة أشكال فارغة جديدة ويُدرجها في مجموعة الأشكال في الفهرس المحدد. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | ينشئ شكل موصل جديد بتنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع تطبيق تنسيق القالب الافتراضي اختياريًا. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق تنسيق القالب الافتراضي. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل الشكل في الفهرس المحدد من مجموعة الأشكال. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | يزيل الظهور الأول للشكل المحدد من مجموعة الأشكال. |
| [clear()](#clear--) | يزيل جميع الأشكال من مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويُدرجها في مجموعة الأشكال في الفهرس المحدد. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

يحصل على كائن مجموعة الشكل الأب لمجموعة الأشكال. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إضافته. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart) - العنصر [IChart](../../com.aspose.slides/ichart) الجديد.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إضافته. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |
| initWithSample | boolean | true لتهيئة المخطط الجديد ببيانات سلسلة تجريبية وإعدادات؛ false لإنشاء مخطط بدون سلاسل وإعدادات قليلة لتسريع الإنشاء. |

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart) - العنصر [IChart](../../com.aspose.slides/ichart) الجديد.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار المخطط، بالنقاط. |
| y | float | إحداثي y لإطار المخطط، بالنقاط. |
| width | float | عرض الإطار، بالنقاط. |
| height | float | ارتفاع الإطار، بالنقاط. |
| layoutType | int | نوع تخطيط SmartArt. |

**القيمة المرجعة:**
[ISmartArt](../../com.aspose.slides/ismartart) - العنصر [ISmartArt](../../com.aspose.slides/ismartart) الجديد.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إنشائه. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه المخطط الجديد في مجموعة الأشكال. |

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart) - العنصر [IChart](../../com.aspose.slides/ichart) الجديد.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

ينشئ مخططًا جديدًا، يهيئه ببيانات سلسلة تجريبية وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | نوع المخطط المراد إنشائه. |
| x | float | إحداثي x للمخطط الجديد، بالنقاط. |
| y | float | إحداثي y للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه المخطط الجديد في مجموعة الأشكال. |
| initWithSample | boolean | true لتهيئة المخطط الجديد ببيانات سلسلة تجريبية وإعدادات؛ false لإنشاء مخطط بدون سلاسل وإعدادات قليلة لتسريع الإنشاء. |

**القيمة المرجعة:**
[IChart](../../com.aspose.slides/ichart) - العنصر [IChart](../../com.aspose.slides/ichart) الجديد.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y للإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات البيانات المدمجة لـ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - العنصر [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الجديد.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y للإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة للكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط.

يُحفظ هذا المسار حرفيًا في العرض التقديمي. إذا تم تحديد مسار نسبي، سيكون الملف غير قابل للوصول عند فتح العرض من دليل مختلف. |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - العنصر [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الجديد.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار OLE. |
| x | float | إحداثي x للإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y للإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات البيانات المدمجة لـ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - العنصر [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الجديد.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار OLE. |
| x | float | إحداثي x للإطار OLE الجديد، بالنقاط. |
| y | float | إحداثي y للإطار OLE الجديد، بالنقاط. |
| width | float | عرض الإطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع الإطار OLE الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة للكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط.

يُحفظ هذا المسار حرفيًا في العرض التقديمي. إذا تم تحديد مسار نسبي، سيكون الملف غير قابل للوصول عند فتح العرض من دليل مختلف. |

**القيمة المرجعة:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - العنصر [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الجديد.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة
>  (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - العنصر [IZoomFrame](../../com.aspose.slides/izoomframe) الجديد.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة
>  (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
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


**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - العنصر [IZoomFrame](../../com.aspose.slides/izoomframe) الجديد.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom عند الفهرس المحدد في مجموعة
>  (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار Zoom. |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - العنصر [IZoomFrame](../../com.aspose.slides/izoomframe) الجديد.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom عند الفهرس المحدد في مجموعة
>  (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار Zoom. |
| x | float | إحداثي x لإطار Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه. |

**القيمة المرجعة:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - العنصر [IZoomFrame](../../com.aspose.slides/izoomframe) الجديد.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - العنصر [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الجديد.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديد بصورة معرفة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) لعرضه داخل إطار Section Zoom. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - العنصر [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الجديد.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Section Zoom عند الفهرس المحدد في مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار Section Zoom. |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - العنصر [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الجديد.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديد بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Section Zoom عند الفهرس المحدد في مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار Section Zoom. |
| x | float | إحداثي x لإطار Section Zoom الجديد، بالنقط. |
| y | float | إحداثي y لإطار Section Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للعرض داخل إطار Section Zoom. |

**القيمة المرجعة:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - العنصر [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الجديد.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Summary Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار Summary Zoom الجديد، بالنقط. |
| y | float | إحداثي y للإطار Summary Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

--------------------

هذه الطريقة تنشئ إطار Summary Zoom يجمع روابط ملخص لجميع الأقسام في العرض. 

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - العنصر [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الجديد.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

ينشئ إطار Summary Zoom جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Summary Zoom عند الفهرس المحدد في مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار Summary Zoom. |
| x | float | إحداثي x للإطار Summary Zoom الجديد، بالنقط. |
| y | float | إحداثي y للإطار Summary Zoom الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

--------------------

هذه الطريقة تنشئ إطار Summary Zoom يجمع روابط ملخص لجميع الأقسام في العرض. 

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - العنصر [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الجديد.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الفيديو الجديد، بالنقط. |
| y | float | إحداثي y للإطار الفيديو الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| fname | java.lang.String | مسار أو اسم ملف الفيديو الذي سيتم دمجه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - العنصر [IVideoFrame](../../com.aspose.slides/ivideoframe) الجديد.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الفيديو الجديد، بالنقط. |
| y | float | إحداثي y للإطار الفيديو الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| video | [IVideo](../../com.aspose.slides/ivideo) | الـ [IVideo](../../com.aspose.slides/ivideo) لدمجه في إطار الفيديو. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - العنصر [IVideoFrame](../../com.aspose.slides/ivideoframe) الجديد.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار الفيديو. |
| x | float | إحداثي x للإطار الفيديو الجديد، بالنقط. |
| y | float | إحداثي y للإطار الفيديو الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| fname | java.lang.String | مسار أو اسم ملف الفيديو الذي سيتم دمجه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - العنصر [IVideoFrame](../../com.aspose.slides/ivideoframe) الجديد.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الإطار الصوتي. |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| fname | java.lang.String | مسار أو اسم الملف الصوتي الخارجي للربط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الإطار الصوتي. |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| fname | java.lang.String | مسار أو اسم الملف الصوتي الخارجي للربط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مدمج ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV للدمج. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | كائن [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد بملف WAV مدمج ويُدرجه في مجموعة الأشكال في الفهرس المحدد. يتم إضافة الصوت المدمج إلى مجموعة Presentation.Audios.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الإطار الصوتي. |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV للدمج. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الإطار الصوتي. |
| x | float | إحداثي x للإطار الصوتي الجديد، بالنقط. |
| y | float | إحداثي y للإطار الصوتي الجديد، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | كائن [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios للدمج. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - العنصر [IAudioFrame](../../com.aspose.slides/iaudioframe) الجديد.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

يعيد الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي يُبحث عنه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس الصفري للظهور الأول للشكل في مجموعة الأشكال إذا وجد؛ وإلا \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال.

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول شكل يُرجع. |
| count | int | عدد الأشكال التي يُرجع. |

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموضع الهدف حيث سيوضع الشكل. |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُنقل داخل المجموعة. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المعطى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموضع الهدف حيث يُوضع أول شكل محدد؛ تتبع الأشكال اللاحقة بالترتيب المقدم. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | واحدة أو أكثر من مثيلات [IShape](../../com.aspose.slides/ishape) للتحريك داخل المجموعة. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للشكل التلقائي المراد إضافته. |
| x | float | إحداثي x لإطار الشكل، بالنقط. |
| y | float | إحداثي y لإطار الشكل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - العنصر [IAutoShape](../../com.aspose.slides/iautoshape) الجديد.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للشكل التلقائي المراد إضافته. |
| x | float | إحداثي x لإطار الشكل، بالنقط. |
| y | float | إحداثي y لإطار الشكل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| createFromTemplate | boolean | true لتطبيق تنسيق القالب الافتراضي (نمط بسيط، نص مركزي، واسم غير فارغ) على الشكل الجديد؛ false لإنشاء الشكل مع جميع الخصائص بالقيم الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - العنصر [IAutoShape](../../com.aspose.slides/iautoshape) الجديد.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا مستطيلًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x لإطار الشكل، بالنقط. |
| y | float | إحداثي y لإطار الشكل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - العنصر [IAutoShape](../../com.aspose.slides/iautoshape) الجديد.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الشكل التلقائي الجديد. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للشكل التلقائي المراد إدراجه. |
| x | float | إحداثي x لإطار الشكل، بالنقط. |
| y | float | إحداثي y لإطار الشكل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - العنصر [IAutoShape](../../com.aspose.slides/iautoshape) الجديد.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا تلقائيًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بتنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الشكل التلقائي. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للشكل التلقائي المراد إدراجه. |
| x | float | إحداثي x لإطار الشكل، بالنقط. |
| y | float | إحداثي y لإطار الشكل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| createFromTemplate | boolean | true لتطبيق تنسيق القالب الافتراضي (باسم غير فارغ، نمط بسيط، نص مركزي)؛ false لإنشاء الشكل بجميع الخصائص بالقيم الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - العنصر [IAutoShape](../../com.aspose.slides/iautoshape) الجديد.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيتكيف إطار المجموعة تلقائيًا لاحتواء أي أشكال تُضاف إليها.

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - العنصر [IGroupShape](../../com.aspose.slides/igroupshape) الجديد.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

ينشئ مجموعة أشكال جديدة، يحول صورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | الـ [ISvgImage](../../com.aspose.slides/isvgimage) الذي يحتوي على محتوى متجه للتحويل إلى أشكال. |
| x | float | إحداثي x لإطار المجموعة، بالنقط. |
| y | float | إحداثي y لإطار المجموعة، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - العنصر [IGroupShape](../../com.aspose.slides/igroupshape) الجديد.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

ينشئ مجموعة أشكال فارغة جديدة ويُدرجها في مجموعة الأشكال في الفهرس المحدد. سيتكيف إطار المجموعة تلقائيًا لاحتواء أي أشكال تُضاف إليها.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه مجموعة الأشكال. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - العنصر [IGroupShape](../../com.aspose.slides/igroupshape) الجديد.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد بتنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إضافته. |
| x | float | إحداثي x لإطار الموصل، بالنقط. |
| y | float | إحداثي y لإطار الموصل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - العنصر [IConnector](../../com.aspose.slides/iconnector) الجديد.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إنشائه. |
| x | float | إحداثي x لإطار الموصل، بالنقط. |
| y | float | إحداثي y لإطار الموصل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| createFromTemplate | boolean | true لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء موصل بالخصائص الافتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - العنصر [IConnector](../../com.aspose.slides/iconnector) الجديد.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الموصل. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إدراجه. |
| x | float | إحداثي x لإطار الموصل، بالنقط. |
| y | float | إحداثي y لإطار الموصل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - العنصر [IConnector](../../com.aspose.slides/iconnector) الجديد.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويُدرجه في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق تنسيق القالب الافتراضي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الموصل. |
| shapeType | int | الـ [ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إدراجه. |
| x | float | إحداثي x لإطار الموصل، بالنقط. |
| y | float | إحداثي y لإطار الموصل، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| createFromTemplate | boolean | true لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بالخصائص الإفتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - العنصر [IConnector](../../com.aspose.slides/iconnector) الجديد.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
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
| x | float | إحداثي x للإطار، بالنقط. |
| y | float | إحداثي y للإطار، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) الذي يُعرض في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - العنصر [IPictureFrame](../../com.aspose.slides/ipictureframe) الجديد.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه إطار الصورة. |
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
| x | float | إحداثي x للإطار، بالنقط. |
| y | float | إحداثي y للإطار، بالنقط. |
| width | float | عرض الإطار، بالنقط. |
| height | float | ارتفاع الإطار، بالنقط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) الذي يُعرض في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - العنصر [IPictureFrame](../../com.aspose.slides/ipictureframe) الجديد.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | إحداثي x للجدول، بالنقط. |
| y | float | إحداثي y للجدول، بالنقط. |
| columnWidths | double[] | مصفوفة تمثل عرض أعمدة الجدول، بالنقط. |
| rowHeights | double[] | مصفوفة تمثل ارتفاع صفوف الجدول، بالنقط. |

**القيمة المرجعة:**
[ITable](../../com.aspose.slides/itable) - العنصر [ITable](../../com.aspose.slides/itable) الجديد.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الجدول. |
| x | float | إحداثي x للجدول، بالنقط. |
| y | float | إحداثي y للجدول، بالنقط. |
| columnWidths | double[] | مصفوفة تمثل عرض أعمدة الجدول، بالنقط. |
| rowHeights | double[] | مصفوفة تمثل ارتفاع صفوف الجدול، بالنقط. |

**القيمة المرجعة:**
[ITable](../../com.aspose.slides/itable) - العنصر [ITable](../../com.aspose.slides/itable) الجديد.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل الشكل في الفهرس المحدد من مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للشكل الذي يُزيل. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

يزيل الظهور الأول للشكل المحدد من مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُزيل. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الأشكال من مجموعة الأشكال.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي يُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقط. |
| width | float | عرض إطار الشكل المستنسخ، بالنقط. |
| height | float | ارتفاع إطار الشكل المستنسخ، بالنقط. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل الجديد بعرض وارتفاع الـ sourceShape.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقط. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. يحتفظ الشكل المستنسخ بموقعه وحجمه الأصلي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقط. |
| width | float | عرض إطار الشكل المستنسخ، بالنقط. |
| height | float | ارتفاع إطار الشكل المستنسخ، بالنقط. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل الجديد بعرض وارتفاع الـ sourceShape.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي x لإطار الشكل المستنسخ، بالنقط. |
| y | float | إحداثي y لإطار الشكل المستنسخ، بالنقط. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويُدرجه في مجموعة الأشكال في الفهرس المحدد. يحتفظ الشكل المستنسخ بموقعه وحجمه الأصلي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للموقع الذي يُدرج فيه الشكل المستنسخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |

**القيمة المرجعة:**
[IShape](../../com.aspose.slides/ishape) - العنصر [IShape](../../com.aspose.slides/ishape) الجديد.