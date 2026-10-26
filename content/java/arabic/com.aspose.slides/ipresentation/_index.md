---
title: IPresentation
second_title: مرجع API Aspose.Slides للغة Java
description: مستند العرض
type: docs
url: /ar/com.aspose.slides/ipresentation/
---
**جميع الواجهات المنفذة:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

مستند العرض
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | إرجاع أو ضبط التاريخ والوقت الذي سيستبدل محتوى حقول datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | إرجاع أو ضبط التاريخ والوقت الذي سيستبدل محتوى حقول datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للعرض. |
| [getProtectionManager()](#getProtectionManager--) | إرجاع مدير الأذونات لهذا العرض. |
| [getSlides()](#getSlides--) | إرجاع قائمة بجميع الشرائح المعرفة في العرض. |
| [getSections()](#getSections--) | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض. |
| [getSlideSize()](#getSlideSize--) | إرجاع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | إرجاع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض. |
| [getMasters()](#getMasters--) | إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | إرجاع مدير الملاحظات الرئيسي. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | إرجاع مدير النسخة المطبوعة الرئيسية. |
| [getFontsManager()](#getFontsManager--) | إرجاع مدير الخطوط. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | إرجاع نمط النص الافتراضي للأشكال. |
| [getCommentAuthors()](#getCommentAuthors--) | إرجاع مجموعة مؤلفي التعليقات. |
| [getDocumentProperties()](#getDocumentProperties--) | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. |
| [getImages()](#getImages--) | إرجاع مجموعة جميع الصور في العرض. |
| [getAudios()](#getAudios--) | إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض. |
| [getVideos()](#getVideos--) | إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض. |
| [getCustomData()](#getCustomData--) | إرجاع البيانات المخصصة للعرض. |
| [getVbaProject()](#getVbaProject--) | إرجاع مشروع VBA مع ماكروهات العرض. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | إرجاع مشروع VBA مع ماكروهات العرض. |
| [getSourceFormat()](#getSourceFormat--) | إرجاع معلومات حول الصيغة التي تم تحميل العرض منها. |
| [getMasterTheme()](#getMasterTheme--) | إرجاع السمة الرئيسية للعرض. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | توفير وصول سهل إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض (بدون الماستر، التخطيط، شرائح الملاحظات). |
| [getViewProperties()](#getViewProperties--) | إرجاع خصائص العرض العامة. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | تمثيل رقم الشريحة الأولى في العرض. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | تمثيل رقم الشريحة الأولى في العرض. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | إرجاع جميع أجزاء البيانات المخصصة في العرض. |
| [getDigitalSignatures()](#getDigitalSignatures--) | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض. |
| [getSensitivityLabels()](#getSensitivityLabels--) | إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض. |
| [save(String fname, int format)](#save-java.lang.String-int-) | حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد مع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد مع خيارات إضافية. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | حفظ جميع شرائح العرض إلى مجموعة من الملفات التي تمثل تنسيق XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | إرجاع كائنات صورة مصغرة للشرائح جميعها في العرض. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | إرجاع كائنات IImage مصغرة للشرائح المحددة في العرض. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | إ رجاع كائنات صورة مصغرة لجميع شرائح العرض مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | إرجاع كائنات صورة مصغرة للشرائح المحددة في العرض مع تحجيم مخصص. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض بالحجم المحدد. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | إرجاع كائنات صورة مصغرة للشرائح المحددة في العرض بالحجم المحدد. |
| [getSlideById(long id)](#getSlideById-long-) | إرجاع شريحة Slide أو MasterSlide أو LayoutSlide حسب المعرف. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دمج المقاطع ذات التنسيق المماثل في جميع الفقرات داخل جميع الأشكال القابلة للمعالجة في جميع الشرائح. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمييز جميع التطابقات للنص النموذجي باللون المحدد. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للنص النموذجي باللون المحدد. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمييز جميع التطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | استبدال جميع حدوث النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | استبدال جميع التطابقات للتعبير النمطي بالسلسلة المحددة. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

إرجاع أو ضبط التاريخ والوقت الذي سيستبدل محتوى حقول datetime. الوقت الافتراضي هو وقت إنشاء كائن Presentation هذا. قراءة/كتابة java.util.Date.

**الإرجاع:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

إرجاع أو ضبط التاريخ والوقت الذي سيستبدل محتوى datetime. الوقت الافتراضي هو وقت إنشاء كائن Presentation هذا. قراءة/كتابة java.util.Date.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter للعرض. قراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**الإرجاع:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

إرجاع مدير الأذونات لهذا العرض. قراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**الإرجاع:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

إرجاع قائمة بجميع الشرائح المعرفة في العرض. قراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

**الإرجاع:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض. قراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

**الإرجاع:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

إرجاع كائن حجم الشريحة. قراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

**الإرجاع:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

إرجاع كائن حجم شريحة الملاحظات. قراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**الإرجاع:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض. قراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

يمكنك الوصول إلى API بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية IMasterSlide.LayoutSlides.

**الإرجاع:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض. قراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**الإرجاع:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

إرجاع مدير الملاحظات الرئيسي. قراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**الإرجاع:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

إرجاع مدير النسخة المطبوعة الرئيسية. قراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**الإرجاع:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

إرجاع مدير الخطوط. قراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

**الإرجاع:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

إرجاع نمط النص الافتراضي للأشكال. قراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

إرجاع مجموعة مؤلفي التعليقات. قراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**الإرجاع:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. قراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**الإرجاع:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

إرجاع مجموعة جميع الصور في العرض. قراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

**الإرجاع:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

إرجاع مجموعة جميع ملفات الصوت المدمجة في العرض. قراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**الإرجاع:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

إرجاع مجموعة جميع ملفات الفيديو المدمجة في العرض. قراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

**الإرجاع:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

إرجاع البيانات المخصصة للعرض. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

إرجاع مشروع VBA مع ماكروهات العرض. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

إرجاع مشروع VBA مع ماكروهات العرض. قراءة/كتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

إرجاع معلومات حول الصيغة التي تم تحميل العرض منها. قراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**الإرجاع:**
int
### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

إرجاع السمة الرئيسية للعرض. قراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

**الإرجاع:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

توفير وصول سهل إلى جميع الروابط الفائقة الموجودة في جميع شرائح العرض (بدون الماستر، التخطيط، شرائح الملاحظات). قراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

إرجاع خصائص العرض العامة. قراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**الإرجاع:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

تمثيل رقم الشريحة الأولى في العرض. قراءة/كتابة int.

**الإرجاع:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

تمثيل رقم الشريحة الأولى في العرض. قراءة/كتابة int.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

إرجاع جميع أجزاء البيانات المخصصة في العرض. قراءة فقط ICustomXmlPart[].

**الإرجاع:**
com.aspose.slides.ICustomXmlPart[]
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض. قراءة فقط [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**الإرجاع:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

إرجاع مجموعة تسميات الحساسية المطبقة على مستند العرض. قراءة فقط [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // الحصول على معرف علامة الحساسية من السياسة
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
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| format | int | صيغة البيانات المصدرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | صيغة البيانات المصدرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد ومع خيارات إضافية.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |

| format | int | تنسيق البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات التنسيق الإضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

يحفظ جميع الشرائح في العرض التقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | تنسيق البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات التنسيق الإضافية. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

يحفظ الشرائح المحددة في العرض التقديمي إلى ملف بالصيغة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المصدرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة في العرض التقديمي إلى ملف بالصيغة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف المُنشأ. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات التنسيق الإضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

يحفظ الشرائح المحددة في العرض التقديمي إلى تدفق بالصيغة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المصدرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

يحفظ الشرائح المحددة في العرض التقديمي إلى تدفق بالصيغة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات التنسيق الإضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

يحفظ جميع الشرائح في العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML.

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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات تنسيق XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

يرجع كائنات IImage مصغرة للشرائح المحددة في العرض التقديمي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي مع تعديل مخصص للقياس.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| scaleX | float | القيمة التي يتم من خلالها تحجيم هذه الصورة المصغرة في اتجاه محور X. |
| scaleY | float | القيمة التي يتم من خلالها تحجيم هذه الصورة المصغرة في اتجاه محور Y. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي مع تعديل مخصص للقياس.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| scaleX | float | القيمة التي يتم من خلالها تحجيم هذه الصورة المصغرة في اتجاه محور X. |
| scaleY | float | القيمة التي يتم من خلالها تحجيم هذه الصورة المصغرة في اتجاه محور Y. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

يرجع كائنات صورة مصغرة لجميع شرائح العرض التقديمي بحجم محدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

يرجع كائنات صورة مصغرة للشرائح المحددة في العرض التقديمي بحجم محدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| imageSize | java.awt.Dimension | حجم الصورة التي سيتم إنشاؤها. |

**القيم المرجعة:**
com.aspose.slides.IImage[] - كائنات IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

يعيد شريحة أو شريحة رئيسية أو شريحة تخطيط حسب المعرّف.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | معرّف الشريحة. |

**القيم المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - كائن IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

يجمع المقاطع ذات التنسيق المتطابق في جميع الفقرات داخل جميع الأشكال القابلة للمعالجة في جميع الشرائح.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

يسلط الضوء على جميع التطابقات للنص النموذجي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تمييز جميع تكرارات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المستخدم لتسليط الضوء على النص. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

يسلط الضوء على جميع التطابقات للنص النموذجي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تمييز جميع تكرارات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | النص المراد تمييزه. |
| highlightColor | java.awt.Color | اللون المستخدم لتسليط الضوء على النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد الاتصال لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

يسلط الضوء على جميع التطابقات للتعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // تمييز جميع تكرارات 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل المراد تمييزها. |
| highlightColor | java.awt.Color | اللون المستخدم لتسليط الضوء على النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد الاتصال لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

يستبدل جميع تكرارات النص المحدد بنص آخر محدد.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع تكرارات 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة المراد استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع تكرارات oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات البحث النصي [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد الاتصال لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

يستبدل جميع التطابقات للتعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع تكرارات 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل المراد استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع تكرارات السلاسل المراد استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن رد الاتصال لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |