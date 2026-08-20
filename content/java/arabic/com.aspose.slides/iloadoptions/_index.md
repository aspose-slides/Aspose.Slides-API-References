---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
url: /ar/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | إرجاع أو تعيين تنسيق العرض التقديمي للتحميل. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | إرجاع أو تعيين تنسيق العرض التقديمي للتحميل. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | إرجاع أو تعيين الخط العادي المستخدم في حالة عدم العثور على الخط الأصلي. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | إرجاع أو تعيين الخط العادي المستخدم في حالة عدم العثور على الخط الأصلي. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | إرجاع أو تعيين خط الرمز المستخدم في حالة عدم العثور على الخط الأصلي. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | إرجاع أو تعيين خط الرمز المستخدم في حالة عدم العثور على الخط الأصلي. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | إرجاع أو تعيين الخط الآسيوي المستخدم في حالة عدم العثور على الخط الأصلي. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | إرجاع أو تعيين الخط الآسيوي المستخدم في حالة عدم العثور على الخط الأصلي. |
| [getPassword()](#getPassword--) | إرجاع أو تعيين كلمة المرور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | إرجاع أو تعيين كلمة المرور. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [getWarningCallback()](#getWarningCallback--) | إرجاع أو تعيين كائن يستقبل التحذيرات ويقرر ما إذا كان سيتم متابعة عملية التحميل أو إلغاؤها. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | إرجاع أو تعيين كائن يستقبل التحذيرات ويقرر ما إذا كان سيتم متابعة عملية التحميل أو إلغاؤها. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات الخاصة بـ BLOBs في الذاكرة. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات الخاصة بـ BLOBs في الذاكرة. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | يحدد مصادر الخطوط الخارجية المستخدمة في العرض التقديمي. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | يحدد مصادر الخطوط الخارجية المستخدمة في العرض التقديمي. |
| [getInterruptionToken()](#getInterruptionToken--) | الرمز لمراقبة طلبات الإيقاف. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | الرمز لمراقبة طلبات الإيقاف. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الحسابية. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الحسابية. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | إرجاع أو تعيين اللغة الافتراضية لنص العرض التقديمي. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | إرجاع أو تعيين اللغة الافتراضية لنص العرض التقديمي. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمّنة أثناء تحميل العرض التقديمي. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمّنة أثناء تحميل العرض التقديمي. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

إرجاع أو تعيين تنسيق العرض التقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**الإرجاع:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

إرجاع أو تعيين تنسيق العرض التقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

إرجاع أو تعيين الخط العادي المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**الإرجاع:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

إرجاع أو تعيين الخط العادي المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

إرجاع أو تعيين خط الرمز المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**الإرجاع:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

إرجاع أو تعيين خط الرمز المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

إرجاع أو تعيين الخط الآسيوي المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**الإرجاع:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

إرجاع أو تعيين الخط الآسيوي المستخدم في حالة عدم العثور على الخط الأصلي. قراءة-كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

إرجاع أو تعيين كلمة المرور. قراءة-كتابة String.

القيمة: كلمة المرور.

**الإرجاع:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

إرجاع أو تعيين كلمة المرور. قراءة-كتابة String.

القيمة: كلمة المرور.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. قيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر وتجاهل كلمة المرور. قيمة false تعني أن يتم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن خصائص المستند لا يمكن تحميلها وسيُرمى استثناء. قراءة-كتابة boolean.

**الإرجاع:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. قيمة true تعني أنه يجب تحميل خصائص المستند فقط من ملف عرض مشفر وتجاهل كلمة المرور. قيمة false تعني أن يتم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت قيمة الخاصية true فإن خصائص المستند لا يمكن تحميلها وسيُرمى استثناء. قراءة-كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

إرجاع أو تعيين كائن يستقبل التحذيرات ويقرر ما إذا كان سيتم متابعة عملية التحميل أو إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**الإرجاع:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

إرجاع أو تعيين كائن يستقبل التحذيرات ويقرر ما إذا كان سيتم متابعة عملية التحميل أو إلغاؤها. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات الخاصة بـ BLOBs في الذاكرة. هذه الخيارات تهدف إلى ضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة معينة أو متطلبات محددة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض التقديمي نفسه.

**الإرجاع:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات الخاصة بـ BLOBs في الذاكرة. هذه الخيارات تهدف إلى ضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة معينة أو متطلبات محددة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض التقديمي نفسه.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض التقديمي. هذه الخطوط متاحة للعرض طوال فترة حياته ولا تُشارك مع عروض تقديمية أخرى.

**الإرجاع:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض التقديمي. هذه الخطوط متاحة للعرض طوال فترة حياته ولا تُشارك مع عروض تقديمية أخرى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

الرمز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر كائن [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم إيقافها عبر استدعاء طريقة [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) الخاصة بـ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**الإرجاع:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

الرمز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر كائن [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم إيقافها عبر استدعاء طريقة [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) الخاصة بـ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**الإرجاع:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

إرجاع أو تعيين واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الحسابية.

**الإرجاع:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

يمثل الخيارات التي يمكن استخدامها لتحديد سلوك إضافي للجداول الحسابية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

إرجاع أو تعيين اللغة الافتراضية لنص العرض التقديمي. قراءة/كتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد الثقافة النصية الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // إضافة شكل مستطيل جديد مع النص
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
public abstract void setDefaultTextLanguage(String value)
```

إرجاع أو تعيين اللغة الافتراضية لنص العرض التقديمي. قراءة/كتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد ثقافة النص الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // إضافة شكل مستطيل جديد مع النص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // التحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمّنة أثناء تحميل العرض التقديمي.

أنواع الكائنات الثنائية المضمّنة:

 *  
 *  
 *  

قراءة-كتابة  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

القيمة الافتراضية هي **false** .

**الإرجاع:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمّنة أثناء تحميل العرض التقديمي.

أنواع الكائنات الثنائية المضمّنة:

 *  
 *  
 *  

قراءة-كتابة  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

القيمة الافتراضية هي **false** .

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |