---
title: IPresentation
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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
| [getCurrentDateTime()](#getCurrentDateTime--) | إرجاع أو تعيين التاريخ والوقت الذي سيستبدل محتوى حقول تاريخ ووقت. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | إرجاع أو تعيين التاريخ والوقت الذي سيستبدل محتوى حقول تاريخ ووقت. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | إرجاع مدير HeaderFooter للعرض. |
| [getProtectionManager()](#getProtectionManager--) | الحصول على مدير الأذونات لهذا العرض. |
| [getSlides()](#getSlides--) | إرجاع قائمة بجميع الشرائح المعرفة في العرض. |
| [getSections()](#getSections--) | إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض. |
| [getSlideSize()](#getSlideSize--) | إرجاع كائن حجم الشريحة. |
| [getNotesSize()](#getNotesSize--) | إرجاع كائن حجم شريحة الملاحظات. |
| [getLayoutSlides()](#getLayoutSlides--) | إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض. |
| [getMasters()](#getMasters--) | إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | إرجاع مدير ملاحظات الرئيس. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | إرجاع مدير نسخة توزيع الرئيس. |
| [getFontsManager()](#getFontsManager--) | إرجاع مدير الخطوط. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | إرجاع نمط النص الافتراضي للأشكال. |
| [getCommentAuthors()](#getCommentAuthors--) | إرجاع مجموعة مؤلفي التعليقات. |
| [getDocumentProperties()](#getDocumentProperties--) | إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. |
| [getImages()](#getImages--) | إرجاع مجموعة جميع الصور في العرض. |
| [getAudios()](#getAudios--) | إرجاع مجموعة جميع ملفات الصوت المضمنة في العرض. |
| [getVideos()](#getVideos--) | إرجاع مجموعة جميع ملفات الفيديو المضمنة في العرض. |
| [getCustomData()](#getCustomData--) | إرجاع البيانات المخصصة للعرض. |
| [getVbaProject()](#getVbaProject--) | الحصول على مشروع VBA مع ماكروات العرض. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | الحصول على مشروع VBA مع ماكروات العرض. |
| [getSourceFormat()](#getSourceFormat--) | إرجاع معلومات عن الصيغة التي تم تحميل العرض منها. |
| [getMasterTheme()](#getMasterTheme--) | إرجاع السمة الرئيسية للعرض. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض (ليس في الشرائح الرئيسية أو تخطيط أو ملاحظات). |
| [getViewProperties()](#getViewProperties--) | الحصول على خصائص عرض العرض. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | يمثل رقم الشريحة الأولى في العرض. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | يمثل رقم الشريحة الأولى في العرض. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | إرجاع جميع أجزاء البيانات المخصصة في العرض. |
| [getDigitalSignatures()](#getDigitalSignatures--) | إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض. |
| [getSensitivityLabels()](#getSensitivityLabels--) | إرجاع مجموعة تصنيفات الحساسية المطبقة على مستند العرض. |
| [save(String fname, int format)](#save-java.lang.String-int-) | حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد ومع خيارات إضافية. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد ومع خيارات إضافية. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | حفظ جميع شرائح العرض إلى مجموعة من الملفات التي تمثل ترميز XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | إرجاع كائنات صورة مصغرة للشرائح المحددة للعرض. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض مع مقياس مخصص. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | إرجاع كائنات صورة مصغرة للشرائح المحددة للعرض مع مقياس مخصص. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | إرجاع كائنات صورة مصغرة لجميع شرائح العرض بالحجم المحدد. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | إرجاع كائنات صورة مصغرة للشرائح المحددة للعرض بالحجم المحدد. |
| [getSlideById(long id)](#getSlideById-long-) | إرجاع شريحة، شريحة رئيسية أو شريحة تخطيط بحسب المعرف. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دمج القيم ذات التنسيق المماثل في جميع الفقرات في جميع الأشكال القابلة للقبول في جميع الشرائح. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | إبراز جميع المطابقات للنص النموذجي باللون المحدد. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | إبراز جميع المطابقات للنص النموذجي باللون المحدد. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | إبراز جميع المطابقات للتعبير النمطي باللون المحدد. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | استبدال جميع حالات النص المحدد بنص آخر محدد. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | استبدال جميع المطابقات للتعبير النمطي بالسلسلة المحددة. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

إرجاع أو تعيين التاريخ والوقت الذي سيستبدل محتوى حقول تاريخ ووقت. الوقت الافتراضي هو وقت إنشاء كائن Presentation هذا. قابل للقراءة والكتابة java.util.Date.

**الإرجاع:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

إرجاع أو تعيين التاريخ والوقت الذي سيستبدل محتوى حقول تاريخ ووقت. الوقت الافتراضي هو وقت إنشاء كائن Presentation هذا. قابل للقراءة والكتابة java.util.Date.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

إرجاع مدير HeaderFooter للعرض. للقراءة فقط [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**الإرجاع:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

الحصول على مدير الأذونات لهذا العرض. للقراءة فقط [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**الإرجاع:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

إرجاع قائمة بجميع الشرائح المعرفة في العرض. للقراءة فقط [ISlideCollection](../../com.aspose.slides/islidecollection).

**الإرجاع:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

إرجاع قائمة بجميع أقسام الشرائح المعرفة في العرض. للقراءة فقط [ISectionCollection](../../com.aspose.slides/isectioncollection).

**الإرجاع:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

إرجاع كائن حجم الشريحة. للقراءة فقط [ISlideSize](../../com.aspose.slides/islidesize).

**الإرجاع:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

إرجاع كائن حجم شريحة الملاحظات. للقراءة فقط [INotesSize](../../com.aspose.slides/inotessize).

**الإرجاع:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

إرجاع قائمة بجميع شرائح التخطيط المعرفة في العرض. للقراءة فقط [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

يمكنك الوصول إلى واجهة برمجة تطبيقات بديلة لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط باستخدام الخاصية IMasterSlide.LayoutSlides.

**الإرجاع:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

إرجاع قائمة بجميع الشرائح الرئيسية المعرفة في العرض. للقراءة فقط [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**الإرجاع:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

إرجاع مدير ملاحظات الرئيس. للقراءة فقط [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**الإرجاع:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

إرجاع مدير نسخة توزيع الرئيس. للقراءة فقط [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**الإرجاع:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

إرجاع مدير الخطوط. للقراءة فقط [IFontsManager](../../com.aspose.slides/ifontsmanager).

**الإرجاع:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

إرجاع نمط النص الافتراضي للأشكال. للقراءة فقط [ITextStyle](../../com.aspose.slides/itextstyle).

**الإرجاع:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

إرجاع مجموعة مؤلفي التعليقات. للقراءة فقط [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**الإرجاع:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

إرجاع كائن DocumentProperties الذي يحتوي على خصائص المستند القياسية والمخصصة. للقراءة فقط [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**الإرجاع:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

إرجاع مجموعة جميع الصور في العرض. للقراءة فقط [IImageCollection](../../com.aspose.slides/iimagecollection).

**الإرجاع:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

إرجاع مجموعة جميع ملفات الصوت المضمنة في العرض. للقراءة فقط [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**الإرجاع:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

إرجاع مجموعة جميع ملفات الفيديو المضمنة في العرض. للقراءة فقط [IVideoCollection](../../com.aspose.slides/ivideocollection).

**الإرجاع:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

إرجاع البيانات المخصصة للعرض. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

الحصول على مشروع VBA مع ماكروات العرض. قابل للقراءة والكتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**الإرجاع:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

الحصول على مشروع VBA مع ماكروات العرض. قابل للقراءة والكتابة [IVbaProject](../../com.aspose.slides/ivbaproject).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

إرجاع معلومات عن الصيغة التي تم تحميل العرض منها. للقراءة فقط [SourceFormat](../../com.aspose.slides/sourceformat).

**الإرجاع:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

إرجاع السمة الرئيسية للعرض. للقراءة فقط [IMasterTheme](../../com.aspose.slides/imastertheme).

**الإرجاع:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

يوفر وصولًا سهلاً إلى جميع الروابط التشعبية الموجودة في جميع شرائح العرض (ليس في الشرائح الرئيسية أو تخطيط أو ملاحظات). للقراءة فقط [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**الإرجاع:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

الحصول على خصائص عرض العرض. للقراءة فقط [IViewProperties](../../com.aspose.slides/iviewproperties).

**الإرجاع:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

يمثل رقم الشريحة الأولى في العرض. قابل للقراءة والكتابة int.

**الإرجاع:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

يمثل رقم الشريحة الأولى في العرض. قابل للقراءة والكتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

إرجاع جميع أجزاء البيانات المخصصة في العرض. للقراءة فقط ICustomXmlPart[].

**الإرجاع:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

إرجاع مجموعة التوقيعات المستخدمة لتوقيع العرض. للقراءة فقط [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

إرجاع مجموعة تصنيفات الحساسية المطبقة على مستند العرض. للقراءة فقط [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print the applied labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Add the new label
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Get the sensitivity label Id from the policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Get the Azure AD site identifier from the policy
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| format | int | تنسيق البيانات المُصدرة. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | تنسيق البيانات المُصدرة. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

حفظ جميع شرائح العرض إلى ملف بالتنسيق المحدد ومع خيارات إضافية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| format | int | تنسيق البيانات المُصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

حفظ جميع شرائح العرض إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| format | int | تنسيق البيانات المُصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المُصدرة. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

حفظ الشرائح المحددة من العرض إلى ملف بالتنسيق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| fname | java.lang.String | مسار الملف الذي سيتم إنشاؤه. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المُصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المُصدرة. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

حفظ الشرائح المحددة من العرض إلى تدفق بالتنسيق المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الإخراج. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| format | int | تنسيق البيانات المُصدرة. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | خيارات تنسيق إضافية. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

حفظ جميع شرائح العرض إلى مجموعة من الملفات التي تمثل ترميز XAML.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | خيارات تنسيق XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

إرجاع كائنات صورة مصغرة لجميع شرائح العرض.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

إرجاع كائنات IImage مصغرة للشرائح المحددة للعرض.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

إرجاع كائنات صورة مصغرة لجميع شرائح العرض مع مقياس مخصص.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |
| scaleX | float | القيمة التي سيتم بمقتضاها قياس الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي سيتم بمقتضاها قياس الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

إرجاع كائنات صورة مصغرة للشرائح المحددة للعرض مع مقياس مخصص.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| scaleX | float | القيمة التي سيتم بمقتضاها قياس الصورة المصغرة في اتجاه المحور السيني. |
| scaleY | float | القيمة التي سيتم بمقتضاها قياس الصورة المصغرة في اتجاه المحور الصادي. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

إرجاع كائنات صورة مصغرة لجميع شرائح العرض بالحجم المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

إرجاع كائنات صورة مصغرة للشرائح المحددة للعرض بالحجم المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التقديم. |
| slides | int[] | مصفوفة بمواقع الشرائح، تبدأ من 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم الصورة المراد إنشاؤها. |

**الإرجاع:**
com.aspose.slides.IImage[] - كائنات IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

إرجاع شريحة، شريحة رئيسية أو شريحة تخطيط بحسب المعرف.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| id | long | معرف الشريحة. |

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - كائن IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دمج القيم ذات التنسيق المماثل في جميع الفقرات في جميع الأشكال القابلة للقبول في جميع الشرائح.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

إبراز جميع المطابقات للنص النموذجي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // إبراز جميع حدوث كلمة 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إبرازَه. |
| highlightColor | java.lang.Integer | اللون المستخدم لإبراز النص. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

إبراز جميع المطابقات للنص النموذجي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // إبراز جميع حدوث كلمة 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إبرازَه. |
| highlightColor | java.lang.Integer | اللون المستخدم لإبراز النص. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

إبراز جميع المطابقات للتعبير النمطي باللون المحدد.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // إبراز جميع حدوث كلمة 'the' المنفصلة
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي سيتم إبرازها. |
| highlightColor | java.lang.Integer | اللون المستخدم لإبراز النص. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

استبدال جميع حالات النص المحدد بنص آخر محدد.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حدوث كلمة 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| oldText | java.lang.String | السلسلة التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | خيارات بحث النص [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

استبدال جميع المطابقات للتعبير النمطي بالسلسلة المحددة.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // استبدال جميع حدوث كلمة 'the' المنفصلة بـ '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| regex | java.util.regex.Pattern | التعبير النمطي java.util.regex.Pattern للحصول على السلاسل التي سيتم استبدالها. |
| newText | java.lang.String | السلسلة التي ستحل محل جميع حالات السلاسل التي سيتم استبدالها. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | كائن الاستدعاء لتلقي نتائج البحث [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |