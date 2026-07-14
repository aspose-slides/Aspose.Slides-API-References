---
title: PortionFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: هذه الفئة تحتوي على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/portionformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**All Implemented Interfaces:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //إنشاء كائن عرض يمثل ملف عرض
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides يستخدم هذه المعرفات الخاصة (مشابهة لتلك المستخدمة في PowerPoint):
>      // +mn-lt - خط جسم لاتيني (خط لاتيني أصغر)
>      // +mj-lt -Heading خط عنوان لاتيني (خط لاتيني رئيسي)
>      // +mn-ea - خط جسم شرق آسيوي (خط شرق آسيوي أصغر)
>      // +mj-ea - خط جسم شرق آسيوي (خط شرق آسيوي أصغر)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحددة للجزء المعين. يعني هذا أنه لا يتم تطبيق الوراثة عند الحصول على القيم، لذا في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم معلمات التنسيق الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [getEffective](../../com.aspose.slides/portionformat\#getEffective) التي تُرجِع مثيلًا من [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | يُنشئ مثيلًا جديدًا من فئة [PortionFormat](../../com.aspose.slides/portionformat). |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | يُرجع أو يضبط معرّف العلامة المرجعية. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | يُرجع أو يضبط معرّف العلامة المرجعية. |
| [getSmartTagClean()](#getSmartTagClean--) | يحدد ما إذا كان يجب تنظيف العلامة الذكية. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | يحدد ما إذا كان يجب تنظيف العلامة الذكية. |
| [getHyperlinkClick()](#getHyperlinkClick--) | يُرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | يُرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | يُرجع أو يضبط الارتباط التشعبي المحدد للتحويم بالفأرة. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | يُرجع أو يضبط الارتباط التشعبي المحدد للتحوم بالفأرة. |
| [getHyperlinkManager()](#getHyperlinkManager--) | مدير الروابط التشعبية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

يُنشئ مثيلًا جديدًا من فئة [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

يرجع أو يضبط معرّف العلامة المرجعية. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

يرجع أو يضبط معرّف العلامة المرجعية. قراءة/كتابة String.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

يحدد ما إذا كان يجب تنظيف العلامة الذكية. لا يتم تطبيق الوراثة. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

يحدد ما إذا كان يجب تنظيف العلامة الذكية. لا يتم تطبيق الوراثة. قراءة/كتابة boolean.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

يرجع أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

يرجع أو يضبط الارتباط التشعبي المحدد للتحويم بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

يرجع أو يضبط الارتباط التشعبي المحدد للتحوم بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

مدير الروابط التشعبية. قراءة فقط [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**القيمة المرجعة:**
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


**القيمة المرجعة:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - كائن من النوع [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).