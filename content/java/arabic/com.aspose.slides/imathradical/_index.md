---
title: IMathRadical
second_title: مرجع API لـ Aspose.Slides لجافا
description: يحدد الدالة الجذرية المكوّنة من قاعدة ودرجة اختيارية.
type: docs
url: /ar/com.aspose.slides/imathradical/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

يحدد الدالة الجذرية، المكوّنة من قاعدة ودرجة اختيارية. مثال على كائن الجذر هو \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
> ```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getDegree()](#getDegree--) | معامل الدرجة |
| [getHideDegree()](#getHideDegree--) | إخفاء الدرجة عندما يكون صحيحًا، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | إخفاء الدرجة عندما يكون صحيحًا، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل القاعدة

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  IMathElement baseElem = radical.getBase();
>  ```


**إرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public abstract IMathElement getDegree()
```

معامل الدرجة

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  IMathElement degreeElem = radical.getDegree();
>  ```

**إرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

إخفاء الدرجة عندما يكون صحيحًا، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  radical.setHideDegree(true);
>  ```

**إرجاع:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

إخفاء الدرجة عندما يكون صحيحًا، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  radical.setHideDegree(true);
>  ```

**المعلمات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |