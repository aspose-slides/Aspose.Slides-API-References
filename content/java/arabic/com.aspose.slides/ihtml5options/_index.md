---
title: IHtml5Options
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ Java
description: يمثل خيارات تصدير HTML5.
type: docs
url: /ar/com.aspose.slides/ihtml5options/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

يمثل خيارات تصدير HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | يُعيد أو يُحدد خيار حركة الانتقالات. قراءة/كتابة boolean. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | يُعيد أو يُحدد خيار حركة الانتقالات. قراءة/كتابة boolean. |
| [getAnimateShapes()](#getAnimateShapes--) | يُعيد أو يُحدد خيار حركة الأشكال. قراءة/كتابة boolean. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | يُعيد أو يُحدد خيار حركة الأشكال. قراءة/كتابة boolean. |
| [getEmbedImages()](#getEmbedImages--) | يُعيد أو يُحدد خيار تضمين الصور. قراءة/كتابة boolean. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | يُعيد أو يُحدد خيار تضمين الصور. قراءة/كتابة boolean. |
| [getOutputPath()](#getOutputPath--) | يحدد أين يجب تخزين الموارد الخارجية. قراءة/كتابة String. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | يحدد أين يجب تخزين الموارد الخارجية. قراءة/كتابة String. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور قراءة/كتابة PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور قراءة/كتابة PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يحدد وضع وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يحدد وضع وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

يُعيد أو يُحدد خيار حركة الانتقالات. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

يُعيد أو يُحدد خيار حركة الانتقالات. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

يُعيد أو يُحدد خيار حركة الأشكال. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

يُعيد أو يُحدد خيار حركة الأشكال. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

يُعيد أو يُحدد خيار تضمين الصور. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public abstract void setEmbedImages(boolean value)
```

يُعيد أو يُحدد خيار تضمين الصور. قراءة/كتابة boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```

يحدد أين يجب تخزين الموارد الخارجية. قراءة/كتابة String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public abstract void setOutputPath(String value)
```

يحدد أين يجب تخزين الموارد الخارجية. قراءة/كتابة String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

يمثل مستوى ضغط الصور قراءة/كتابة PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**القيمة المرجعة:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور قراءة/كتابة PicturesCompression (\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

يحصل أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تُضبط على true، سيتم تعطيل الأحرف المتصلة في المخرجات المرسومة. بشكل افتراضي، تُضبط هذه الخاصية على false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

يحصل أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تُضبط على true، سيتم تعطيل الأحرف المتصلة في المخرجات المرسومة. بشكل افتراضي، تُضبط هذه الخاصية على false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // تعطيل الأحرف المتصلة في عرض النص
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يحدد وضع وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يحدد وضع وضع الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |