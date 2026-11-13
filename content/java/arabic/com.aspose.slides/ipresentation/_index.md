---
title: IPresentation
second_title: مرجع API Aspose.Slides للـ Java
description: مستند عرض تقديمي
type: docs
url: /ar/com.aspose.slides/ipresentation/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

مستند العرض التقديمي
## الطرق

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | يُرجع أو يعيّن التاريخ والوقت اللذين سيستبدلان محتوى حقول datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | يُرجع أو يعيّن التاريخ والوقت اللذين سيستبدلان محتوى datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | يُرجع مدير HeaderFooter للعرض التقديمي. |
| [getProtectionManager()](#getProtectionManager--) | يحصل على مدير الأذونات لهذا العرض التقديمي. |
| [getSlides()](#getSlides--) | يُرجع قائمة بجميع الشرائح المعرفة في العرض التقديمي. |
| [getSections()](#getSections--) | يُرجع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. |
| [getSlideSize()](#getSlideSize--) | يُرجع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | يُرجع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | يُرجع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. |
| [getMasters()](#getMasters--) | يُرجع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | يُرجع مدير الملاحظات الرئيسي. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | يُرجع مدير المخطوطات الرئيسي. |
| [getFontsManager()](#getFontsManager--) | يُرجع مدير الخطوط. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | يُرجع نمط النص الافتراضي للأشكال. |
| [getCommentAuthors()](#getCommentAuthors--) | يُرجع مجموعة مؤلفي التعليقات. |
| [getDocumentProperties()](#getDocumentProperties--) | يُرجع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. |
| [getImages()](#getImages--) | يُرجع مجموعة جميع الصور في العرض التقديمي. |
| [getAudios()](#getAudios--) | يُرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. |
| [getVideos()](#getVideos--) | يُرجع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. |
| [getCustomData()](#getCustomData--) | يُرجع البيانات المخصصة للعرض التقديمي. |
| [getVbaProject()](#getVbaProject--) | يحصل على مشروع VBA مع وحدات ماكرو العرض التقديمي. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | يحصل على مشروع VBA مع وحدات ماكرو العرض التقديمي. |
| [getSourceFormat()](#getSourceFormat--) | يُرجع معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. |
| [getMasterTheme()](#getMasterTheme--) | يُرجع السمة الرئيسية للعرض التقديمي. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلًا إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، التخطيط، أو الملاحظات). |
| [getViewProperties()](#getViewProperties--) | يحصل على خصائص العرض التقديمي العامة. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | يمثل رقم الشريحة الأولى في العرض التقديمي. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | يمثل رقم الشريحة الأولى في العرض التقديمي. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | يُرجع جميع أجزاء البيانات المخصصة في العرض التقديمي. |
| [getDigitalSignatures()](#getDigitalSignatures--) | يُرجع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. |
| [getSensitivityLabels()](#getSensitivityLabels--) | يُرجع مجموعة تصنيفات الحساسية المطبقة على مستند العرض التقديمي. |
| [save(String fname, int format)](#save-java.lang.String-int-) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | يحفظ جميع شرائح العرض التقديمي إلى تدفق في الصّيغة المحددة. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | يحفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة ومع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | يحفظ جميع شرائح العرض التقديمي إلى تدفق في الصّيغة المحددة ومع خيارات إضافية. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | يحفظ الشرائح المحددة للعرض التقديمي إلى ملف بالصّيغة المحددة. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة للعرض التقديمي إلى ملف بالصّيغة المحددة. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | يحفظ الشرائح المحددة للعرض التقديمي إلى تدفق بالصّيغة المحددة. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | يحفظ الشرائح المحددة للعرض التقديمي إلى تدفق بالصّيغة المحددة. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | يحفظ جميع شرائح العرض التقديمي إلى مجموعة ملفات تمثل ترميز XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | يُرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | يُرجع كائنات IImage المصغرة للشرائح المحددة للعرض التقديمي. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | يُرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع مقياس مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | يُرجع كائنات صورة مصغرة للشرائح المحددة للعرض التقديمي مع مقياس مخصص. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | يُرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بالحجم المحدد. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | يُرجع كائنات صورة مصغرة للشرائح المحددة للعرض التقديمي بالحجم المحدد. |
| [getSlideById(long id)](#getSlideById-long-) | يُرجع Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | يجمع النصوص ذات التنسيق المتطابق في جميع الفقرات بجميع الأشكال المقبولة في جميع الشرائح. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | يبرِز جميع مطابقة النص العيني باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يبرِز جميع مطابقة النص العيني باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | يبرِز جميع مطابقة التعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | يستبدل جميع تكرارات النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة. |
| [refreshChartsData()](#refreshChartsData--) | يعيد تحميل بيانات جميع المخططات في العرض التقديمي من دفاتر العمل المصدر. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | يعيد تحميل بيانات جميع المخططات في العرض التقديمي من دفاتر العمل المصدر. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

يُرجع أو يعيّن التاريخ والوقت اللذين سيستبدلان محتوى حقول datetime. الوقت الافتراضي لإنشاء كائن Presentation هذا. قراءة/كتابة java.util.Date.

**القيمة المرجعة:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

يُرجع أو يعيّن التاريخ والوقت اللذين سيستبدلان محتوى datetime. الوقت الافتراضي لإنشاء كائن Presentation هذا. قراءة/كتابة java.util.Date.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

يُرجع مدير HeaderFooter للعرض التقديمي. قراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**القيمة المرجعة:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

يحصل على مدير الأذونات لهذا العرض التقديمي. قراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**القيمة المرجعة:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

يُرجع قائمة بجميع الشرائح المعرفة في العرض التقديمي. قراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

**القيمة المرجعة:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

يُرجع قائمة بجميع أقسام الشرائح المعرفة في العرض التقديمي. قراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

**القيمة المرجعة:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

يُرجع كائن حجم الشريحة. قراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

**القيمة المرجعة:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

يُرجع كائن حجم شريحة الملاحظات. قراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**القيمة المرجعة:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

يُرجع قائمة بجميع شرائح التخطيط المعرفة في العرض التقديمي. قراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية IMasterSlide.LayoutSlides.

**القيمة المرجعة:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

يُرجع قائمة بجميع الشرائح الرئيسية المعرفة في العرض التقديمي. قراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**القيمة المرجعة:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

يُرجع مدير الملاحظات الرئيسي. قراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**القيمة المرجعة:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

يُرجع مدير المخطوطات الرئيسي. قراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**القيمة المرجعة:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

يُرجع مدير الخطوط. قراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

**القيمة المرجعة:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

يُرجع نمط النص الافتراضي للأشكال. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**القيمة المرجعة:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

يُرجع مجموعة مؤلفي التعليقات. قراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**القيمة المرجعة:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

يُرجع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**القيمة المرجعة:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

يُرجع مجموعة جميع الصور في العرض التقديمي. قراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

**القيمة المرجعة:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

يُرجع مجموعة جميع ملفات الصوت المدمجة في العرض التقديمي. قراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**القيمة المرجعة:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

يُرجع مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. قراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

**القيمة المرجعة:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

يُرجع البيانات المخصصة للعرض التقديمي. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

يحصل على مشروع VBA مع وحدات ماكرو العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**القيمة المرجعة:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

يحصل على مشروع VBA مع وحدات ماكرو العرض التقديمي. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

يُرجع معلومات حول الصيغة التي تم تحميل العرض التقديمي منها. قراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**القيمة المرجعة:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

يُرجع السمة الرئيسية للعرض التقديمي. قراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

**القيمة المرجعة:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلًا إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض التقديمي (ليس في الشرائح الرئيسية، التخطيط، أو الملاحظات). قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**القيمة المرجعة:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

يحصل على خصائص العرض التقديمي العامة. قراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**القيمة المرجعة:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

يمثل رقم الشريحة الأولى في العرض التقديمي. قراءة/كتابة int.

**القيمة المرجعة:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

يمثل رقم الشريحة الأولى في العرض التقديمي. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

يُرجع جميع أجزاء البيانات المخصصة في العرض التقديمي. قراءة فقط ICustomXmlPart[].

**القيمة المرجعة:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

يُرجع مجموعة التوقيعات المستخدمة لتوقيع العرض التقديمي. قراءة فقط [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

يُرجع مجموعة تصنيفات الحساسية المطبقة على مستند العرض التقديمي. قراءة فقط [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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


**القيمة المرجعة:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

يحفظ جميع شرائح العرض التقديمي إلى ملف بالصّيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصّيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
يحفظ جميع شرائح العرض التقديمي في ملف بالصيغة المحددة ومع خيارات إضافية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف الذي تم إنشاؤه. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات الصيغة الإضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

يحفظ جميع شرائح العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات الصيغة الإضافية. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي في ملف بالصيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي في ملف بالصيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | المسار إلى الملف الذي تم إنشاؤه. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات الصيغة الإضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالصيغة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| format | int | صيغة البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات الصيغة الإضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات صيغة XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

يعيد كائنات IImage مصغرة للشرائح المحددة في العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تحجيم مخصص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| scaleX | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

يعيد كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تحجيم مخصص.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| scaleX | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي يتم بها تحجيم هذه الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

يعيد كائنات صورة مصغرة لجميع شرائح العرض التقديمي بحجم محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| imageSize | java.awt.Dimension | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

يعيد كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بحجم محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |
| slides | int[] | مصفوفة تحتوي على مواضع الشرائح، بدءاً من 1. |
| imageSize | java.awt.Dimension | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

يعيد شريحة (Slide) أو شريحة رئيسية (MasterSlide) أو شريحة تخطيط (LayoutSlide) بحسب المعرف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | long | معرف الشريحة. |

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - كائن IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات في جميع الأشكال القابلة للقبول في جميع الشرائح.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

يسلط الضوء على جميع مطابقة النص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تسليط الضوء على جميع حالات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تسليط الضوء عليه. |
| highlightColor | java.awt.Color | اللون الذي سيُستخدم لتسليط الضوء على النص. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يسلط الضوء على جميع مطابقة النص العيني باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تسليط الضوء على جميع حالات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد تسليط الضوء عليه. |
| highlightColor | java.awt.Color | اللون الذي سيُستخدم لتسليط الضوء على النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

يسلط الضوء على جميع مطابقة التعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تسليط الضوء على جميع حالات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل المراد تسليط الضوء عليها. |
| highlightColor | java.awt.Color | اللون الذي سيُستخدم لتسليط الضوء على النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
>      // استبدال جميع حالات 'the' المنفصلة بـ '***'
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
| newText | java.lang.String | السلسلة التي ستحل محل جميع مرات ظهور oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع مطابقة التعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حالات 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل المراد استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع مرات ظهور السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

يعيد تحميل بيانات جميع المخططات في العرض التقديمي من دفاتر العمل المصدر.

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
public abstract void refreshChartsData(boolean skipFailedCharts)
```

يعيد تحميل بيانات جميع المخططات في العرض التقديمي من دفاتر العمل المصدر.

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
| skipFailedCharts | boolean | يحدد ما إذا كانت عملية التحديث تستمر إذا فشل مخطط في التحديث. إذا كان true، يتم تخطي المخططات التي تتسبب في استثناء؛ وإلا يتم نشر الاستثناء. |