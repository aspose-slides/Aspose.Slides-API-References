---
title: MathFunction
second_title: مرجع API Aspose.Slides برای Java
description: یک تابع از آرگومان را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathfunction/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

یک تابع از یک آرگومان را مشخص می‌کند.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathFunction را مقداردهی اولیه می‌کند. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathFunction را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام تابع برای مثال، نام توابع sin و cos هستند |
| [getBase()](#getBase--) | آرگومان تابع |
| [getChildren()](#getChildren--) | دریافت عناصر فرزندان |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


یک نمونه جدید از کلاس MathFunction را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


یک نمونه جدید از کلاس MathFunction را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


نام تابع برای مثال، نام توابع sin و cos هستند

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


آرگومان تابع

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**بازگشت:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزندان

**بازگشت:**  
com.aspose.slides.IMathElement[] - آرایه‌ای از [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


ویژگی‌های کاراکتر کنترل

**بازگشت:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps