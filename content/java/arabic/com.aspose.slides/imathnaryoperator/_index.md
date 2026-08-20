---
title: IMathNaryOperator
second_title: Aspose.Slides للـ Java مرجع API
description: يحدد كائنًا رياضيًا متعدد الحدّ مثل الجمع والتكامل.
type: docs
url: /ar/com.aspose.slides/imathnaryoperator/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

يحدد كائنًا رياضيًا متعدد الحدّ، مثل الجمع والتكامل. يتكوّن من عامل، أساسي (أو مُعامل)، وحدود علوية وسفلية اختيارية. أمثلة على العوامل متعددة الحدّ هي: الجمع، الاتحاد، التقاطع، التكامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getSubscript()](#getSubscript--) | يحدد معاملًا فرعيًا، على سبيل المثال، في حالة التكامل، يحدد الحد الأدنى |
| [getSuperscript()](#getSuperscript--) | يحدد معاملًا أعلى، على سبيل المثال، في حالة التكامل، يحدد الحد الأعلى |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل أساسي

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

يحدد معاملًا فرعيًا، على سبيل المثال، في حالة التكامل، يحدد الحد الأدنى

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

يحدد معاملًا أعلى، على سبيل المثال، في حالة التكامل، يحدد الحد الأعلى

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)