---
title: IMathRadical
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد الدالة الجذرية التي تتكون من قاعدة ودرجة اختيارية.
type: docs
url: /ar/com.aspose.slides/imathradical/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRadical extends IMathElement
```

يحدد الدالة الجذرية، التي تتكون من قاعدة ودرجة اختيارية. مثال على كائن جذري هو \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getDegree()](#getDegree--) | معامل الدرجة |
| [getHideDegree()](#getHideDegree--) | إخفاء الدرجة عندما تكون true، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | إخفاء الدرجة عندما تكون true، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65 |
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


**القيمة المرجعة:**
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

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public abstract boolean getHideDegree()
```

إخفاء الدرجة عندما تكون true، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  radical.setHideDegree(true);
>  ```


**القيمة المرجعة:** boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public abstract void setHideDegree(boolean value)
```

إخفاء الدرجة عندما تكون true، لا يتم إظهار الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  IMathRadical radical = new MathematicalText("x").radical("3"); // جذر مكعب
>  radical.setHideDegree(true);
>  ```


**المعاملات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |