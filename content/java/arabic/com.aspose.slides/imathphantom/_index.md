---
title: IMathPhantom
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل كائن رياضي شبح (ltmphantgt) يؤثر على تخطيط العنصر الفرعي دون الحاجة إلى عرضه.
type: docs
url: /ar/com.aspose.slides/imathphantom/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

يمثل كائن رياضي شبح (<m:phant>) يؤثر على تخطيط العنصر الفرعي دون عرضه بالضرورة. يمكن للشفّاح إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في السلوك المرئي والهندسي عن طريق خصائص مثل Show و ZeroWid و ZeroAsc و ZeroDesc و Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // إخفاء المحتوى
>  phantom.setZeroWidth(false);     // الحفاظ على العرض
```
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
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

المعامل الأساسي

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
public abstract boolean getShow()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا.

--------------------

عند كون القيمة false، يكون العنصر الأساسي مخفيًا لكن قد يحتفظ بالمساحة وفقًا لإعدادات الشبح الأخرى. يتوافق مع السمة OMML m:show.

**القيمة المرجعة:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا.

--------------------

عند كون القيمة false، يكون العنصر الأساسي مخفيًا لكن قد يحتفظ بالمساحة وفقًا لإعدادات الشبح الأخرى. يتوافق مع السمة OMML m:show.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحجز الشبح مساحة أفقية لقاعدته. يتوافق مع السمة OMML m:zeroWid.

**القيمة المرجعة:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحجز الشبح مساحة أفقية لقاعدته. يتوافق مع السمة OMML m:zeroWid.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار صعود العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يرفع الشبح الخط الأساسي لسطر الرياضيات المحيط. يتوافق مع السمة OMML m:zeroAsc.

**القيمة المرجعة:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار صعود العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يرفع الشبح الخط الأساسي لسطر الرياضيات المحيط. يتوافق مع السمة OMML m:zeroAsc.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار هبوط العنصر الأساسي (العمق أسفل الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يخفض الشبح الخط الأساسي لسطر الرياضيات المحيط. يتوافق مع السمة OMML m:zeroDesc.

**القيمة المرجعة:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار هبوط العنصر الأساسي (العمق أسفل الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يخفض الشبح الخط الأساسي لسطر الرياضيات المحيط. يتوافق مع السمة OMML m:zeroDesc.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشبح شفافًا لقواعد التباعد المستندة إلى الفئة.

--------------------

عند كون القيمة true، لا يزال المشغّلات والرموز داخل الشبح تؤثر على التباعد الرياضي حول الشبح (كما لو كان مرئيًا). عند كون القيمة false، يتم تجاهل التباعد المستند إلى الفئة. يتوافق مع السمة OMML m:transp.

**القيمة المرجعة:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشبح شفافًا لقواعد التباعد المستندة إلى الفئة.

--------------------

عند كون القيمة true، لا يزال المشغّلات والرموز داخل الشبح تؤثر على التباعد الرياضي حول الشبح (كما لو كان مرئيًا). عند كون القيمة false، يتم تجاهل التباعد المستند إلى الفئة. يتوافق مع السمة OMML m:transp.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |