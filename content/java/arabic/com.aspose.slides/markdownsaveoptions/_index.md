---
title: MarkdownSaveOptions
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل الخيارات التي تتحكم في كيفية حفظ العرض التقديمي إلى markdown.
type: docs
url: /ar/com.aspose.slides/markdownsaveoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

يمثل الخيارات التي تتحكم في كيفية حفظ العرض التقديمي إلى markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | منشئ. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getExportType()](#getExportType--) | يحدد مواصفة markdown لتحويل العرض التقديمي. |
| [setExportType(int value)](#setExportType-int-) | يحدد مواصفة markdown لتحويل العرض التقديمي. |
| [getBasePath()](#getBasePath--) | يحدد المسار الأساسي حيث سيتم حفظ المستند مع الموارد. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | يحدد المسار الأساسي حيث سيتم حفظ المستند مع الموارد. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | يحدد اسم المجلد لحفظ الصور. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | يحدد اسم المجلد لحفظ الصور. |
| [getNewLineType()](#getNewLineType--) | يحدد ما إذا كان المستند المُولد يجب أن يحتوي على أسطر جديدة \\r(Macintosh) أو \\n(Unix) أو \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | يحدد ما إذا كان المستند المُولد يجب أن يحتوي على أسطر جديدة \\r(Macintosh) أو \\n(Unix) أو \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | يحدد ما إذا كان المستند المُولد يجب أن يظهر التعليقات أم لا. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | يحدد ما إذا كان المستند المُولد يجب أن يظهر التعليقات أم لا. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [getShowSlideNumber()](#getShowSlideNumber--) | يحدد ما إذا كان المستند المُولد يجب أن يعرض رقم كل شريحة أم لا. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | يحدد ما إذا كان المستند المُولد يجب أن يعرض رقم كل شريحة أم لا. |
| [getFlavor()](#getFlavor--) | يحدد مواصفة markdown لتحويل العرض التقديمي. |
| [setFlavor(int value)](#setFlavor-int-) | يحدد مواصفة markdown لتحويل العرض التقديمي. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | الحصول أو تعيين سلسلة التنسيق المستخدمة لعناوين أرقام الشرائح في مخرجات Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | الحصول أو تعيين سلسلة التنسيق المستخدمة لعناوين أرقام الشرائح في مخرجات Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | إذا تم تعيينها إلى true، يزيل الأسطر الفارغة أو التي تحتوي فقط على مسافات من مخرجات Markdown النهائية. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | إذا تم تعيينها إلى true، يزيل الأسطر الفارغة أو التي تحتوي فقط على مسافات من مخرجات Markdown النهائية. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | يحدث لكل صورة غير SVG (صورة نقطية أو ملف ميتا) أثناء تصدير Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | يحدث لكل صورة SVG أثناء تصدير Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

منشئ.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

يحدد مواصفة markdown لتحويل العرض التقديمي. الافتراضي هو TextOnly.

**الإرجاع:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

يحدد مواصفة markdown لتحويل العرض التقديمي. الافتراضي هو TextOnly.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

يحدد المسار الأساسي حيث سيتم حفظ المستند مع الموارد. الافتراضي هو الدليل الحالي للتطبيق.

**الإرجاع:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

يحدد المسار الأساسي حيث سيتم حفظ المستند مع الموارد. الافتراضي هو الدليل الحالي للتطبيق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

يحدد اسم المجلد لحفظ الصور. الافتراضي هو Images.

**الإرجاع:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

يحدد اسم المجلد لحفظ الصور. الافتراضي هو Images.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

يحدد ما إذا كان المستند المُولد يجب أن يحتوي على أسطر جديدة \\r(Macintosh) أو \\n(Unix) أو \\r\\n(Windows). الافتراضي هو Unix.

**الإرجاع:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

يحدد ما إذا كان المستند المُولد يجب أن يحتوي على أسطر جديدة \\r(Macintosh) أو \\n(Unix) أو \\r\\n(Windows). الافتراضي هو Unix.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

يحدد ما إذا كان المستند المُولد يجب أن يظهر التعليقات أم لا. الافتراضي هو false.

**الإرجاع:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

يحدد ما إذا كان المستند المُولد يجب أن يظهر التعليقات أم لا. الافتراضي هو false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

يحدد ما إذا كان المستند المُولد يجب أن يعرض رقم كل شريحة أم لا. الافتراضي هو false.

**الإرجاع:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

يحدد ما إذا كان المستند المُولد يجب أن يعرض رقم كل شريحة أم لا. الافتراضي هو false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

يحدد مواصفة markdown لتحويل العرض التقديمي. الافتراضي هو Multi-markdown.

**الإرجاع:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

يحدد مواصفة markdown لتحويل العرض التقديمي. الافتراضي هو Multi-markdown.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

الحصول أو تعيين سلسلة التنسيق المستخدمة لعناوين أرقام الشرائح في مخرجات Markdown. يجب أن تتضمن السلسلة العنصر "\{0\}"، والذي سيستبدل بفهرس الشريحة أثناء التصدير. مثال: "\# Slide \{0\}" سينتج "\# Slide 1"، "\# Slide 2"، الخ.

**الإرجاع:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

الحصول أو تعيين سلسلة التنسيق المستخدمة لعناوين أرقام الشرائح في مخرجات Markdown. يجب أن تتضمن السلسلة العنصر "\{0\}"، والذي سيستبدل بفهرس الشريحة أثناء التصدير. مثال: "\# Slide \{0\}" سينتج "\# Slide 1"، "\# Slide 2"، الخ.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown. هذه الخاصية تعرف ما إذا كانت المسافات المتتابعة: - تُحافظ كمسافات عادية، - تُبدل بين المسافات العادية وكيانات المسافة غير القابلة للكسر (�)، - أو تُستبدل بالكامل (بعد الأولى) بمسافة غير قابلة للكسر للحفاظ على المحاذاة البصرية في مخرجات Markdown. القيمة الافتراضية هي [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**الإرجاع:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

يحدد كيفية التعامل مع الأحرف المتكررة للمسافات العادية أثناء تصدير Markdown. هذه الخاصية تعرف ما إذا كانت المسافات المتتابعة: - تُحافظ كمسافات عادية، - تُبدل بين المسافات العادية وكيانات المسافة غير القابلة للكسر (�)، - أو تُستبدل بالكامل (بعد الأولى) بمسافة غير قابلة للكسر للحفاظ على المحاذاة البصرية في مخرجات Markdown. القيمة الافتراضية هي [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

إذا تم تعيينها إلى true، يزيل الأسطر الفارغة أو التي تحتوي فقط على مسافات من مخرجات Markdown النهائية. الافتراضي هو false.

**الإرجاع:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

إذا تم تعيينها إلى true، يزيل الأسطر الفارغة أو التي تحتوي فقط على مسافات من مخرجات Markdown النهائية. الافتراضي هو false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

يحدث لكل صورة غير SVG (صورة نقطية أو ملف ميتا) أثناء تصدير Markdown. يسمح بتخصيص طريقة حفظ الصورة وإشارتها. إذا لم يتم معالجتها، تُحفظ الصورة محليًا برابط نسبي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | حدث حفظ صورة Markdown. |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

يحدث لكل صورة SVG أثناء تصدير Markdown. يسمح بتجاوز عملية الحفظ وتوليد الرابط الافتراضي. إذا لم يتم معالجتها، تُحفظ SVG محليًا برابط نسبي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | حدث حفظ صورة SVG في Markdown. |