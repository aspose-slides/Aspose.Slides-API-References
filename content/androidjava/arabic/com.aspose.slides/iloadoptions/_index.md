---
title: ILoadOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يسمح بتحديد خيارات إضافية مثل التنسيق أو الخط الافتراضي عند تحميل عرض تقديمي.
type: docs
url: /ar/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | تُرجِع أو تُعيّن تنسيق العرض التقديمي للتحميل. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | تُرجِع أو تُعيّن تنسيق العرض التقديمي للتحميل. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | تُرجِع أو تُعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | تُرجِع أو تُعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | تُرجِع أو تُعيّن خط الرمز المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | تُرجِع أو تُعيّن خط الرمز المستخدم في حالة عدم العثور على الخط المصدر. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | تُرجِع أو تُعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | تُرجِع أو تُعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. |
| [getPassword()](#getPassword--) | تُحصل أو تُعيّن كلمة المرور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تُحصل أو تُعيّن كلمة المرور. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. |
| [getWarningCallback()](#getWarningCallback--) | تُرجِع أو تُعيّن كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُلغى. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | تُرجِع أو تُعيّن كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُلغى. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | تمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | تمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | يحدد مصادر الخطوط الخارجية المستخدمة في العرض. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | يحدد مصادر الخطوط الخارجية المستخدمة في العرض. |
| [getInterruptionToken()](#getInterruptionToken--) | الرمز المميز لمراقبة طلبات الإيقاف. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | الرمز المميز لمراقبة طلبات الإيقاف. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | تُرجِع أو تُعيّن واجهة رد الاتصال التي تدير تحميل الموارد الخارجية. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | تُرجِع أو تُعيّن واجهة رد الاتصال التي تدير تحميل الموارد الخارجية. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | تمثل الخيارات التي يمكن استخدامها لتحديد سلوك جداول البيانات الإضافية. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | تمثل الخيارات التي يمكن استخدامها لتحديد سلوك جداول البيانات الإضافية. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | تُرجِع أو تُعيّن اللغة الافتراضية لنص العرض. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | تُرجِع أو تُعيّن اللغة الافتراضية لنص العرض. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | يحدد ما إذا كانت Aspose.Slides ستحذف جميع الكائنات الثنائية المضمَّنة أثناء تحميل العرض. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | يحدد ما إذا كانت Aspose.Slides ستحذف جميع الكائنات الثنائية المضمَّنة أثناء تحميل العرض. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

تُرجِع أو تُعيّن تنسيق العرض التقديمي للتحميل. قابل للقراءة والكتابة [LoadFormat](../../com.aspose.slides/loadformat).

**القيمة المرجعة:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

تُرجِع أو تُعيّن تنسيق العرض التقديمي للتحميل. قابل للقراءة والكتابة [LoadFormat](../../com.aspose.slides/loadformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

تُرجِع أو تُعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

تُرجِع أو تُعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

تُرجِع أو تُعيّن خط الرمز المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

تُرجِع أو تُعيّن خط الرمز المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

تُرجِع أو تُعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**القيمة المرجعة:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

تُرجِع أو تُعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. قابل للقراءة والكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

تُحصل أو تُعيّن كلمة المرور. قابل للقراءة والكتابة String.

القيمة: كلمة المرور.

**القيمة المرجعة:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

تُحصل أو تُعيّن كلمة المرور. قابل للقراءة والكتابة String.

القيمة: كلمة المرور.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن خصائص المستند فقط يجب تحميلها من ملف عرض مشفر ويُتجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت القيمة true فإن خصائص المستند لا يمكن تحميلها وسيتم رمي استثناء. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن خصائص المستند فقط يجب تحميلها من ملف عرض مشفر ويُتجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت القيمة true فإن خصائص المستند لا يمكن تحميلها وسيتم رمي استثناء. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

تُرجِع أو تُعيّن كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُلغى. قابل للقراءة والكتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**القيمة المرجعة:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

تُرجِع أو تُعيّن كائنًا يستقبل التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو تُلغى. قابل للقراءة والكتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

تمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تم تصميم هذه الخيارات لتحقيق أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض نفسه.

**القيمة المرجعة:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

تمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى لعدد بايتات BLOBs في الذاكرة. تم تصميم هذه الخيارات لتحقيق أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي يمكن أن يكون BLOB صوتًا أو فيديو أو العرض نفسه.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |
### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض. هذه الخطوط متاحة للعرض طوال مدة حياته ولا تُشارك مع عروض أخرى.

**القيمة المرجعة:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

يحدد مصادر الخطوط الخارجية المستخدمة في العرض. هذه الخطوط متاحة للعرض طوال مدة حياته ولا تُشارك مع عروض أخرى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |
### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

الرمز المميز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر مثال [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، ستتوقف عبر استدعاء طريقة [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) الخاصة بـ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**القيمة المرجعة:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

الرمز المميز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر مثال [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، ستتوقف عبر استدعاء طريقة [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) الخاصة بـ [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |
### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

تُرجِع أو تُعيّن واجهة رد الاتصال التي تدير تحميل الموارد الخارجية. قابل للقراءة والكتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**القيمة المرجعة:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

تُرجِع أو تُعيّن واجهة رد الاتصال التي تدير تحميل الموارد الخارجية. قابل للقراءة والكتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |
### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

تمثل الخيارات التي يمكن استخدامها لتحديد سلوك جداول البيانات الإضافية.

**القيمة المرجعة:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

تمثل الخيارات التي يمكن استخدامها لتحديد سلوك جداول البيانات الإضافية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |
### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

تُرجِع أو تُعيّن اللغة الافتراضية لنص العرض. قابل للقراءة والكتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد ثقافة النص الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // أضف شكل مستطيل جديد مع نص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // تحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

تُرجِع أو تُعيّن اللغة الافتراضية لنص العرض. قابل للقراءة والكتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد ثقافة النص الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // أضف شكل مستطيل جديد مع نص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // تحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

يحدد ما إذا كانت Aspose.Slides ستحذف جميع الكائنات الثنائية المضمَّنة أثناء تحميل العرض.

أنواع الكائنات الثنائية المضمَّنة:

 *  
 *  
 *  

قابل للقراءة والكتابة boolean .

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

الإعداد الافتراضي هو **false**.

**القيمة المرجعة:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

يحدد ما إذا كانت Aspose.Slides ستحذف جميع الكائنات الثنائية المضمَّنة أثناء تحميل العرض.

أنواع الكائنات الثنائية المضمَّنة:

 *  
 *  
 *  

قابل للقراءة والكتابة boolean .

--------------------

> ```
> المثال التالي يوضح كيفية تحميل العرض التقديمي دون أي كائنات ثنائية مضمَّنة.
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

الإعداد الافتراضي هو **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |