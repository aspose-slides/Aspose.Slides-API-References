---
title: IShapeCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من الأشكال.
type: docs
url: /ar/com.aspose.slides/ishapecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

يمثِّل مجموعة من الأشكال.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getParentGroup()](#getParentGroup--) | يحصل على كائن مجموعة الشكل الأصل لمجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | ينشئ مخطط SmartArt ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | ينشئ إطار كائن OLE جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | ينشئ إطار تكبير جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير جديد بصورة مسبقة ويضيفه إلى مجموعة الأشكال في الفهرس المحدد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار تكبير قسم جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير قسم جديد بصورة مسبقة ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | ينشئ إطار تكبير قسم جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | ينشئ إطار تكبير قسم جديد بصورة مسبقة ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | ينشئ إطار تكبير ملخص جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | ينشئ إطار تكبير ملخص جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | ينشئ إطار فيديو جديد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار قرص CD ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | ينشئ إطار صوت جديد مرتبط بمسار قرص CD ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد مع ملف WAV مضمّن ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | ينشئ إطار صوت جديد مع ملف WAV مضمّن ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | ينشئ إطار صوت جديد ويدخله في مجموعة الأشكال في الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | يُرجِع الفهرس الصفري للظهور الأول للشكل المحدد في المجموعة. |
| [toArray()](#toArray--) | ينشئ ويُرجِع مصفوفة تحتوي على جميع الأشكال. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويُرجِع مصفوفة تحتوي على جميع الأشكال في النطاق المحدد. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | ينقل الشكل المحدد إلى موقع جديد داخل مجموعة الأشكال. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعًا إياها بدءًا من الفهرس المحدد. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا بالتنسيق الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | ينشئ شكلًا تلقائيًا مستطيلًا لاستضافة محتوى رياضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تهيئته بتنسيق القالب الافتراضي. |
| [addGroupShape()](#addGroupShape--) | ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | ينشئ مجموعة أشكال جديدة، يحول الصورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | ينشئ مجموعة أشكال فارغة جديدة ويدخلها إلى مجموعة الأشكال في الفهرس المحدد. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | ينشئ شكل موصل جديد بتنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق القالب الافتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | ينشئ شكل موصل جديد ويدخله في مجموعة الأشكال في الفهرس المحدد، مع إمكانية تطبيق تنسيق القالب الافتراضي. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | ينشئ جدولًا جديدًا ويدخله إلى مجموعة الأشكال في الفهرس المحدد. |
| [removeAt(int index)](#removeAt-int-) | يزيل الشكل في الفهرس المحدد من مجموعة الأشكال. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | يزيل الظهور الأول للشكل المحدد من مجموعة الأشكال. |
| [clear()](#clear--) | يزيل جميع الأشكال من مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | ينشئ نسخة من الشكل المحدد ويدخله في مجموعة الأشكال في الفهرس المحدد. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```


يحصل على كائن مجموعة الشكل الأصل لمجموعة الأشكال. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**Returns:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```


ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع المخطط الذي سيتم إضافته. |
| x | float | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | float | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```


ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويضيفه إلى نهاية مجموعة الأشكال.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع المخطط الذي سيتم إضافته. |
| x | float | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | float | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط، بالنقاط. |
| height | float | ارتفاع المخطط، بالنقاط. |
| initWithSample | boolean | true لتهيئة المخطط الجديد ببيانات عينة وإعدادات؛ false لإنشاء المخطط بدون سلاسل وإعدادات بسيطة، مما يجعل الإنشاء أسرع. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.
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


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار المخطط، بالنقاط. |
| y | float | الإحداثي الصادي لإطار المخطط، بالنقاط. |
| width | float | عرض إطار المخطط، بالنقاط. |
| height | float | ارتفاع إطار المخطط، بالنقاط. |
| layoutType | int | نوع تخطيط SmartArt. |

**Returns:**
[ISmartArt](../../com.aspose.slides/ismartart) - الـ [ISmartArt](../../com.aspose.slides/ismartart) الذي تم إنشاؤه حديثًا.
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```


ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويدخله إلى مجموعة الأشكال في الفهرس المحدد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع المخطط الذي سيتم إنشاؤه. |
| x | float | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | float | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري الذي سيتم إدراج المخطط الجديد فيه داخل مجموعة الأشكال. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - الـ [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```


ينشئ مخططًا جديدًا، يهيئه ببيانات عينة وإعدادات، ويدخله إلى مجموعة الأشكال في الفهرس المحدد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع المخطط الذي سيتم إنشاؤه. |
| x | float | الإحداثي السيني للمخطط الجديد، بالنقاط. |
| y | float | الإحداثي الصادي للمخطط الجديد، بالنقاط. |
| width | float | عرض المخطط الجديد، بالنقاط. |
| height | float | ارتفاع المخطط الجديد، بالنقاط. |
| index | int | الفهرس الصفري الذي سيتم إدراج المخطط الجديد فيه داخل مجموعة الأشكال. |
| initWithSample | boolean | True لتهيئة المخطط الجديد ببيانات وإعدادات السلاسل النموذجية؛ false لإنشاء المخطط بدون سلاسل وبإعدادات حد أدنى فقط، مما يجعل الإنشاء أسرع. |

**القيمة المرجعة:**  
[IChart](../../com.aspose.slides/ichart) - الكائن [IChart](../../com.aspose.slides/ichart) الذي تم إنشاؤه حديثًا.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض إطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع إطار OLE الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المدمجة ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الكائن [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض إطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع إطار OLE الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط. يتم تخزين هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فلن يكون الملف قابلًا للوصول عند فتح العرض التقديمي من دليل مختلف. |

**القيمة المرجعة:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الكائن [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

ينشئ إطار كائن OLE جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار كائن OLE. |
| x | float | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض إطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع إطار OLE الجديد، بالنقاط. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | معلومات بيانات OLE المدمجة ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**القيمة المرجعة:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الكائن [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

ينشئ إطار كائن OLE جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار كائن OLE. |
| x | float | الإحداثي x لإطار OLE الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار OLE الجديد، بالنقاط. |
| width | float | عرض إطار OLE الجديد، بالنقاط. |
| height | float | ارتفاع إطار OLE الجديد، بالنقاط. |
| className | java.lang.String | اسم الفئة لكائن OLE. |
| path | java.lang.String | المسار إلى الملف المرتبط. يتم تخزين هذا المسار كما هو في العرض التقديمي. إذا تم تحديد مسار نسبي، فلن يكون الملف قابلًا للوصول عند فتح العرض التقديمي من دليل مختلف. |

**القيمة المرجعة:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - الكائن [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) الذي تم إنشاؤه حديثًا.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديدٍ ويضيفه إلى نهاية مجموعة الأشكال.

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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي. |

**القيمة المرجعة:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الكائن [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديدٍ ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> يوضح هذا المثال إضافة كائن Zoom إلى نهاية مجموعة
>  (يفترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
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


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه. |

**القيمة المرجعة:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الكائن [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

ينشئ إطار Zoom جديدٍ ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Zoom في الفهرس المحدد لمجموعة
>  (افترض وجود شريحتين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار Zoom. |
| x | float | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom. |

**القيمة المرجعة:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الكائن [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

ينشئ إطار Zoom جديدٍ بصورة محددة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> هذا المثال يوضح إنشاء وإدخال كائن Zoom في الفهرس المحدد لمجموعة
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


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار Zoom. |
| x | float | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [ISlide](../../com.aspose.slides/islide) | الـ [ISlide](../../com.aspose.slides/islide) المشار إليه بواسطة إطار Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة للـ [IPPImage](../../com.aspose.slides/ippimage) المشار إليه. |

**القيمة المرجعة:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - الكائن [IZoomFrame](../../com.aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديدٍ ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> هذا المثال يوضح إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الكائن [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديدٍ بصورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> هذا المثال يوضح إضافة كائن Section Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
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
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ [IPPImage](../../com.aspose.slides/ippimage) لعرضه داخل إطار Section Zoom. |

**القيمة المرجعة:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الكائن [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

ينشئ إطار Section Zoom جديدٍ ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (يفترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار Section Zoom. |
| x | float | الإحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

**القيمة المرجعة:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الكائن [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

ينشئ إطار Section Zoom جديدٍ بصورة محددة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Section Zoom في الفهرس المحدد لمجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
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


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري-المؤشر الذي يُدرج عنده إطار Section Zoom. |
| x | float | الإحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [ISection](../../com.aspose.slides/isection) | الـ [ISection](../../com.aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الصورة لعرضها داخل إطار Section Zoom. |

**القيمة المرجعة:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - الكائن [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

ينشئ إطار Summary Zoom جديدٍ ويضيفه إلى نهاية مجموعة الأشكال.

--------------------

> ```
> هذا المثال يوضح إضافة كائن Summary Zoom إلى نهاية مجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | الإحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | float | الإحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | float | عرض إطار Summary Zoom الجديد، بالنقاط. |
| height | float | ارتفاع إطار Summary Zoom الجديد، بالنقاط. |
| | | |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - الـ[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

ينشئ إطار ملخص تكبير جديد ويضيفه إلى مجموعة الأشكال عند الفهرس المحدد.

--------------------

> ```
> يوضح هذا المثال إنشاء وإدراج كائن Summary Zoom في الفهرس المحدد لمجموعة
>  (افترض وجود قسمين على الأقل في عرض "Presentation.pptx"):
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
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار ملخص التكبير. |
| x | float | الإحداثي السيني لإطار ملخص التكبير الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار ملخص التكبير الجديد، بالنقاط. |
| width | float | العرض لإطار ملخص التكبير الجديد، بالنقاط. |
| height | float | الارتفاع لإطار ملخص التكبير الجديد، بالنقاط. |

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**القيمة المرجعة:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - الـ[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بالنقاط. |
| width | float | العرض لإطار الفيديو الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الفيديو الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو لتضمينه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ[IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

ينشئ إطار فيديو جديد ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بالنقاط. |
| width | float | العرض لإطار الفيديو الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الفيديو الجديد، بالنقاط. |
| video | [IVideo](../../com.aspose.slides/ivideo) | الـ[IVideo](../../com.aspose.slides/ivideo) لتضمينه في إطار الفيديو. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ[IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار فيديو جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار الفيديو. |
| x | float | الإحداثي السيني لإطار الفيديو الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الفيديو الجديد، بالنقاط. |
| width | float | العرض لإطار الفيديو الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الفيديو الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الفيديو لتضمينه. |

**القيمة المرجعة:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - الـ[IVideoFrame](../../com.aspose.slides/ivideoframe) الذي تم إنشاؤه حديثًا.
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

ينشئ إطار صوت جديد مرتبط بمسار CD ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي لربطه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

ينشئ إطار صوت جديد مرتبط بملف صوت خارجي ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| fname | java.lang.String | المسار أو اسم ملف الصوت الخارجي لربطه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد مع ملف WAV مضمّن ويضيفه إلى نهاية مجموعة الأشكال. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويضيفه إلى نهاية مجموعة الأشكال باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مثيل [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

ينشئ إطار صوت جديد مع ملف WAV مضمّن ويُدرجه في مجموعة الأشكال عند الفهرس المحدد. يتم إضافة الصوت المضمّن إلى مجموعة Presentation.Audios.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio_stream | java.io.InputStream | تدفق إدخال يحتوي على بيانات صوت WAV لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

ينشئ إطار صوت جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد باستخدام كائن صوت موجود من قائمة Presentation.Audios.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدراج إطار الصوت. |
| x | float | الإحداثي السيني لإطار الصوت الجديد، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصوت الجديد، بالنقاط. |
| width | float | العرض لإطار الصوت الجديد، بالنقاط. |
| height | float | الارتفاع لإطار الصوت الجديد، بالنقاط. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | مثيل [IAudio](../../com.aspose.slides/iaudio) من مجموعة Presentation.Audios لتضمينه. |

**القيمة المرجعة:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - الـ[IAudioFrame](../../com.aspose.slides/iaudioframe) الذي تم إنشاؤه حديثًا.
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

يرجع الفهرس الصفري لأول ظهور للشكل المحدد في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | الشكل لتحديد موقعه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس الصفري لأول ظهور للشكل في مجموعة الأشكال إذا تم العثور عليه؛ وإلا، \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

ينشئ ويرجع مصفوفة تحتوي على جميع الأشكال.

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

ينشئ ويرجع مصفوفة تحتوي على جميع الأشكال في النطاق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس الشكل الأول لإرجاعه. |
| count | int | عدد الأشكال لإرجاعها. |

**القيمة المرجعة:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

ينقل الشكل المحدد إلى موضع جديد داخل مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الهدف حيث سيُوضع الشكل. |
| shape | [IShape](../../com.aspose.slides/ishape) | الـ[IShape](../../com.aspose.slides/ishape) لنقله داخل المجموعة. |
### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

ينقل الأشكال المحددة داخل مجموعة الأشكال، موضعاً إياها بدءاً من الفهرس المقدم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الهدف حيث سيُوضع أول شكل محدد؛ تتبع الأشكال التالية بالترتيب المقدم. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | واحد أو أكثر من مثيلات [IShape](../../com.aspose.slides/ishape) لنقلها داخل المجموعة. |
### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | الـ[ShapeType](../../com.aspose.slides/shapetype) للشكل التلقائي الذي سيُضاف. |

| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - التي تم إنشاؤها حديثًا [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا ذاتيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته باستخدام تنسيق القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للشكل الذاتي المراد إضافته. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق نمط القالب الافتراضي (نمط بسيط، نص متمركز، واسم غير فارغ) على الشكل الجديد؛ false لإنشاء الشكل بجميع الخصائص مضبوطة على القيم الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الذي تم إنشاؤه حديثًا [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

ينشئ شكلًا ذاتيًا مستطيلًا جديدًا لاستضافة المحتوى الرياضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - التي تم إنشاؤها حديثًا [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكلًا ذاتيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه الشكل الذاتي الجديد. |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للشكل الذاتي المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الذي تم إنشاؤه حديثًا [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكلًا ذاتيًا جديدًا ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تهيئته باستخدام نمط القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه الشكل الذاتي. |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للشكل الذاتي المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | float | عرض إطار الشكل، بالنقاط. |
| height | float | ارتفاع إطار الشكل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق نمط القالب الافتراضي (يتضمن اسمًا غير فارغ، نمطًا بسيطًا، ونصًا متمركزًا)؛ false لإنشاء الشكل بجميع الخصائص مضبوطة على القيم الافتراضية. |

**القيمة المرجعة:**
[IAutoShape](../../com.aspose.slides/iautoshape) - الذي تم إنشاؤه حديثًا [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

ينشئ مجموعة أشكال فارغة جديدة ويضيفها إلى نهاية مجموعة الأشكال. سيُضبط إطار المجموعة تلقائيًا ليلائم أي أشكال تُضاف إليها.

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - التي تم إنشاؤها حديثًا [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

ينشئ مجموعة أشكال جديدة، يحول الصورة SVG المحددة إلى أشكال فردية، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | الـ[ISvgImage](../../com.aspose.slides/isvgimage) الذي يحتوي على محتوى متجه للتحويل إلى أشكال. |
| x | float | الإحداثي السيني لإطار المجموعة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار المجموعة، بالنقاط. |
| width | float | عرض إطار المجموعة، بالنقاط. |
| height | float | ارتفاع إطار المجموعة، بالنقاط. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - التي تم إنشاؤها حديثًا [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

ينشئ مجموعة أشكال فارغة جديدة ويُدخله إلى مجموعة الأشكال عند الفهرس المحدد. سيُضبط إطار المجموعة تلقائيًا ليلائم أي أشكال تُضاف إليها.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه مجموعة الأشكال. |

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape) - التي تم إنشاؤها حديثًا [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد بنمط القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إضافته. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الذي تم إنشاؤه حديثًا [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إنشائه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الذي تم إنشاؤه حديثًا [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

ينشئ شكل موصل جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه موصل الشكل. |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الذي تم إنشاؤه حديثًا [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

ينشئ شكل موصل جديد ويُدخله في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق نمط القالب الافتراضي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه موصل الشكل. |
| shapeType | int | ال[ShapeType](../../com.aspose.slides/shapetype) للموصل المراد إدراجه. |
| x | float | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | float | عرض إطار الموصل، بالنقاط. |
| height | float | ارتفاع إطار الموصل، بالنقاط. |
| createFromTemplate | boolean | true لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ false لإنشاء الموصل بقيم الخصائص الافتراضية. |

**القيمة المرجعة:**
[IConnector](../../com.aspose.slides/iconnector) - الذي تم إنشاؤه حديثًا [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeType | int | يحدد نوع الشكل الموجود في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ[IPPImage](../../com.aspose.slides/ippimage) الذي يُعرض في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - التي تم إنشاؤها حديثًا [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

ينشئ إطار صورة جديد يحتوي على الصورة المحددة ويُدخله في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري (الصفر-مبني) الذي يُدرج فيه إطار الصورة. |
| shapeType | int | يحدد نوع الشكل الموجود في [ShapeType](../../com.aspose.slides/shapetype)، باستثناء جميع أنواع الخطوط:<br>ShapeType.Line,<br>ShapeType.StraightConnector1,<br>ShapeType.BentConnector2,<br>ShapeType.BentConnector3,<br>ShapeType.BentConnector4,<br>ShapeType.BentConnector5,<br>ShapeType.CurvedConnector2,<br>ShapeType.CurvedConnector3,<br>ShapeType.CurvedConnector4,<br>ShapeType.CurvedConnector5. |
| x | float | الإحداثي السيني لإطار الصورة، بالنقاط. |
| y | float | الإحداثي الصادي لإطار الصورة، بالنقاط. |
| width | float | عرض إطار الصورة، بالنقاط. |
| height | float | ارتفاع إطار الصورة، بالنقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | الـ[IPPImage](../../com.aspose.slides/ippimage) الذي يُعرض في إطار الصورة. |

**القيمة المرجعة:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - الذي تم إنشاؤه حديثًا [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

ينشئ جدولًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | float | الإحداثي السيني للجدول، بالنقاط. |
| y | float | الإحداثي الصادي للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة من القيم المزدوجة تمثل عرْض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة من القيم المزدوجة تمثل ارتفاع صفوف الجدول، بالنقاط. |

**القيمة المرجعة:**
[ITable](../../com.aspose.slides/itable) - الذي تم إنشاؤه حديثًا [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
ينشئ جدولًا جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري الذي يتم عنده إدراج table. |
| x | float | إحداثي الـ x للجدول، بالنقاط. |
| y | float | إحداثي الـ y للجدول، بالنقاط. |
| columnWidths | double[] | مصفوفة من القيم المزدوجة تمثّل عرض أعمدة الجدول، بالنقاط. |
| rowHeights | double[] | مصفوفة من القيم المزدوجة تمثّل ارتفاع صفوف الجدول، بالنقاط. |

**الإرجاع:**
[ITable](../../com.aspose.slides/itable) - الـ [ITable](../../com.aspose.slides/itable) الذي تم إنشاؤه حديثًا.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل الشكل عند الفهرس المحدد من مجموعة الأشكال.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري للشكل الذي يُزيل. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

يزيل أول ظهور للشكل المحدد من مجموعة الأشكال.

**المعلمات:**
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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الشكل الذي يُستنسخ. |
| x | float | إحداثي الـ x لإطار الشكل المستنسَخ، بالنقاط. |
| y | float | إحداثي الـ y لإطار الشكل المستنسَخ، بالنقاط. |
| width | float | عرض إطار الشكل المستنسَخ، بالنقاط. |
| height | float | ارتفاع إطار الشكل المستنسَخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. الشكل الجديد يحتفظ بعرض وارتفاع الـ sourceShape.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي الـ x لإطار الشكل المستنسَخ، بالنقاط. |
| y | float | إحداثي الـ y لإطار الشكل المستنسَخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويضيفها إلى نهاية مجموعة الأشكال. الشكل المستنسَخ يحتفظ بموقع وحجم الأصل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري الذي يتم عنده إدراج الشكل المستنسَخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي الـ x لإطار الشكل المستنسَخ، بالنقاط. |
| y | float | إحداثي الـ y لإطار الشكل المستنسَخ، بالنقاط. |
| width | float | عرض إطار الشكل المستنسَخ، بالنقاط. |
| height | float | ارتفاع إطار الشكل المستنسَخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال عند الفهرس المحدد. الشكل الجديد يحتفظ بعرض وارتفاع الـ sourceShape.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري الذي يتم عنده إدراج الشكل المستنسَخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |
| x | float | إحداثي الـ x لإطار الشكل المستنسَخ، بالنقاط. |
| y | float | إحداثي الـ y لإطار الشكل المستنسَخ، بالنقاط. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

ينشئ نسخة من الشكل المحدد ويدخلها في مجموعة الأشكال عند الفهرس المحدد. الشكل المستنسَخ يحتفظ بموقع وحجم الأصل.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | المؤشر الصفري الذي يتم عنده إدراج الشكل المستنسَخ. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | الـ [IShape](../../com.aspose.slides/ishape) الذي يُستنسخ. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - الـ [IShape](../../com.aspose.slides/ishape) الذي تم إنشاؤه حديثًا.