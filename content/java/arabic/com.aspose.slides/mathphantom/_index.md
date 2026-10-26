---
title: MathPhantom
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل كائن رياضي شبح ltmphantgt يؤثر على تخطيط العنصر الفرعي دون الحاجة إلى عرضه.
type: docs
url: /ar/com.aspose.slides/mathphantom/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

يمثل كائن رياضي شبح (<m:phant>) يؤثر على تخطيط العنصر الفرعي دون الحاجة إلى عرضه. يمكن للشفاح إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لتنسيق الصيغ أو حجز مساحة. يتم التحكم في السلوك المرئي والهندسي بواسطة خصائص مثل Show و ZeroWid و ZeroAsc و ZeroDesc و Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // إخفاء المحتوى
>  phantom.setZeroWidth(false);     // الإبقاء على العرض
> ```
## البُنى

| المُنشئ | الوصف |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | يقوم بإنشاء مثيل جديد من الفئة [MathPhantom](../../com.aspose.slides/mathphantom) باستخدام عنصر الرياضيات الأساسي المحدد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getShow()](#getShow--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [setShow(boolean value)](#setShow-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [getZeroWidth()](#getZeroWidth--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا. |
| [getZeroAsc()](#getZeroAsc--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار ارتفاع العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار ارتفاع العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا. |
| [getZeroDesc()](#getZeroDesc--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار انخفاض العنصر الأساسي (العمق تحت الخط الأساسي) صفرًا. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار انخفاض العنصر الأساسي (العمق تحت الخط الأساسي) صفرًا. |
| [getTransp()](#getTransp--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشفاح شفافًا لقواعد التباعد القائمة على الفئة. |
| [setTransp(boolean value)](#setTransp-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشفاح شفافًا لقواعد التباعد القائمة على الفئة. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص الأحرف المتحكم فيها |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

يقوم بإنشاء مثيل جديد من الفئة [MathPhantom](../../com.aspose.slides/mathphantom) باستخدام عنصر الرياضيات الأساسي المحدد.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي [IMathElement](../../com.aspose.slides/imathelement) الذي سيتم التحكم في رؤيته وتخطيطه بواسطة الشفاح. يحدد هذا العنصر المحتوى الذي قد يتم إخفاؤه أو إظهاره، مع الاستمرار في التأثير على محاذاة الشكل الهندسي للرياضيات المحيطة. |

يُستخدم عنصر الشفاح لحجز أو كبت المساحة البصرية لتعبيره الأساسي دون الحاجة إلى عرضه. يتطابق مع عنصر OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل أساسي

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

يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا.

--------------------

عند كون القيمة false، يكون العنصر الأساسي مخفيًا لكنه قد يظل يشغل مساحة اعتمادًا على إعدادات الشفاح الأخرى. يتطابق مع صفة OMML m:show.

**القيمة المرجعة:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا.

--------------------

عند كون القيمة false، يكون العنصر الأساسي مخفيًا لكنه قد يظل يشغل مساحة اعتمادًا على إعدادات الشفاح الأخرى. يتطابق مع صفة OMML m:show.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحجز الشفاح مساحة أفقية لعنصره الأساسي. يتطابق مع صفة OMML m:zeroWid.

**القيمة المرجعة:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحجز الشفاح مساحة أفقية لعنصره الأساسي. يتطابق مع صفة OMML m:zeroWid.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار ارتفاع العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يرفع الشفاح الخط الأساسي لسطر الرياضيات المحيط. يتطابق مع صفة OMML m:zeroAsc.

**القيمة المرجعة:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار ارتفاع العنصر الأساسي (الارتفاع فوق الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يرفع الشفاح الخط الأساسي لسطر الرياضيات المحيط. يتطابق مع صفة OMML m:zeroAsc.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار انخفاض العنصر الأساسي (العمق تحت الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يخفض الشفاح الخط الأساسي لسطر الرياضيات المحيط. يتطابق مع صفة OMML m:zeroDesc.

**القيمة المرجعة:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان يجب اعتبار انخفاض العنصر الأساسي (العمق تحت الخط الأساسي) صفرًا.

--------------------

عند كون القيمة true، لا يخفض الشفاح الخط الأساسي لسطر الرياضيات المحيط. يتطابق مع صفة OMML m:zeroDesc.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشفاح شفافًا لقواعد التباعد القائمة على الفئة.

--------------------

عند كون القيمة true، لا تزال العوامل والرموز داخل الشفاح تؤثر على التباعد الرياضي حول الشفاح (كما لو كانت مرئية). عند كون القيمة false، يتم تجاهل التباعد القائم على الفئة. يتطابق مع صفة OMML m:transp.

**القيمة المرجعة:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشفاح شفافًا لقواعد التباعد القائمة على الفئة.

--------------------

عند كون القيمة true، لا تزال العوامل والرموز داخل الشفاح تؤثر على التباعد الرياضي حول الشفاح (كما لو كانت مرئية). عند كون القيمة false، يتم تجاهل التباعد القائم على الفئة. يتطابق مع صفة OMML m:transp.

**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص الأحرف المتحكم فيها

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]