---
title: IMathNaryOperator
second_title: Aspose.Slides للأندرويد عبر مرجع API للغة جافا
description: يحدد كائنًا رياضيًا متعدد القيم مثل الجمع والتكامل.
type: docs
url: /ar/com.aspose.slides/imathnaryoperator/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

يحدد كائنًا رياضيًا متعدد القيم، مثل الجمع والتكامل. يتكون من عامل، وقاعدة (أو معامل)، وحدود عليا وسفلى اختيارية. أمثلة على العوامل المتعددة: الجمع، الاتحاد، التقاطع، التكامل

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Specifies a subscript argument that, for example, in the case of an integral, sets the lower limit |
| [getSuperscript()](#getSuperscript--) | Specifies a supersript argument that, for example, in the case of an integral, sets the upper limit |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


معامل القاعدة

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


يحدد معامل أسفل يضع، على سبيل المثال، الحد الأدنى في حالة التكامل

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


يحدد معامل أعلى يضع، على سبيل المثال، الحد الأعلى في حالة التكامل

--------------------

> ```
> مثال:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```


**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)