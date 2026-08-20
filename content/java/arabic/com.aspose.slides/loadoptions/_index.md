---
title: LoadOptions
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يسمح بتحديد خيارات إضافية مثل التنسيق أو الخط الافتراضي عند تحميل عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/loadoptions/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.

## المنشئات

| Constructor | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | ينشئ خيارات تحميل افتراضية جديدة. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | ينشئ خيارات تحميل جديدة. |

## الطرق

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | إرجاع أو تعيين تنسيق عرض تقديمي للتحميل. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | إرجاع أو تعيين تنسيق عرض تقديمي للتحميل. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | إرجاع أو تعيين الخط العادي المستخدم في حال عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | إرجاع أو تعيين الخط العادي المستخدم في حال عدم العثور على الخط المصدر. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | إرجاع أو تعيين خط الرموز المستخدم في حال عدم العثور على الخط المصدر. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | إرجاع أو تعيين خط الرموز المستخدم في حال عدم العثور على الخط المصدر. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | إرجاع أو تعيين الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | إرجاع أو تعيين الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. |
| [getPassword()](#getPassword--) | إحضار أو تعيين كلمة المرور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | إحضار أو تعيين كلمة المرور. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [getWarningCallback()](#getWarningCallback--) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا ستستمر عملية التحميل أو ستُلغى. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا ستستمر عملية التحميل أو ستُلغى. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لبايتات BLOBs في الذاكرة. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لبايتات BLOBs في الذاكرة. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | يحدد المصادر للخطوط الخارجية المستخدمة في العرض. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | يحدد المصادر للخطوط الخارجية المستخدمة في العرض. |
| [getInterruptionToken()](#getInterruptionToken--) | الرمز لمراقبة طلبات الانقطاع. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | الرمز لمراقبة طلبات الانقطاع. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | إحضار خيارات للجداول الحسابية. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | إحضار خيارات للجداول الحسابية. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | إرجاع أو تعيين اللغة الافتراضية لنص العرض. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | إرجاع أو تعيين اللغة الافتراضية لنص العرض. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

ينشئ خيارات تحميل افتراضية جديدة.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

ينشئ خيارات تحميل جديدة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadFormat | int | تنسيق عرض تقديمي للتحميل. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

إرجاع أو تعيين تنسيق عرض تقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**الإرجاع:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

إرجاع أو تعيين تنسيق عرض تقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

إرجاع أو تعيين الخط العادي المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // استخدم خيارات التحميل لتحديد الخط العادي والآسيوي الافتراضي
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // إنشاء صورة مصغرة للشريحة
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // إنشاء PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // إنشاء XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

إرجاع أو تعيين الخط العادي المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // استخدم خيارات التحميل لتحديد الخط العادي والآسيوي الافتراضي
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // إنشاء صورة مصغرة للشريحة
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // إنشاء PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // إنشاء XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

إرجاع أو تعيين خط الرموز المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

إرجاع أو تعيين خط الرموز المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

إرجاع أو تعيين الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

إرجاع أو تعيين الخط الآسيوي المستخدم في حال عدم العثور على الخط المصدر. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

إحضار أو تعيين كلمة المرور. قراءة/كتابة String.

--------------------

> ```
> يوضح المثال التالي كيفية فتح عرض PowerPoint محمي بكلمة مرور.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // العمل مع العرض المفكوك
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


القيمة: كلمة المرور.

**الإرجاع:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

إحضار أو تعيين كلمة المرور. قراءة/كتابة String.

--------------------

> ```
> يوضح المثال التالي كيفية فتح عرض PowerPoint محمي بكلمة مرور.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // العمل مع العرض المفكوك
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


القيمة: كلمة المرور.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن يتم تحميل خصائص المستند فقط من ملف عرض مشفر ويتجاهل كلمة المرور. القيمة false تعني أن يتم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فستُهمل قيمة الخاصية دائمًا. إذا كانت خصائص المستند لملف مشفر غير عامة وكانت قيمة الخاصية true فلن يمكن تحميل خصائص المستند وسيتم رمي استثناء. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن يتم تحميل خصائص المستند فقط من ملف عرض مشفر ويتجاهل كلمة المرور. القيمة false تعني أن يتم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فستُهمل قيمة الخاصية دائمًا. إذا كانت خصائص المستند لملف مشفر غير عامة وكانت قيمة الخاصية true فلن يمكن تحميل خصائص المستند وسيتم رمي استثناء. قراءة/كتابة boolean.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا ستستمر عملية التحميل أو ستُلغى. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**الإرجاع:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

إرجاع أو تعيين كائن يتلقى التحذيرات ويقرر ما إذا ستستمر عملية التحميل أو ستُلغى. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لبايتات BLOBs في الذاكرة. هذه الخيارات تهدف إلى ضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض نفسه.

**الإرجاع:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لبايتات BLOBs في الذاكرة. هذه الخيارات تهدف إلى ضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض نفسه.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض. هذه الخطوط متاحة للعرض طوال مدة عمره ولا يتم مشاركتها مع عروض أخرى.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // العمل مع العرض
>  // يتوفر الخطان CustomFont1 و CustomFont2 بالإضافة إلى الخطوط من مجلدات assets\fonts و global\fonts ومجلداتها الفرعية للعرض
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**الإرجاع:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض. هذه الخطوط متاحة للعرض طوال مدة عمره ولا يتم مشاركتها مع عروض أخرى.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // العمل مع العرض
>  // CustomFont1, CustomFont2 بالإضافة إلى الخطوط من مجلدات assets\fonts و global\fonts ومجلداتها الفرعية متاحة للعرض
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

الرمز لمراقبة طلبات الانقطاع.

--------------------

هذا الرمز يدير كامل عمر مثيل [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، ستُقاطع عبر استدعاء طريقة [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) للـ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**الإرجاع:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

الرمز لمراقبة طلبات الانقطاع.

--------------------

هذا الرمز يدير كامل عمر مثيل [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، ستُقاطع عبر استدعاء طريقة [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) للـ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**الإرجاع:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

إحضار خيارات للجداول الحسابية. على سبيل المثال، تؤثر هذه الخيارات على حساب الصيغ للرسوم البيانية.

**الإرجاع:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

إحضار خيارات للجداول الحسابية. على سبيل المثال، تؤثر هذه الخيارات على حساب الصيغ للرسوم البيانية.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

إرجاع أو تعيين اللغة الافتراضية لنص العرض. قراءة/كتابة String.

--------------------

> ```
> مثال:
>   
>  // استخدم خيارات التحميل لتحديد ثقافة النص الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // إضافة شكل مستطيل جديد مع نص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // تحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

إرجاع أو تعيين اللغة الافتراضية لنص العرض. قراءة/كتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد ثقافة النص الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // إضافة شكل مستطيل جديد مع نص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // تحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض.

أنواع الكائنات الثنائية المدمجة:

قراءة/كتابة boolean.

--------------------

```
> يوضح المثال التالي كيفية تحميل العرض دون أي كائنات ثنائية مدمجة.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

الافتراضي هو **false**.

**الإرجاع:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المدمجة أثناء تحميل العرض.

أنواع الكائنات الثنائية المدمجة:

قراءة/كتابة boolean.

--------------------

```
> يوضح المثال التالي كيفية تحميل العرض دون أي كائنات ثنائية مدمجة.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

الافتراضي هو **false**.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |