---
title: IMathFunction
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد دالة للمعامل.
type: docs
url: /ar/com.aspose.slides/imathfunction/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

يحدد دالة للمعامل.

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos |
| [getBase()](#getBase--) | معامل الدالة |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

اسم الدالة على سبيل المثال، أسماء الدوال هي sin و cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل الدالة

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)