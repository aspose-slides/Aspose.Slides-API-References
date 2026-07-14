---
title: Presentation
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل عرضًا تقديميًا لبرنامج Microsoft PowerPoint.
type: docs
url: /ar/com.aspose.slides/presentation/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

يمثل عرضًا تقديميًا لبرنامج Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
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
>  // تحميل أي ملف مدعوم في Presentation مثل ppt أو pptx أو odp إلخ.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // حفظ ملف العرض التقديمي.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Presentation()](#Presentation--) | هذا المُنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | هذا المُنشئ ينشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(String file)](#Presentation-java.lang.String-) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرَأ منه محتويات العرض التقديمي. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرَأ منه محتويات العرض التقديمي. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | إرجاع أو تعيين التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | إرجاع أو تعيين التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter الفعلي. |
| [getProtectionManager()](#getProtectionManager--) | يحصل على مدير أذونات هذا العرض التقديمي. |
| [getSlides()](#getSlides--) | إرجاع قائمة بجميع الشرائح المعرفة في العرض التقديمي. |
| [getSections()](#getSections--) | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. |
| [getSlideSize()](#getSlideSize--) | إرجاع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | إرجاع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. |
| [getMasters()](#getMasters--) | إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | إرجاع مدير الملاحظات الرئيسي. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | إرجاع مدير نسخة المذكرة الرئيسية. |
| [getFontsManager()](#getFontsManager--) | إرجاع مدير الخطوط. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | إرجاع نمط النص الافتراضي للأشكال. |
| [getCommentAuthors()](#getCommentAuthors--) | إرجاع مجموعة مؤلفي التعليقات. |
| [getDocumentProperties()](#getDocumentProperties--) | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. |
| [getImages()](#getImages--) | إرجاع مجموعة جميع الصور في العرض التقديمي. |
| [getAudios()](#getAudios--) | إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. |
| [getVideos()](#getVideos--) | إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. |
| [getSlideShowSettings()](#getSlideShowSettings--) | إرجاع إعدادات عرض الشرائح للعرض التقديمي. |
| [getDigitalSignatures()](#getDigitalSignatures--) | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. |
| [getCustomData()](#getCustomData--) | إرجاع البيانات المخصصة للعرض التقديمي. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | إرجاع جميع أجزاء البيانات المخصصة في العرض التقديمي. |
| [getVbaProject()](#getVbaProject--) | الحصول على أو تعيين مشروع VBA مع ماكروات العرض التقديمي. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | الحصول على أو تعيين مشروع VBA مع ماكروات العرض التقديمي. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، التخطيطية، أو شرائح الملاحظات). |
| [getViewProperties()](#getViewProperties--) | الحصول على خصائص العرض العامة للعرض التقديمي. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [getSensitivityLabels()](#getSensitivityLabels--) | إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. |
| [getSlideById(long id)](#getSlideById-long-) | إرجاع Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [getSourceFormat()](#getSourceFormat--) | إرجاع معلومات عن الصيغة التي تم تحميل العرض التقديمي منها. |
| [getMasterTheme()](#getMasterTheme--) | إرجاع السمة الرئيسية. |
| [save(String fname, int format)](#save-java.lang.String-int-) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغ المحددة. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغ المحددة. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغ المحددة ومع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغ المحددة ومع خيارات إضافية. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | حفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل تنسيق XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | إرجاع كائنات Image لجميع شرائح العرض التقديمي. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي مع مقياس مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي مع مقياس مخصص. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي بحجم محدد. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي بحجم محدد. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات في جميع الأشكال المقبولة في جميع الشرائح. |
| [dispose()](#dispose--) | يطلق جميع الموارد المستخدمة بواسطة كائن Presentation هذا. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصلي للنص. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع تطابقات التعبير النمطي بالسلسة المحددة. |
### Presentation() {#Presentation--}
```
public Presentation()
```

هذا المُنشئ ينشئ عرض تقديمي جديد من الصفر. يحتوي العرض المخلق على شريحة فارغة واحدة.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

هذا المُنشئ ينشئ عرض تقديمي جديد من الصفر. يحتوي العرض المخلق على شريحة فارغة واحدة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تدفق الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرَأ منه محتويات العرض التقديمي.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقرَأ منه محتويات العرض التقديمي.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

إرجاع أو تعيين التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. الوقت عند إنشاء كائن Presentation هذا افتراضيًا. قراءة/كتابة java.util.Date.

**الإرجاع:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

إرجاع أو تعيين التاريخ والوقت اللذان سيستبدلان محتوى حقول datetime. الوقت عند إنشاء كائن Presentation هذا افتراضيًا. قراءة/كتابة java.util.Date.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter الفعلي. للقراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible تُستخدم للإشارة إلى أن عنصر نُسق التذييل في الشريحة غير موجود.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility تُستخدم لجعل عنصر نُسق التذييل في الشريحة مرئيًا.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible تُستخدم للإشارة إلى أن عنصر نُسق رقم الشريحة غير موجود.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility تُستخدم لجعل عنصر نُسق رقم الشريحة مرئيًا.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible تُستخدم للإشارة إلى أن عنصر نُسق التاريخ والوقت في الشريحة غير موجود.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility تُستخدم لجعل عنصر نُسق التاريخ والوقت في الشريحة مرئيًا.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText تُستخدم لتعيين النص إلى عنصر نُسق التذييل في الشريحة.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText تُستخدم لتعيين النص إلى عنصر نُسق التاريخ والوقت في الشريحة.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility تُستخدم لجعل الشريحة الرئيسية وجميع العناصر الفرعية للتذييل مرئية.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility تُستخدم لجعل الشريحة الرئيسية وجميع عناصر أرقام الصفحات الفرعية مرئية.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility تُستخدم لجعل الشريحة الرئيسية وجميع عناصر التاريخ والوقت الفرعية مرئية.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText تُستخدم لتعيين النص إلى الشريحة الرئيسية وجميع العناصر الفرعية للتذييل.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText تُستخدم لتعيين النص إلى الشريحة الرئيسية وجميع العناصر الفرعية للتاريخ والوقت.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

يحصل على مدير أذونات هذا العرض التقديمي. للقراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**الإرجاع:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

إرجاع قائمة بجميع الشرائح المعرفة في العرض التقديمي. للقراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // ضبط لون خلفية أول ISlide إلى اللون الأزرق
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
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // ضبط الخلفية باستخدام صورة
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // ضبط الصورة
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // إضافة صورة إلى مجموعة صور العرض التقديمي
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
>  // إنشاء كائن Presentation لتحميل ملف العرض التقديمي المصدر
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
>  // إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // تطبيق انتقال من نوع دائرة على الشريحة 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // ضبط مدة الانتقال إلى 3 ثوانٍ
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // تطبيق انتقال من نوع مشط على الشريحة 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // ضبطمدة الانتقال إلى 5 ثوانٍ
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // تطبيق انتقال من نوع تكبير على الشريحة 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // ضبط مدة الانتقال إلى 7 ثوانٍ
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


**الإرجاع:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. للقراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

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
>      // section1 سيتم إنهاؤها عند newSlide2 وبعدها سيبدأ section2
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

**الإرجاع:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

إرجاع كائن حجم الشريحة. للقراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

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
>          // ضبط حجم شريحة العروض المنشأة لتكون مطابقة لمصدرها
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize تُستخدم لتعيين حجم الشريحة مع مقياس المحتوى لضمان الملاءمة
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize تُستخدم لتعيين حجم الشريحة مع تعظيم حجم المحتوى
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


**الإرجاع:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

إرجاع كائن حجم شريحة الملاحظات. للقراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**الإرجاع:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. للقراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام خاصية IMasterSlide.LayoutSlides.

**الإرجاع:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. للقراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // ضبط لون خلفية الشريحة الرئيسية (Master ISlide) إلى اللون الأخضر الداكن
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
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
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
>          // ملف العرض التقديمي يحتوي فقط على نوعي التخطيط فارغ ومخصص.
>          // لكن شرائح التخطيط ذات الأنواع المخصصة لديها أسماء شرائح مختلفة،
>          // مثل "Title" و "Title and Content" وغيرها. ويمكن استخدام هذه
>          // الأسماء لاختيار شريحة التخطيط.
>          // كما يمكن استخدام مجموعة أنواع الأشكال النائبة. على سبيل المثال،
>          // يجب أن تحتوي شريحة العنوان على نوعٍ واحد فقط من العنصر النائب Title، إلخ.
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


**الإرجاع:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

إرجاع مدير الملاحظات الرئيسي. للقراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**الإرجاع:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

إرجاع مدير نسخة المذكرة الرئيسية. للقراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**الإرجاع:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

إرجاع مدير الخطوط. للقراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // تحميل خط المصدر لاستبداله
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


**الإرجاع:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

إرجاع نمط النص الافتراضي للأشكال. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

إرجاع مجموعة مؤلفي التعليقات. للقراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**الإرجاع:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. للقراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**الإرجاع:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

إرجاع مجموعة جميع الصور في العرض التقديمي. للقراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // إنشاء عرض تقديمي جديد سيُضاف إليه الصورة.
>  Presentation pres = new Presentation();
>  try
>  {
>      // نفترض أن لدينا ملف صورة كبير نريد تضمينه في العرض التقديمي
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // لنضيف الصورة إلى العرض التقديمي - نختار سلوك KeepLocked لأننا
>          // لا نعتزم الوصول إلى ملف "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // يحفظ العرض التقديمي. أثناء توليد عرض تقديمي كبير، يبقى استهلاك الذاكرة
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // يضيف الصورة إلى العرض التقديمي
>          IPPImage image = pres.getImages().addImage(fos);
>          // ينشئ إطار صورة على الشريحة 1 استنادًا إلى الصورة التي تمت إضافتها مسبقًا
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. للقراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. للقراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف PPTX
>  Presentation pres = new Presentation();
>  try {
>      // الحصول على الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // تضمين فيديو داخل العرض التقديمي
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // إضافة إطار فيديو
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // ضبط الفيديو في إطار الفيديو
>      vf.setEmbeddedVideo(vid);
>      // ضبط وضع التشغيل ومستوى الصوت للفيديو
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // حفظ العرض التقديمي إلى القرص
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
>  // إنشاء عرض تقديمي جديد ستُضاف إليه الفيديو
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // لنضيف الفيديو إلى العرض التقديمي - اخترنا سلوك KeepLocked لأننا
>          // لا نعتزم الوصول إلى ملف "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // حفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير، يظل استهلاك الذاكرة
>          // منخفضًا طوال دورة حياة كائن pres.
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
>  // إنشاء مثال من Presentation، يقفل ملف "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // لنحفظ كل فيديو إلى ملف. لتجنب استهلاك الذاكرة العالي، نحتاج إلى مخزن يُستخدم
>      // لنقل البيانات من تدفق الفيديو في العرض التقديمي إلى تدفق لملف فيديو جديد تم إنشاؤه.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // يفتح تدفق فيديو العرض التقديمي. يرجى ملاحظة أننا تجنبنا عن قصد الوصول إلى الخصائص
>          // مثل video.BinaryData - لأن هذه الخاصية تُعيد مصفوفة بايت تحتوي على فيديو كامل، مما
>          // يؤدي إلى تحميل البايتات إلى الذاكرة. نستخدم video.GetStream، التي تُعيد Stream - ولا
>          //  تتطلب تحميل الفيديو بالكامل إلى الذاكرة.
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
>          // سيظل استهلاك الذاكرة منخفضًا بغض النظر عن حجم الفيديو أو العرض التقديمي،
>          // إذا لزم الأمر، يمكنك تطبيق الخطوات نفسها على ملفات الصوت.
>      }
>      // If necessary, you can apply the same steps for audio files.
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


**الإرجاع:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

إرجاع إعدادات عرض الشرائح للعرض التقديمي.

**الإرجاع:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. للقراءة فقط [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**الإرجاع:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

إرجاع البيانات المخصصة للعرض التقديمي. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

إرجاع جميع أجزاء البيانات المخصصة في العرض التقديمي. للقراءة فقط ICustomXmlPart[].

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


**الإرجاع:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

الحصول على أو تعيين مشروع VBA مع ماكروات العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

الحصول على أو تعيين مشروع VBA مع ماكروات العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، التخطيطية، أو شرائح الملاحظات). للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

الحصول على خصائص العرض العامة للعرض التقديمي. للقراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**الإرجاع:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

يمثل رقم الشريحة الأولى في العرض التقديمي

**الإرجاع:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

يمثل رقم الشريحة الأولى في العرض التقديمي

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // طباعة التسميات المطبقة
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // إضافة التسمية الجديدة
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // الحصول على معرف التسمية الحساسة من السياسة
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // الحصول على معرف موقع Azure AD من السياسة
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

إرجاع Slide أو MasterSlide أو LayoutSlide حسب المعرف.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| id | long | معرف الشريحة. |

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

إرجاع معلومات عن الصيغة التي تم تحميل العرض التقديمي منها. للقراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**الإرجاع:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

إرجاع السمة الرئيسية. للقراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> //إنشاء كائن Presentation الذي يمثل ملف عرض تقديمي
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

**الإرجاع:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغ المحددة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيُنشأ. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(String fname, int format)
```

حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغ المحددة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغ المحددة ومع خيارات إضافية.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيُنشأ. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغ المحددة ومع خيارات إضافية.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

حفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل تنسيق XAML.

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


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات تنسيق XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

إرجاع كائنات Image لجميع شرائح العرض التقديمي.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي مع مقياس مخصص.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| scaleX | float | القيمة التي سيُكَبَّر بها هذا Thumbnail في اتجاه المحور س. |
| scaleY | float | القيمة التي سيُكَبَّر بها هذا Thumbnail في اتجاه المحور ص. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي مع مقياس مخصص.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| scaleX | float | القيمة التي سيُكَبَّر بها هذا Thumbnail في اتجاه المحور س. |
| scaleY | float | القيمة التي سيُكَبَّر بها هذا Thumbnail في اتجاه المحور ص. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي بحجم محدد.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة في العرض التقديمي بحجم محدد.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيُنشא. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغ المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغ المحددة مع الحفاظ على أرقام الصفحات.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات في جميع الأشكال المقبولة في جميع الشرائح.

### dispose() {#dispose--}
```
public final void dispose()
```

يطلق جميع الموارد المستخدمة بواسطة كائن Presentation هذا.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

إرجاع العرض التقديمي الأصلي للنص. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

تمييز جميع التطابقات للنص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تسليط الضوء على جميع حدوثات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.lang.Integer | اللون المستخدم لتمييز النص. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمييز جميع التطابقات للنص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تسليط الضوء على جميع حدوثات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.lang.Integer | اللون المستخدم لتمييز النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

تمييز جميع التطابقات للتعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // تسليط الضوء على جميع الكلمات التي تتكون من 10 أحرف أو أكثر
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لتمييزها. |
| highlightColor | java.lang.Integer | اللون المستخدم لتمييز النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع مرات ظهور النص المحدد بنص آخر محدد.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حدوثات 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة المراد استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع مرات ظهور oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع تطابقات التعبير النمطي بالسلسة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // استبدال جميع الكلمات التي تتكون من 10 أحرف أو أكثر بـ '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل لاستبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع مرات ظهور السلاسل المستبدلة. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |