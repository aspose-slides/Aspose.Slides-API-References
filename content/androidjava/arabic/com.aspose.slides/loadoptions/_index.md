---
title: LoadOptions
second_title: Aspose.Slides للـ Android عبر مرجع API لجافا
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

يسمح بتحديد خيارات إضافية (مثل التنسيق أو الخط الافتراضي) عند تحميل العرض التقديمي.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | يخلق خيارات تحميل افتراضية جديدة. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | يخلق خيارات تحميل جديدة. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | يعيد أو يعيّن تنسيق العرض التقديمي للتحميل. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | يعيد أو يعيّن تنسيق العرض التقديمي للتحميل. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | يعيد أو يعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | يعيد أو يعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | يعيد أو يعيّن خط الرموز المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | يعيد أو يعيّن خط الرموز المستخدم في حالة عدم العثور على الخط المصدر. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | يعيد أو يعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | يعيد أو يعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. |
| [getPassword()](#getPassword--) | يحصل أو يعيّن كلمة المرور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يعيّن كلمة المرور. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور. |
| [getWarningCallback()](#getWarningCallback--) | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات في الذاكرة. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات في الذاكرة. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض. |
| [getInterruptionToken()](#getInterruptionToken--) | الرمز المميز لمراقبة طلبات الإيقاف. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | الرمز المميز لمراقبة طلبات الإيقاف. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | يعيد أو يعيّن واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | يعيد أو يعيّن واجهة رد النداء التي تدير تحميل الموارد الخارجية. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | يحصل على خيارات جداول البيانات. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | يحصل على خيارات جداول البيانات. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | يعيد أو يعيّن اللغة الافتراضية لنص العرض. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | يعيد أو يعيّن اللغة الافتراضية لنص العرض. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

يخلق خيارات تحميل افتراضية جديدة.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

يخلق خيارات تحميل جديدة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| loadFormat | int | تنسيق العرض التقديمي للتحميل. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

يعيد أو يعيّن تنسيق العرض التقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**القيمة المرجعة:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

يعيد أو يعيّن تنسيق العرض التقديمي للتحميل. قراءة/كتابة [LoadFormat](../../com.aspose.slides/loadformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

يعيد أو يعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // استخدم خيارات التحميل لتحديد الخطوط العادية والآسيوية الافتراضية
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // إنشاء صورة مصغرة للشريحة
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // إنشاء PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // إنشاء XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

يعيد أو يعيّن الخط العادي المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // استخدم خيارات التحميل لتحديد الخطوط العادية والآسيوية الافتراضية
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // تحميل العرض التقديمي
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // إنشاء صورة مصغرة للشريحة
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

يعيد أو يعيّن خط الرموز المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

يعيد أو يعيّن خط الرموز المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

يعيد أو يعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

يعيد أو يعيّن الخط الآسيوي المستخدم في حالة عدم العثور على الخط المصدر. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

يحصل أو يعيّن كلمة المرور. قراءة/كتابة String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // العمل مع العرض المفكك
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


القيمة: كلمة المرور.

**القيمة المرجعة:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

يحصل أو يعيّن كلمة المرور. قراءة/كتابة String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // العمل مع العرض المفكك
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


القيمة: كلمة المرور.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن يتم تحميل خصائص المستند فقط من ملف عرض مشفر ويجب تجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت القيمة true فإن خصائص المستند لا يمكن تحميلها وسيتم إلقاء استثناء. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور. القيمة true تعني أن يتم تحميل خصائص المستند فقط من ملف عرض مشفر ويجب تجاهل كلمة المرور. القيمة false تعني أنه يجب تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تُهمل دائمًا. إذا لم تكن خصائص المستند لملف مشفر عامة وكانت القيمة true فإن خصائص المستند لا يمكن تحميلها وسيتم إلقاء استثناء. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**القيمة المرجعة:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

يعيد أو يعيّن كائنًا يتلقى التحذيرات ويقرر ما إذا كانت عملية التحميل ستستمر أو ستُجهض. قراءة/كتابة [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات في الذاكرة. تم تصميم هذه الخيارات لضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون صوتًا أو فيديو أو العرض التقديمي نفسه.

**القيمة المرجعة:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

يمثل الخيارات التي يمكن استخدامها لإدارة سلوك معالجة الكائنات الثنائية الكبيرة (BLOBs)، مثل استخدام الملفات المؤقتة أو الحد الأقصى للبايتات في الذاكرة. تم تصميم هذه الخيارات لضبط أفضل نسبة أداء/استهلاك للذاكرة لبيئة أو متطلبات معينة.

--------------------

كائن ثنائي كبير (BLOB) هو بيانات ثنائية مخزنة ككيان واحد - أي أن BLOB يمكن أن يكون صوتًا أو فيديو أو العرض التقديمي نفسه.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض. هذه الخطوط متاحة للعرض طوال عمره ولا تُشارك مع عروض أخرى.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // العمل مع العرض التقديمي
>  //CustomFont1، CustomFont2 بالإضافة إلى الخطوط من مجلدات assets\fonts و global\fonts ومجلداتها الفرعية متاحة للعرض التقديمي
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**القيمة المرجعة:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

يحدد مصادر الخطوط الخارجية التي سيستخدمها العرض. هذه الخطوط متاحة للعرض طوال عمره ولا تُشارك مع عروض أخرى.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //العمل مع العرض التقديمي
>  //CustomFont1، CustomFont2 بالإضافة إلى الخطوط من مجلدات assets\fonts و global\fonts ومجلداتها الفرعية متاحة للعرض التقديمي
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

الرمز المميز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر كائن [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، سيتم إيقافها عبر استدعاء طريقة [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) الخاصة بـ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**القيمة المرجعة:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

الرمز المميز لمراقبة طلبات الإيقاف.

--------------------

هذا الرمز يدير كامل عمر كائن [IPresentation](../../com.aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض، سيتم إيقافها عبر استدعاء طريقة [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) الخاصة بـ [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

يعيد أو يعيّن واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**القيمة المرجعة:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

يعيد أو يعيّن واجهة رد النداء التي تدير تحميل الموارد الخارجية. قراءة/كتابة [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

يحصل على خيارات جداول البيانات. على سبيل المثال، تؤثر هذه الخيارات على حساب صيغ المخططات.

**القيمة المرجعة:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

يحصل على خيارات جداول البيانات. على سبيل المثال، تؤثر هذه الخيارات على حساب صيغ المخططات.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

يعيد أو يعيّن اللغة الافتراضية لنص العرض. قراءة/كتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد الثقافة النصية الافتراضية
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // إضافة شكل مستطيل جديد مع نص
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // التحقق من لغة الجزء الأول
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

يعيد أو يعيّن اللغة الافتراضية لنص العرض. قراءة/كتابة String.

--------------------

> ```
> Example:
>   
>  // استخدم خيارات التحميل لتحديد الثقافة النصية الافتراضية
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض.

أنواع الكائنات الثنائية المضمنة:

قراءة/كتابة boolean.

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

القيمة الافتراضية **false**.

**القيمة المرجعة:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

يحدد ما إذا كان Aspose.Slides سيحذف جميع الكائنات الثنائية المضمنة أثناء تحميل العرض.

أنواع الكائنات الثنائية المضمنة:

قراءة/كتابة boolean.

--------------------

> ```
> المثال التالي يوضح كيفية تحميل العرض التقديمي بدون أي كائنات ثنائية مضمّنة.
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

القيمة الافتراضية **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |