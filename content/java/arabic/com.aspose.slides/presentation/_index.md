---
title: Presentation
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل عرض تقديمي من Microsoft PowerPoint.
type: docs
url: /ar/com.aspose.slides/presentation/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

يمثل عرضًا تقديميًا من Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى
>      ISlide slide = pres.getSlides().get_Item(0);
>      // إضافة شكل تلقائي من النوع خط
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // حفظ ملف العرض التقديمي.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // تحميل أي ملف مدعوم في Presentation مثل ppt، pptx، odp وغيرها.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // حفظ ملف العرض التقديمي.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [Presentation()](#Presentation--) | هذا المنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | هذا المنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(String file)](#Presentation-java.lang.String-) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | يرجع أو يضبط التاريخ والوقت اللذين سيستبدان محتوى حقول التاريخ والوقت. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | يرجع أو يضبط التاريخ والوقت اللذين سيستبدان محتوى حقول التاريخ والوقت. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يرجع مدير رأس وتذييل الصفحة الحالي. |
| [getProtectionManager()](#getProtectionManager--) | يحصل على مدير الصلاحيات لهذا العرض التقديمي. |
| [getSlides()](#getSlides--) | يرجع قائمة بجميع الشرائح المعرفة في العرض التقديمي. |
| [getSections()](#getSections--) | يرجع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. |
| [getSlideSize()](#getSlideSize--) | يرجع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | يرجع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | يرجع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. |
| [getMasters()](#getMasters--) | يرجع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | يرجع مدير ملاحظات الشرائح الرئيسية. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | يرجع مدير مخطوطات الشرائح الرئيسية. |
| [getFontsManager()](#getFontsManager--) | يرجع مدير الخطوط. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | يرجع نمط النص الافتراضي للأشكال. |
| [getCommentAuthors()](#getCommentAuthors--) | يرجع مجموعة مؤلفي التعليقات. |
| [getDocumentProperties()](#getDocumentProperties--) | يرجع كائن DocumentProperties الذي يحتوي على خصائص الوثيقة القياسية والمخصصة. |
| [getImages()](#getImages--) | يرجع مجموعة جميع الصور في العرض التقديمي. |
| [getAudios()](#getAudios--) | يرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. |
| [getVideos()](#getVideos--) | يرجع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. |
| [getSlideShowSettings()](#getSlideShowSettings--) | يرجع إعدادات عرض الشرائح للعرض التقديمي. |
| [getDigitalSignatures()](#getDigitalSignatures--) | يرجع مجموعة التواقيع المستخدمة لتوقيع العرض التقديمي. |
| [getCustomData()](#getCustomData--) | يرجع البيانات المخصصة للعرض التقديمي. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | يرجع جميع الأجزاء المخصصة للبيانات في العرض التقديمي. |
| [getVbaProject()](#getVbaProject--) | يحصل على أو يضبط مشروع VBA مع وحدات ماكرو العرض التقديمي. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | يحصل على أو يضبط مشروع VBA مع وحدات ماكرو العرض التقديمي. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، أو التخطيط، أو الملاحظات). |
| [getViewProperties()](#getViewProperties--) | يحصل على خصائص العرض العامة للعرض التقديمي. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | يمثل رقم الشريحة الأولى في العرض التقديمي. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | يمثل رقم الشريحة الأولى في العرض التقديمي. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يرجع مجموعة تسميات الحساسية المطبقة على وثيقة العرض التقديمي. |
| [getSlideById(long id)](#getSlideById-long-) | يرجع شريحة، شريحة رئيسية أو شريحة تخطيط حسب المعرف. |
| [getSourceFormat()](#getSourceFormat--) | يرجع معلومات حول التنسيق الذي تم تحميل العرض التقديمي منه. |
| [getMasterTheme()](#getMasterTheme--) | يرجع السمة الرئيسية. |
| [save(String fname, int format)](#save-java.lang.String-int-) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة ومع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات تمثل ترميز XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | يرجع كائنات Image لجميع شرائح العرض التقديمي. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بحجم محدد. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بحجم محدد. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الاحتفاظ بأرقام الصفحات. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الاحتفاظ بأرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الاحتفاظ بأرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الاحتفاظ بأرقام الصفحات. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع المقاطع ذات التنسيق نفسه في جميع الفقرات في جميع الأشكال المقبولة في جميع الشرائح. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة من قبل كائن Presentation هذا. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأصل للنص. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يبرز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | يبرز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع مرات ظهور النص المحدد بنص محدد آخر. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
### Presentation() {#Presentation--}
```
public Presentation()
```

هذا المنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

هذا المنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. يحتوي العرض التقديمي المنشأ على شريحة فارغة واحدة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود.

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

هذا المنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي.

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

هذا المنشئ يحصل على مسار ملف المصدر الذي تُقرأ منه محتويات العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

يرجع أو يضبط التاريخ والوقت اللذين سيستبدان محتوى حقول التاريخ والوقت. وقت إنشاء كائن Presentation هذا هو الافتراضي. قراءة/كتابة java.util.Date.

**القيمة المرجعة:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

يرجع أو يضبط التاريخ والوقت اللذين سيستبدان محتوى حقول التاريخ والوقت. وقت إنشاء كائن Presentation هذا هو الافتراضي. قراءة/كتابة java.util.Date.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

يرجع مدير HeaderFooter الحالي. قراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // الخاصية IsFooterVisible تُستخدم للدلالة على أن عنصر نائب تذييل الشريحة غير موجود.
>      {
>          headerFooterManager.setFooterVisibility(true); // الطريقة SetFooterVisibility تُستخدم لجعل عنصر نائب تذييل الشريحة مرئي.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // الخاصية IsSlideNumberVisible تُستخدم للدلالة على أن عنصر نائب رقم صفحة الشريحة غير موجود.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // الطريقة SetSlideNumberVisibility تُستخدم لجعل عنصر نائب رقم صفحة الشريحة مرئي.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // الخاصية IsDateTimeVisible تُستخدم للدلالة على أن عنصر نائب التاريخ والوقت للشريحة غير موجود.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // الطريقة SetFooterVisibility تُستخدم لجعل عنصر نائب التاريخ والوقت للشريحة مرئي.
>      }
>      headerFooterManager.setFooterText("Footer text"); // الطريقة SetFooterText تُستخدم لتعيين نص إلى عنصر نائب تذييل الشريحة.
>      headerFooterManager.setDateTimeText("Date and time text"); // الطريقة SetDateTimeText تُستخدم لتعيين نص إلى عنصر نائب التاريخ والوقت للشريحة.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // الطريقة SetFooterAndChildFootersVisibility تُستخدم لجعل الشريحة الرئيسية وجميع عناصر نائب التذييل التابعة مرئية.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // الطريقة SetSlideNumberAndChildSlideNumbersVisibility تُستخدم لجعل الشريحة الرئيسية وجميع عناصر نائب رقم الصفحة التابعة مرئية.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // الطريقة SetDateTimeAndChildDateTimesVisibility تُستخدم لجعل الشريحة الرئيسية وجميع عناصر نائب التاريخ والوقت التابعة مرئية.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // الطريقة SetFooterAndChildFootersText تُستخدم لتعيين نص إلى الشريحة الرئيسية وجميع عناصر نائب التذييل التابعة.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // الطريقة SetDateTimeAndChildDateTimesText تُستخدم لتعيين نص إلى الشريحة الرئيسية وجميع عناصر نائب التاريخ والوقت التابعة.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

يحصل على مدير الصلاحيات لهذا العرض التقديمي. قراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**القيمة المرجعة:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

يرجع قائمة بجميع الشرائح المعرفة في العرض التقديمي. قراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // تعيين لون خلفية أول شريحة ISlide إلى أزرق
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف العرض التقديمي
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // تعيين الخلفية باستخدام صورة
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // تعيين الصورة
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // إضافة الصورة إلى مجموعة صور العرض التقديمي
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // كتابة العرض التقديمي إلى القرص
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // إنشاء فئة Presentation لتحميل ملف العرض التقديمي المصدر
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // تطبيق انتقال من نوع دائرة على الشريحة 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // تطبيق انتقال من نوع مشط على الشريحة 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // كتابة العرض التقديمي إلى القرص
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // إنشاء فئة Presentation التي تمثل ملف العرض التقديمي
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // تطبيق انتقال من نوع دائرة على الشريحة 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // تعيين مدة الانتقال إلى 3 ثوانٍ
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // تطبيق انتقال من نوع مشط على الشريحة 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // تعيين مدة الانتقال إلى 5 ثوانٍ
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // تطبيق انتقال من نوع تكبير/تصغير على الشريحة 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // تعيين مدة الانتقال إلى 7 ثوانٍ
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // كتابة العرض التقديمي إلى القرص
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

يرجع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. قراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // سيتم إنهاء القسم 1 عند الشريحة newSlide2 وبعدها سيبدأ القسم 2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

يرجع كائن حجم الشريحة. قراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // تعيين حجم الشريحة للعرض التقديمي المولد إلى حجم المصدر
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // الطريقة SetSize تُستخدم لتعيين حجم الشريحة مع تحجيم المحتوى لضمان التناسب
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // الطريقة SetSize تُستخدم لتعيين حجم الشريحة مع تكبير حجم المحتوى
>          // حفظ العرض التقديمي إلى القرص
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // حجم ورق A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

يرجع كائن حجم شريحة الملاحظات. قراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**القيمة المرجعة:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

يرجع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. قراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام خاصية IMasterSlide.LayoutSlides.

**القيمة المرجعة:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

يرجع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. قراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // تعيين لون خلفية الشرائح الرئيسية إلى اللون الأخضر الغابوي
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // كتابة العرض التقديمي إلى القرص
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف العرض التقديمي
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // محاولة البحث حسب نوع شريحة التخطيط
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // الحالة عندما لا يحتوي العرض التقديمي على بعض أنواع التخطيطات.
>          // ملف العرض التقديمي يحتوي فقط على أنواع التخطيط فارغ ومخصص.
>          // لكن شرائح التخطيط ذات الأنواع المخصصة لها أسماء شرائح مختلفة،
>          // مثل "Title"، "Title and Content"، وما إلى ذلك. ويمكن استخدام هذه
>          // الأسماء لاختيار شريحة تخطيط.
>          // كما يمكن استخدام مجموعة أنواع أشكال العنصر النائب. على سبيل المثال،
>          // يجب أن تحتوي شريحة العنوان على نوع العنصر النائب "Title" فقط، إلخ.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // إضافة شريحة فارغة باستخدام شريحة التخطيط المضافة
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // حفظ العرض التقديمي
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**القيمة المرجعة:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

يرجع مدير ملاحظات الشرائح الرئيسية. قراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**القيمة المرجعة:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

يرجع مدير مخطوطات الشرائح الرئيسية. قراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**القيمة المرجعة:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

يرجع مدير الخطوط. قراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // تحميل الخط المصدر ليتم استبداله
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // حفظ العرض التقديمي
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

يرجع نمط النص الافتراضي للأشكال. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

يرجع مجموعة مؤلفي التعليقات. قراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**القيمة المرجعة:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

يرجع كائن DocumentProperties الذي يحتوي على خصائص الوثيقة القياسية والمخصصة. قراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**القيمة المرجعة:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

يرجع مجموعة جميع الصور في العرض التقديمي. قراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // إنشاء عرض تقديمي جديد سيتم إضافة الصورة إليه.
>  Presentation pres = new Presentation();
>  try
>  {
>      // نفترض أن لدينا ملف الصورة الكبيرة الذي نريد تضمينه في العرض التقديمي
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // لنضيف الصورة إلى العرض التقديمي - نختار سلوك KeepLocked لأننا
>          // لا نهدف إلى الوصول إلى ملف "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // حفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير، يبقى استهلاك الذاكرة
>          // منخفضًا طوال دورة حياة كائن pres.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // إضافة صورة إلى العرض التقديمي
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // إنشاء إطار صورة على الشريحة 1 بناءً على الصورة التي أضيفت مسبقًا
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

يرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. قراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
يعيد مجموعة جميع ملفات الفيديو المضمَّنة في العرض التقديمي. للقراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation التي تمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // إدراج الفيديو داخل العرض التقديمي
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // إضافة إطار فيديو
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // تعيين الفيديو إلى إطار الفيديو
>      vf.setEmbeddedVideo(vid);
>      // تعيين وضع التشغيل وحجم الصوت للفيديو
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // كتابة ملف PPTX إلى القرص
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // إنشاء عرض تقديمي جديد سيتم إضافة الفيديو إليه
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // لنضيف الفيديو إلى العرض التقديمي - اخترنا سلوك KeepLocked لأننا
>          // لا نهدف إلى الوصول إلى ملف "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // حفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير، استهلاك الذاكرة
>          // يبقى منخفضًا طوال دورة حياة كائن pres.
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // قفل ملف المصدر وعدم تحميله إلى الذاكرة
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // إنشاء مثيل Presentation، قفل ملف "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // لنحفظ كل فيديو إلى ملف. لتجنب استهلاك عالي للذاكرة، نحتاج إلى مخزن وسيتم استخدامه
>      // لنقل البيانات من تدفق الفيديو الخاص بالعرض التقديمي إلى تدفق لملف فيديو تم إنشاؤه حديثًا.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // يفتح تدفق فيديو العرض التقديمي. يرجى ملاحظة أننا تجنبنا عمدًا الوصول إلى الخصائص
>          // مثل video.BinaryData - لأن هذه الخاصية تعيد مصفوفة بايت تحتوي على فيديو كامل، وبالتالي
>          // تؤدي إلى تحميل البايتات إلى الذاكرة. نستخدم video.GetStream، التي ستعيد Stream - ولا تقوم
>          // تتطلب تحميل الفيديو بالكامل إلى الذاكرة.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // استهلاك الذاكرة سيظل منخفضًا بغض النظر عن حجم الفيديو أو العرض التقديمي،
>      }
>      // إذا لزم الأمر، يمكنك تطبيق نفس الخطوات على ملفات الصوت.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      // إضافة إطار فيديو
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // تحميل الصورة المصغرة
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**القيمة المرجعة:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

يعيد إعدادات عرض الشرائح للعرض التقديمي.

**القيمة المرجعة:**  
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

يعيد مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. للقراءة فقط [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**  
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

يعيد البيانات المخصَّصة للعرض التقديمي. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**  
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

يعيد جميع أجزاء البيانات المخصَّصة في العرض التقديمي. للقراءة فقط ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // تكرار جميع أجزاء XML المخصصة
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**  
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

يحصل أو يعيّن مشروع VBA مع ماكروهات العرض التقديمي. قابل للقراءة والكتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**القيمة المرجعة:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

يحصل أو يعيّن مشروع VBA مع ماكروهات العرض التقديمي. قابل للقراءة والكتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى جميع الارتباطات الفائقة الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، أو التخطيطات، أو شرائح الملاحظات). للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**القيمة المرجعة:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

يحصل على خصائص العرض على مستوى العرض التقديمي. للقراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**القيمة المرجعة:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

يمثل رقم الشريحة الأولى في العرض التقديمي

**القيمة المرجعة:**  
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

يمثل رقم الشريحة الأولى في العرض التقديمي

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

يعيد مجموعة علامات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // طباعة العلامات المطبقة
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // إضافة العلامة الجديدة
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // الحصول على معرّف علامة الحساسية من السياسة
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // الحصول على معرّف موقع Azure AD من السياسة
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**  
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

يعيد شريحة Slide أو MasterSlide أو LayoutSlide حسب المعرف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | long | معرف الشريحة. |

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

يعيد معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. للقراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**القيمة المرجعة:**  
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

يعيد السمة الرئيسية. للقراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| format | int | تنسيق البيانات المُصدَّرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

يحفظ جميع شرائح العرض التقديمي إلى دفق بالإعدادات المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الإخراج. |
| format | int | تنسيق البيانات المُصدَّرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد ومع خيارات إضافية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| format | int | تنسيق البيانات المُصدَّرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى دفق بالتنسيق المحدد ومع خيارات إضافية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الإخراج. |
| format | int | تنسيق البيانات المُصدَّرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات تنسيق XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

يعيد كائنات Image لجميع شرائح العرض التقديمي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

يعيد كائنات Image مصغرة للشرائح المحددة من العرض التقديمي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

يعيد كائنات Image مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |
| scaleX | float | القيمة التي يتم بموجبها تكبير الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بموجبها تكبير الصورة المصغرة في اتجاه المحور الصادي. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

يعيد كائنات Image مصغرة للشرائح المحددة من العرض التقديمي مع تحجيم مخصص.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| scaleX | float | القيمة التي يتم بموجبها تكبير الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بموجبها تكبير الصورة المصغرة في اتجاه المحور الصادي. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

يعيد كائنات Image مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

يعيد كائنات Image مصغرة للشرائح المحددة من العرض التقديمي بالحجم المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات TIFF. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**القيمة المرجعة:**  
com.aspose.slides.IImage[] - كائنات Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | تنسيق البيانات المُصدَّرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | تنسيق البيانات المُصدَّرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى دفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | تنسيق البيانات المُصدَّرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى دفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | دفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | تنسيق البيانات المُصدَّرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

يوحد المقاطع ذات التنسيق المتطابق في جميع الفقرات في جميع الأشكال المقبولة في جميع الشرائح.

### dispose() {#dispose--}
```
public final void dispose()
```

يطلق جميع الموارد المستخدمة بواسطة كائن Presentation هذا.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض التقديمي الأب للنص. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

يُبرز جميع التطابقات للنص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تمييز جميع وقوعات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المراد تمييز النص به. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يُبرز جميع التطابقات للنص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تمييز جميع وقوعات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المراد تمييز النص به. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

يُبرز جميع التطابقات للتعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // تمييز جميع الكلمات التي تحتوي على 10 رموز أو أكثر
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل المراد تمييزها. |
| highlightColor | java.awt.Color | اللون المراد تمييز النص به. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع حدوث النص المحدد بنص محدد آخر.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع وقوعات 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء الراجعي لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع تطابقات التعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // استبدال جميع الكلمات التي تحتوي على 10 رموز أو أكثر بـ '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حدوث السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء الراجعي لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |