---
title: FontsLoader
second_title: مرجع API لـ Aspose.Slides للغة Java
description: فئة لتحميل الخطوط المخصصة التي يحددها المستخدم.
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

فئة لتحميل الخطوط المخصصة التي يحددها المستخدم. يجب استخدامها قبل إنشاء أي كائنات عرض تقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | يضيف مجلدات إضافية للبحث عن الخطوط. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | يضيف خطًا من البيانات الثنائية |
| [getFontFolders()](#getFontFolders--) | يحصل على مجلدات الخطوط. |
| [clearCache()](#clearCache--) | يفرج عن جميع الخطوط المخصصة التي يعرفها المستخدم |
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
>  // المجلدات للبحث عن الخطوط
>  String[] folders = new String[] { dataDir };
>  // تحميل الخطوط من مجلد الخطوط المخصص
>  FontsLoader.loadExternalFonts(folders);
>  // إجراء بعض الأعمال وعرض تقديم الشرائح
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // مسح ذاكرة الخط
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| directories | java.lang.String[] | مجلدات لقراءة خطوط إضافية. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


يضيف خطًا من البيانات الثنائية

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | بيانات الخط |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


يحصل على مجلدات الخطوط. يرجع المجلدات التي تمت إضافتها باستخدام طريقة LoadExternalFonts وكذلك مجلدات الخطوط النظامية

**القيم المرجعة:**
java.lang.String[] - مصفوفة تحتوي على أسماء المجلدات
### clearCache() {#clearCache--}
```
public static void clearCache()
```


يفرغ جميع الخطوط المخصصة التي يعرفها المستخدم

--------------------

هذه الطريقة تحتاج إلى إفراغ الذاكرة المؤقتة للخطوط المخصصة التي يعرفها المستخدم.