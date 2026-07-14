---
title: MathPhantom
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل كائن رياضي شبح ltmphantgt يؤثر على تخطيط العنصر الفرعي دون ضرورة عرضه.
type: docs
url: /ar/com.aspose.slides/mathphantent/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

يمثِّل كائن رياضي شبح (<m:phant>) يؤثّر على تخطيط العنصر الفرعي دون ضرورة عرضه. يمكن للشفبح إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في السلوك المتعلق بالرؤية والهندسة عبر خصائص مثل Show وZeroWid وZeroAsc وZeroDesc وTransp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // إخفاء المحتوى
>  phantom.setZeroWidth(false);     // الاحتفاظ بالعرض
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initializes a new instance of the [MathPhantom](../../com.aspose.slides/mathphantom) class using the specified base math element. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Gets or sets a value indicating whether the base element is displayed. |
| [setShow(boolean value)](#setShow-boolean-) | Gets or sets a value indicating whether the base element is displayed. |
| [getZeroWidth()](#getZeroWidth--) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [getZeroAsc()](#getZeroAsc--) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [getZeroDesc()](#getZeroDesc--) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [getTransp()](#getTransp--) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [setTransp(boolean value)](#setTransp-boolean-) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

يُنشئ مثيلًا جديدًا من الفئة [MathPhantom](../../com.aspose.slides/mathphantom) باستخدام عنصر رياضي أساسي محدد.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The base [IMathElement](../../com.aspose.slides/imathelement) whose visibility and layout will be controlled by the phantom. This element defines the content that may be hidden or shown, while still affecting the geometric alignment of the surrounding math.

--------------------

يُستخدم العنصر الشبح لحجز أو قمع المساحة البصرية لتعبيره الأساسي دون ضرورة عرضه. وهو ما يُقابل العنصر OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**القيمة المرجعة:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**القيمة المرجعة:**  
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Gets or sets a value indicating whether the base element is displayed.

--------------------

When false, the base element is hidden but may still occupy space depending on other phantom settings. Corresponds to the OMML attribute m:show.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**القيمة المرجعة:**  
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Gets or sets a value indicating whether the width of the base element should be treated as zero.

--------------------

When true, the phantom does not reserve horizontal space for its base. Corresponds to the OMML attribute m:zeroWid.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**القيمة المرجعة:**  
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not raise the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroAsc.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**القيمة المرجعة:**  
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero.

--------------------

When true, the phantom does not lower the baseline of the surrounding math line. Corresponds to the OMML attribute m:zeroDesc.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**القيمة المرجعة:**  
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules.

--------------------

When true, operators and symbols inside the phantom still affect mathematical spacing around the phantom (as if visible). When false, class-based spacing is ignored. Corresponds to the OMML attribute m:transp.

**المُعاملات:**  
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Get children elements

**القيمة المرجعة:**  
com.aspose.slides.IMathElement[]