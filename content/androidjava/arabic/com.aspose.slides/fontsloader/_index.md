---
title: FontsLoader
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: فئة لتحميل الخطوط المخصصة المعرفة من قبل المستخدم.
type: docs
url: /ar/com.aspose.slides/fontsloader/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

فئة لتحميل الخطوط المخصصة المعرفة من قبل المستخدم. يجب استخدامها قبل إنشاء أي كائنات عرض.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | يضيف مجلدات إضافية للبحث عن الخطوط. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | يضيف خطًا من البيانات الثنائية |
| [getFontFolders()](#getFontFolders--) | يحصل على مجلدات الخطوط. |
| [clearCache()](#clearCache--) | يطلق جميع الخطوط المخصصة المعرفة من قبل المستخدم |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


يضيف مجلدات إضافية للبحث عن الخطوط.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // مجلدات للبحث عن الخطوط
>  String[] folders = new String[] { dataDir };
>  // تحميل الخطوط من مجلد الخطوط المخصص
>  FontsLoader.loadExternalFonts(folders);
>  // قم ببعض العمل وأجرِ عرض الشرائح
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // مسح ذاكرة الخط
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| directories | java.lang.String[] | المجلدات لقراءة الخطوط الإضافية. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


يضيف خطًا من البيانات الثنائية

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | بيانات الخط |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


يحصل على مجلدات الخطوط. يعيد المجلدات التي تمت إضافتها باستخدام طريقة LoadExternalFonts بالإضافة إلى مجلدات الخطوط النظامية

**القيمة المرجعة:**
java.lang.String[] - مصفوفة تحتوي على أسماء المجلدات
### clearCache() {#clearCache--}
```
public static void clearCache()
```


يطلق جميع الخطوط المخصصة المعرفة من قبل المستخدم

--------------------

تحتاج هذه الطريقة إلى مسح الذاكرة المؤقتة للخطوط المخصصة المعرفة من قبل المستخدم.