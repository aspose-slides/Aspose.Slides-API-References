---
title: Presentation
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل عرض تقديمي من Microsoft PowerPoint.
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
>      // إضافة شكل تلقائي من نوع خط
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // حفظ ملف العرض التقديمي.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // تحميل أي ملف مدعوم في Presentation مثل ppt, pptx, odp وغيرها.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // حفظ ملف العرض التقديمي.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## البُناة

| المُنشئ | الوصف |
| --- | --- |
| [Presentation()](#Presentation--) | هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود. |
| [Presentation(String file)](#Presentation-java.lang.String-) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقْرَأ منه محتويات العرض التقديمي. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقْرَأ منه محتويات العرض التقديمي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | إرجاع أو تعيين التاريخ والوقت اللذين سيستبدلان محتوى حقول التاريخ والوقت. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | إرجاع أو تعيين التاريخ والوقت اللذين سيستبدلان محتوى حقول التاريخ والوقت. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter الفعلي. |
| [getProtectionManager()](#getProtectionManager--) | الحصول على مدير الأذونات لهذا العرض التقديمي. |
| [getSlides()](#getSlides--) | إرجاع قائمة بجميع الشرائح المُعَرَّفة في العرض التقديمي. |
| [getSections()](#getSections--) | إرجاع قائمة بجميع أقسام الشرائح المُعَرَّفة في العرض التقديمي. |
| [getSlideSize()](#getSlideSize--) | إرجاع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | إرجاع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | إرجاع قائمة بجميع شرائح التخطيط المُعَرَّفة في العرض التقديمي. |
| [getMasters()](#getMasters--) | إرجاع قائمة بجميع شرائح القالب المُعَرَّفة في العرض التقديمي. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | إرجاع مدير القالب الملاحظات. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | إرجاع مدير القالب النشرة. |
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
| [getVbaProject()](#getVbaProject--) | الحصول على أو تعيين مشروع VBA مع وحدات الماكرو للعرض التقديمي. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | الحصول على أو تعيين مشروع VBA مع وحدات الماكرو للعرض التقديمي. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | توفير وصول سهل إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في القوالب أو التخطيطات أو شرائح الملاحظات). |
| [getViewProperties()](#getViewProperties--) | الحصول على خصائص العرض الواسعة للعرض التقديمي. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | يمثل رقم الشريحة الأولى في العرض التقديمي |
| [getSensitivityLabels()](#getSensitivityLabels--) | إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. |
| [getSlideById(long id)](#getSlideById-long-) | إرجاع شريحة Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [getSourceFormat()](#getSourceFormat--) | إرجاع معلومات حول التنسيق الذي تم تحميل العرض التقديمي منه. |
| [getMasterTheme()](#getMasterTheme--) | إرجاع سمة القالب. |
| [save(String fname, int format)](#save-java.lang.String-int-) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض التقديمي إلى ملف بالصيغة المحددة ومع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | حفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | إرجاع كائنات Image لجميع شرائح العرض التقديمي. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | إرجاع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | إرجاع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | إرجاع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بالحجم المحدد. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | حفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | حفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع النصوص المتصلة التي لها نفس التنسيق في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح. |
| [dispose()](#dispose--) | يطبع جميع الموارد المستخدمة بواسطة كائن Presentation هذا. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصل للنص. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للنص العيني باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | استبدال جميع مرات ظهور النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | استبدال جميع تطابقات التعبير النمطي بالسلسلة المحددة. |
| [refreshChartsData()](#refreshChartsData--) | إعادة تحميل البيانات لجميع المخططات في العرض التقديمي من دفاتر العمل المصدر. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | إعادة تحميل البيانات لجميع المخططات في العرض التقديمي من دفاتر العمل المصدر. |

### Presentation() {#Presentation--}
```
public Presentation()
```

هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر. العرض التقديمي المُنشأ يحتوي على شريحة فارغة واحدة.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

هذا المُنشئ يُنشئ عرضًا تقديميًا جديدًا من الصفر. العرض التقديمي المُنشأ يحتوي على شريحة فارغة واحدة.

**المعلمات:**
| المعامل | النوع | الوصف |
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تيار الإدخال. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

هذا المُنشئ هو الآلية الأساسية لقراءة عرض تقديمي موجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تيار الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقْرَأ منه محتويات العرض التقديمي.

--------------------

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

هذا المُنشئ يحصل على مسار ملف المصدر الذي تُقْرَأ منه محتويات العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف الإدخال. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | خيارات تحميل إضافية. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

إرجاع أو تعيين التاريخ والوقت اللذين سيستبدلان محتوى حقول التاريخ والوقت. الوقت هو وقت إنشاء كائن Presentation هذا افتراضيًا. قراءة/كتابة java.util.Date.

**القيمة المرجعة:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

إرجاع أو تعيين التاريخ والوقت اللذين سيستبدلان محتوى حقول التاريخ والوقت. الوقت هو وقت إنشاء كائن Presentation هذا افتراضيًا. قراءة/كتابة java.util.Date.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter الفعلي. قراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // خاصية IsFooterVisible تُستخدم للدلالة على أن عنصر النائب لتذييل الشريحة غير موجود.
>      {
>          headerFooterManager.setFooterVisibility(true); // طريقة SetFooterVisibility تُستخدم لجعل عنصر النائب لتذييل الشريحة مرئيًا.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // خاصية IsSlideNumberVisible تُستخدم للدلالة على أن عنصر النائب لرقم صفحة الشريحة غير موجود.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // طريقة SetSlideNumberVisibility تُستخدم لجعل عنصر النائب لرقم صفحة الشريحة مرئيًا.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // خاصية IsDateTimeVisible تُستخدم للدلالة على أن عنصر النائب لتاريخ ووقت الشريحة غير موجود.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // طريقة SetFooterVisibility تُستخدم لجعل عنصر النائب لتاريخ ووقت الشريحة مرئيًا.
>      }
>      headerFooterManager.setFooterText("Footer text"); // طريقة SetFooterText تُستخدم لتعيين النص إلى عنصر النائب لتذييل الشريحة.
>      headerFooterManager.setDateTimeText("Date and time text"); // طريقة SetDateTimeText تُستخدم لتعيين النص إلى عنصر النائب لتاريخ ووقت الشريحة.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // طريقة SetFooterAndChildFootersVisibility تُستخدم لجعل شريحة الماستر وجميع عناصر النائب لتذييل الفروع مرئية.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // طريقة SetSlideNumberAndChildSlideNumbersVisibility تُستخدم لجعل شريحة الماستر وجميع عناصر النائب لأرقام الصفحات الفروع مرئية.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // طريقة SetDateTimeAndChildDateTimesVisibility تُستخدم لجعل شريحة الماستر وجميع عناصر النائب لتاريخ ووقت الفروع مرئية.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // طريقة SetFooterAndChildFootersText تُستخدم لتعيين النص إلى شريحة الماستر وجميع عناصر النائب لتذييل الفروع.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // طريقة SetDateTimeAndChildDateTimesText تُستخدم لتعيين النص إلى شريحة الماستر وجميع عناصر النائب لتاريخ ووقت الفروع.
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

الحصول على مدير الأذونات لهذا العرض التقديمي. قراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**القيمة المرجعة:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

إرجاع قائمة بجميع الشرائح المُعَرَّفة في العرض التقديمي. قراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // تعيين لون خلفية الشريحة الأولى (ISlide) إلى اللون الأزرق
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
>      // تعيين الخلفية بصورة
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // تعيين الصورة
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // إضافة الصورة إلى مجموعة صور العرض التقديمي
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // حفظ العرض التقديمي إلى القرص
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
>      // حفظ العرض التقديمي إلى القرص
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
>      // حفظ العرض التقديمي إلى القرص
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

إرجاع قائمة بجميع أقسام الشرائح المُعَرَّفة في العرض التقديمي. قراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 سيتنتهي عند newSlide2 وبعد ذلك سيبدأ section2
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

إرجاع كائن حجم الشريحة. قراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

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
>          // تعيين حجم الشرائح للعروض التقديمية المولدة بما يتوافق مع المصدر
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // طريقة SetSize تُستخدم لتعيين حجم الشريحة مع تعديل المحتوى لضمان الملاءمة
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // طريقة SetSize تُستخدم لتعيين حجم الشريحة مع تكبير حجم المحتوى إلى الحد الأقصى
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

إرجاع كائن حجم شريحة الملاحظات. قراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**القيمة المرجعة:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

إرجاع قائمة بجميع شرائح التخطيط المُعَرَّفة في العرض التقديمي. قراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية IMasterSlide.LayoutSlides.

**القيمة المرجعة:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

إرجاع قائمة بجميع شرائح القالب المُعَرَّفة في العرض التقديمي. قراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

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
>  // إنشاء كائن Presentation الذي يمثل ملف العرض التقديمي
>  Presentation pres = new Presentation();
>  try
>  {
>      // تعيين لون خلفية شريحة Master (ISlide) إلى اللون الأخضر الغابي
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // حفظ العرض التقديمي إلى القرص
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
>          // ملف العرض يحتوي فقط على تخطيطات فارغة ومخصصة.
>          // ولكن شرائح التخطيط ذات الأنواع المخصصة لها أسماء شرائح مختلفة،
>          // مثل "Title"، "Title and Content"، إلخ. ويمكن استخدام هذه
>          // الأسماء لاختيار شريحة التخطيط.
>          // كما يمكن استخدام مجموعة أنواع الأشكال النائبة. على سبيل المثال،
>          // يجب أن تحتوي شريحة العنوان على نوع العنصر النائب Title فقط، إلخ.
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

إرجاع مدير القالب الملاحظات. قراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**القيمة المرجعة:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

إرجاع مدير القالب النشرة. قراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**القيمة المرجعة:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

إرجاع مدير الخطوط. قراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // تحميل الخط المصدر للاستبدال
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

إرجاع نمط النص الافتراضي للأشكال. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

إرجاع مجموعة مؤلفي التعليقات. قراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**القيمة المرجعة:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**القيمة المرجعة:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

إرجاع مجموعة جميع الصور في العرض التقديمي. قراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

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
>          // لنضيف الصورة إلى العرض التقديمي - نختار سلوك KeepLocked لأننا لا
>          // نعتزم الوصول إلى ملف "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // حفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير، يظل استهلاك الذاكرة
>          // منخفضًا طوال دورة حياة كائن pres
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
>      // إنشاء إطار صورة على الشريحة 1 بناءً على الصورة المضافة مسبقًا
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
إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. للقراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

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

**الإرجاع:**  
[IAudioCollection](../../com.aspose.slides/iaudiocollection)  
### getVideos() {#getVideos--}  
```
public final IVideoCollection getVideos()
```

إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. للقراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // إنشاء عرض تقديمي جديد سيتم إضافة الصورة إليه.
>  Presentation pres = new Presentation();
>  try
>  {
>      // نفترض أن لدينا ملف صورة كبير نريد تضمينه في العرض التقديمي
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // دعنا نضيف الصورة إلى العرض التقديمي - نختار سلوك KeepLocked لأننا
>          // لا نعتزم الوصول إلى ملف "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // حفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير، يظل استهلاك الذاكرة
>          // منخفضًا طوال دورة حياة كائن pres
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
>      // إنشاء إطار صورة على الشريحة 1 بناءً على الصورة المضافة مسبقًا
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

**الإرجاع:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)  
### getSlideShowSettings() {#getSlideShowSettings--}  
```
public SlideShowSettings getSlideShow  
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
>      // تكرار جميع عناصر XML المخصصة
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

الحصول على أو تعيين مشروع VBA مع ماكرو العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**الإرجاع:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)  
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}  
```
public final void setVbaProject(IVbaProject value)
```

الحصول على أو تعيين مشروع VBA مع ماكرو العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}  
```
public final IHyperlinkQueries getHyperlinkQueries()
```

توفر وصولًا سهلًا إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض التقديمي (ليس في القالب أو التخطيط أو شرائح الملاحظات). للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)  
### getViewProperties() {#getViewProperties--}  
```
public final IViewProperties getViewProperties()
```

الحصول على خصائص العرض على مستوى العرض التقديمي. للقراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**الإرجاع:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)  
### getFirstSlideNumber() {#getFirstSlideNumber--}  
```
public final int getFirstSlideNumber()
```

يمثّل رقم الشريحة الأولى في العرض التقديمي

**الإرجاع:**  
int  
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}  
```
public final void setFirstSlideNumber(int value)
```

يمثّل رقم الشريحة الأولى في العرض التقديمي

**المعلمات:**  
| المعامل | النوع | الوصف |
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
>      // طباعة العلامات المطبقة
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // إضافة العلامة الجديدة
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // الحصول على معرف العلامة الحساسة من السياسة
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

إرجاع شريحة أو شريحة رئيسية أو شريحة تخطيط حسب المعرف.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | long | معرف الشريحة. |

**الإرجاع:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.  
### getSourceFormat() {#getSourceFormat--}  
```
public final int getSourceFormat()
```

إرجاع معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. للقراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**الإرجاع:**  
int  
### getMasterTheme() {#getMasterTheme--}  
```
public final IMasterTheme getMasterTheme()
```

إرجاع السمة الرئيسية. للقراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //إنشاء كائن Presentation يمثل ملف عرض تقديمي
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

يحفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}  
```
public final void save(OutputStream stream, int format)
```

يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصّيغة المحددة.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}  
```
public final void save(String fname, int format, ISaveOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة ومع خيارات إضافية.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}  
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصّيغة المحددة ومع خيارات إضافية.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}  
```
public final void save(IXamlOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات تمثل ترميز XAML.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات تنسيق XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}  
```
public final IImage[] getImages(IRenderingOptions options)
```

إرجاع كائنات Image لجميع شرائح العرض التقديمي.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}  
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}  
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي مع مقياس مخصص.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| scaleX | float | القيمة التي يُجرى بها تعديل مقياس الصورة المصغرة في اتجاه المحور س. |
| scaleY | float | القيمة التي تُجرى بها تعديل مقياس الصورة المصغرة في اتجاه المحور ص. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}  
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي مع مقياس مخصص.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| scaleX | float | القيمة التي يُجرى بها تعديل مقياس الصورة المصغرة في اتجاه المحور س. |
| scaleY | float | القيمة التي تُجرى بها تعديل مقياس الصورة المصغرة في اتجاه المحور ص. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}  
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

إرجاع كائنات Thumbnail Image لجميع شرائح العرض التقديمي بالحجم المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| imageSize | java.awt.Dimension | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}  
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

إرجاع كائنات Thumbnail Image للشرائح المحددة من العرض التقديمي بالحجم المحدد.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات Tiff. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| imageSize | java.awt.Dimension | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**  
com.aspose.slides.IImage[] - كائنات Image.  
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}  
```
public final void save(String fname, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصّيغة المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}  
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالصّيغة المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}  
```
public final void save(OutputStream stream, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصّيغة المحددة مع الحفاظ على أرقام الصفحات.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}  
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصّيغة المحددة مع الحفاظ على أرقام الصفحات.

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

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات صيغة إضافية. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}  
```
public final void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال المقبولة في جميع الشرائح.

### dispose() {#dispose--}  
```
public final void dispose()
```

يطلق جميع الموارد المستخدمة بواسطة كائن Presentation هذا.

### getPresentation() {#getPresentation--}  
```
public final IPresentation getPresentation()
```

إرجاع العرض التقديمي الأصل للنص. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**  
[IPresentation](../../com.aspose.slides/ipresentation)  
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}  
```
public final void highlightText(String text, Color highlightColor)
```

تمييز جميع مطابقات النص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تظليل جميع ظهورات كلمة 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المستخدم لتمييز النص. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}  
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمييز جميع مطابقات النص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تظليل جميع ظهورات كلمة 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المستخدم لتمييز النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}  
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمييز جميع تطابقات التعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // تظليل جميع الكلمات التي تحتوي على 10 رموز أو أكثر
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |

| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي يجب تظليلها. |
| highlightColor | java.awt.Color | اللون لتظليل النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع تكرارات النص المحدد بنص محدد آخر.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع ظهورات كلمة 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع تكرارات oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع مطابقات التعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Replace all words with 10 symbols or longer with '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي يجب استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع تكرارات السلاسل التي يجب استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد النداء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

يعيد تحميل البيانات لجميع المخططات في العرض من دفاتر العمل المصدر.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public final void refreshChartsData(boolean skipFailedCharts)
```

يعيد تحميل البيانات لجميع المخططات في العرض من دفاتر العمل المصدر.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| skipFailedCharts | boolean | يحدد ما إذا كانت عملية التحديث تستمر إذا فشل مخطط في التحديث. إذا كانت true، يتم تخطي المخططات التي تسبب استثناء؛ وإلا يتم نقل الاستثناء. |