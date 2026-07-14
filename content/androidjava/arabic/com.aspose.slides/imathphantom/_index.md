---
title: IMathPhantom
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل كائن رياضي وهمي ltmphantgt يؤثر على تخطيط العنصر الفرعي دون الحاجة إلى عرضه.
type: docs
url: /ar/com.aspose.slides/imathphantom/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

يمثل كائن رياضي وهمي (<m:phant>) يؤثّر على تخطيط العنصر الفرعي دون ضرورة عرضه. يمكن للعنصر الوهمي إخفاء التعبير الأساسي مع الحفاظ على عرضه أو ارتفاعه أو عمقه لضبط الصيغ أو حفظ مساحة. يتم التحكم في الإظهار والسلوك الهندسي عبر الخصائص مثل Show، ZeroWid، ZeroAsc، ZeroDesc، وTransp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // إخفاء المحتوى
>  phantom.setZeroWidth(false);     // الحفاظ على العرض
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getShow()](#getShow--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [setShow(boolean value)](#setShow-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا. |
| [getZeroWidth()](#getZeroWidth--) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار عرض العنصر الأساسي صفرًا. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار عرض العنصر الأساسي صفرًا. |
| [getZeroAsc()](#getZeroAsc--) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار ارتفاع الصعود (الارتفاع فوق خط القاعدة) للعنصر الأساسي صفرًا. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار ارتفاع الصعود (الارتفاع فوق خط القاعدة) للعنصر الأساسي صفرًا. |
| [getZeroDesc()](#getZeroDesc--) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار انخفاض الهبوط (العمق تحت خط القاعدة) للعنصر الأساسي صفرًا. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار انخفاض الهبوط (العمق تحت خط القاعدة) للعنصر الأساسي صفرًا. |
| [getTransp()](#getTransp--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الوهم شفافًا لقواعد التباعد المستندة إلى الفئة. |
| [setTransp(boolean value)](#setTransp-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الوهم شفافًا لقواعد التباعد المستندة إلى الفئة. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل القاعدة

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

عند كون القيمة false، يكون العنصر الأساسي مخفيًا ولكن قد يظل يشغل مساحة اعتمادًا على إعدادات الوهم الأخرى. يتطابق مع سمة OMML m:show.

**القيمة المرجعة:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان العنصر الأساسي معروضًا.

--------------------

عند كون القيمة false، يكون العنصر الأساسي مخفيًا ولكن قد يظل يشغل مساحة اعتمادًا على إعدادات الوهم الأخرى. يتطابق مع سمة OMML m:show.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحتفظ الوهم بمساحة أفقية للعنصر الأساسي. يتطابق مع سمة OMML m:zeroWid.

**القيمة المرجعة:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار عرض العنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يحتفظ الوهم بمساحة أفقية للعنصر الأساسي. يتطابق مع سمة OMML m:zeroWid.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار ارتفاع الصعود (الارتفاع فوق خط القاعدة) للعنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يرتفع خط القاعدة للخط الرياضي المحيط. يتطابق مع سمة OMML m:zeroAsc.

**القيمة المرجعة:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار ارتفاع الصعود (الارتفاع فوق خط القاعدة) للعنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يرتفع خط القاعدة للخط الرياضي المحيط. يتطابق مع سمة OMML m:zeroAsc.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار انخفاض الهبوط (العمق تحت خط القاعدة) للعنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يخفض خط القاعدة للخط الرياضي المحيط. يتطابق مع سمة OMML m:zeroDesc.

**القيمة المرجعة:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا يجب اعتبار انخفاض الهبوط (العمق تحت خط القاعدة) للعنصر الأساسي صفرًا.

--------------------

عند كون القيمة true، لا يخفض خط القاعدة للخط الرياضي المحيط. يتطابق مع سمة OMML m:zeroDesc.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الوهم شفافًا لقواعد التباعد المستندة إلى الفئة.

--------------------

عند كون القيمة true، لا تزال المشغّلات والرموز داخل الوهم تؤثر على التباعد الرياضي حوله (كما لو كان مرئيًا). عند كون القيمة false، يتم تجاهل التباعد المستند إلى الفئة. يتطابق مع سمة OMML m:transp.

**القيمة المرجعة:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان الوهم شفافًا لقواعد التباعد المستندة إلى الفئة.

--------------------

عند كون القيمة true، لا تزال المشغّلات والرموز داخل الوهم تؤثر على التباعد الرياضي حوله (كما لو كان مرئيًا). عند كون القيمة false، يتم تجاهل التباعد المستند إلى الفئة. يتطابق مع سمة OMML m:transp.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |