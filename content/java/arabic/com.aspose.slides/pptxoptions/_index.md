---
title: PptxOptions
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خيارات حفظ عروض OpenXml التقديمية PPTX PPSX POTX PPTM PPSM POTM.
type: docs
url: /ar/com.aspose.slides/pptxoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المطبقة:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

يمثل خيارات حفظ عروض OpenXml التقديمية (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | ينشئ نسخة جديدة من PptxOptions |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getConformance()](#getConformance--) | يحدد فئة التوافق التي يتوافق معها مستند Presentation. |
| [setConformance(int value)](#setConformance-int-) | يحدد فئة التوافق التي يتوافق معها مستند Presentation. |
| [getZip64Mode()](#getZip64Mode--) | يحدد ما إذا كان تنسيق ZIP64 يُستخدم لمستند Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | يحدد ما إذا كان تنسيق ZIP64 يُستخدم لمستند Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | يحدد ما إذا كان سيتم تحديث الصورة المصغرة للعرض التقديمي. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | يحدد ما إذا كان سيتم تحديث الصورة المصغرة للعرض التقديمي. |
| [getCompressionLevel()](#getCompressionLevel--) | يحدد مستوى الضغط المستخدم عند حفظ مستند Presentation. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | يحدد مستوى الضغط المستخدم عند حفظ مستند Presentation. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

ينشئ نسخة جديدة من PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

يحدد فئة التوافق التي يتوافق معها مستند Presentation. القيمة الافتراضية هي [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**القيمة المرجعة:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

يحدد فئة التوافق التي يتوافق معها مستند Presentation. القيمة الافتراضية هي [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

يحدد ما إذا كان تنسيق ZIP64 يُستخدم لمستند Presentation. القيمة الافتراضية هي [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

يحدد ما إذا كان تنسيق ZIP64 يُستخدم لمستند Presentation. القيمة الافتراضية هي [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

يحدد ما إذا كان سيتم تحديث الصورة المصغرة للعرض التقديمي. قابل للقراءة/الكتابة من نوع boolean. القيمة الافتراضية هي **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

عند كون قيمة الخيار **true**، سيتم توليد صورة مصغرة جديدة.

عند كون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

**القيمة المرجعة:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

يحدد ما إذا كان سيتم تحديث الصورة المصغرة للعرض التقديمي. قابل للقراءة/الكتابة من نوع boolean. القيمة الافتراضية هي **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

عند كون قيمة الخيار **true**، سيتم توليد صورة مصغرة جديدة.

عند كون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

يحدد مستوى الضغط المستخدم عند حفظ مستند Presentation. القيمة الافتراضية هي [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

مستويات الضغط الأعلى تنتج ملفات أصغر ولكن تتطلب وقت معالجة أطول. نسبة الضغط الفعلية تعتمد على محتوى العرض التقديمي.

**القيمة المرجعة:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

يحدد مستوى الضغط المستخدم عند حفظ مستند Presentation. القيمة الافتراضية هي [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مستويات الضغط الأعلى تنتج ملفات أصغر ولكن تتطلب وقت معالجة أطول. نسبة الضغط الفعلية تعتمد على محتوى العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |