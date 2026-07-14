---
title: IPptxOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل خيارات حفظ عروض OpenXml بصيغ PPTX، PPSX، POTX، PPTM، PPSM، POTM.
type: docs
url: /ar/com.aspose.slides/ipptxoptions/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

يمثل خيارات حفظ عروض OpenXml (PPTX، PPSX، POTX، PPTM، PPSM، POTM).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getConformance()](#getConformance--) | يحدد فئة التوافق التي يتوافق معها مستند Presentation. |
| [setConformance(int value)](#setConformance-int-) | يحدد فئة التوافق التي يتوافق معها مستند Presentation. |
| [getZip64Mode()](#getZip64Mode--) | يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | يحدد ما إذا كانت صورة مصغرة للعرض ستتم تحديثها. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | يحدد ما إذا كانت صورة مصغرة للعرض ستتم تحديثها. |
| [getCompressionLevel()](#getCompressionLevel--) | يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

يحدد فئة التوافق التي يتوافق معها مستند Presentation. القيمة الافتراضية هي [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**القيمة المرجعة:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

يحدد فئة التوافق التي يتوافق معها مستند Presentation. القيمة الافتراضية هي [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. القيمة الافتراضية هي [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

يحدد ما إذا كان يتم استخدام تنسيق ZIP64 لمستند Presentation. القيمة الافتراضية هي [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```

يحدد ما إذا كانت صورة مصغرة للعرض ستتم تحديثها. قابل للقراءة/الكتابة boolean. القيمة الافتراضية هي **true**.

> ```
> مثال:
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

عند كون قيمة الخيار **true**، سيتم إنشاء صورة مصغرة جديدة.  
عند كون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

**القيمة المرجعة:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

يحدد ما إذا كانت صورة مصغرة للعرض ستتم تحديثها. قابل للقراءة/الكتابة boolean. القيمة الافتراضية هي **true**.

> ```
> مثال:
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

عند كون قيمة الخيار **true**، سيتم إنشاء صورة مصغرة جديدة.  
عند كون قيمة الخيار **false**، سيتم حفظ الصورة المصغرة الحالية كما هي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. القيمة الافتراضية هي [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

مستويات الضغط الأعلى تنتج ملفات أصغر ولكنها تتطلب وقت معالجة أكبر. نسبة الضغط الفعلية تعتمد على محتوى العرض.

**القيمة المرجعة:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

يحدد مستوى الضغط المستخدم عند حفظ مستند العرض. القيمة الافتراضية هي [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

مستويات الضغط الأعلى تنتج ملفات أصغر ولكنها تتطلب وقت معالجة أكبر. نسبة الضغط الفعلية تعتمد على محتوى العرض.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |