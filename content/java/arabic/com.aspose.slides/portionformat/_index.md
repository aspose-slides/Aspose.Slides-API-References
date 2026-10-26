---
title: PortionFormat
second_title: مرجع API لـ Aspose.Slides for Java
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/portionformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

> ```
> الأمثلة التالية توضح لك كيفية تعيين الخط اللاتيني إلى جزء الفقرة في عرض PowerPoint.
>  
>  //إنشاء كائن عرض يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides يستخدم هذه المعرفات الخاصة (مشابهة لتلك المستخدمة في PowerPoint):
>      // +mn-lt - خط جسم لاتيني (خط لاتيني صغير)
>      // +mj-lt -خط عنوان لاتيني (خط لاتيني رئيسي)
>      // +mn-ea - خط جسم شرق آسيوي (خط شرق آسيوي صغير)
>      // +mj-ea -خط جسم شرق آسيوي (خط شرق آسيوي رئيسي)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المعرفة للجزء المحدد. هذا يعني أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

من أجل الحصول على قيم معاملات التنسيق الفعلية بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [getEffective](../../com.aspose.slides/portionformat\#getEffective) التي تُرجع كائن [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## المُنشئات

| منشئ | الوصف |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | ينشئ مثالًا جديدًا من الفئة [PortionFormat](../../com.aspose.slides/portionformat). |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | تُرجع أو تُعيّن معرف الإشارة المرجعية. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | تُرجع أو تُعيّن معرف الإشارة المرجعية. |
| [getSmartTagClean()](#getSmartTagClean--) | تُحدّد ما إذا كان يجب تنظيف العلامة الذكية. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | تُحدّد ما إذا كان يجب تنظيف العلامة الذكية. |
| [getHyperlinkClick()](#getHyperlinkClick--) | تُرجع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | تُرجع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | تُرجع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | تُرجع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. |
| [getHyperlinkManager()](#getHyperlinkManager--) | مدير الارتباطات التشعبية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

ينشئ مثالًا جديدًا من الفئة [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

تُرجع أو تُعيّن معرف الإشارة المرجعية. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

تُرجع أو تُعيّن معرف الإشارة المرجعية. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

تُحدّد ما إذا كان يجب تنظيف العلامة الذكية. لا تُطبّق الوراثة. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

تُحدّد ما إذا كان يجب تنظيف العلامة الذكية. لا تُطبّق الوراثة. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

تُرجع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**الإرجاع:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

تُرجع أو تُعيّن الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

تُرجع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**الإرجاع:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

تُرجع أو تُعيّن الارتباط التشعبي المحدد عند مرور الفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

مدير الارتباطات التشعبية. قراءة فقط [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**الإرجاع:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).