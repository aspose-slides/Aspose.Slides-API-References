---
title: IMathFunction
second_title: Aspose.Slides Java API 参考
description: 指定参数的函数。
type: docs
url: /zh/com.aspose.slides/imathfunction/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

指定参数的函数。

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 函数名称 例如，函数名称为 sin 和 cos |
| [getBase()](#getBase--) | 函数参数 |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

函数名称 例如，函数名称为 sin 和 cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

函数参数

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```


**返回：**
[IMathElement](../../com.aspose.slides/imathelement)