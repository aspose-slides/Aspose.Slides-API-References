---
title: IMathFunction
second_title: Aspose.Slides Java API 參考
description: 指定參數的函式。
type: docs
url: /zh-hant/com.aspose.slides/imathfunction/
---
**所有已實作的介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFunction extends IMathElement
```

指定參數的函式。

--------------------

> ```
> Example:
>  
>  IMathFunction sinX = new MathematicalText("sin").function("x");
>  ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getName()](#getName--) | 函式名稱 例如，函式名稱為 sin 和 cos |
| [getBase()](#getBase--) | 函式參數 |
### getName() {#getName--}
```
public abstract IMathElement getName()
```

函式名稱 例如，函式名稱為 sin 和 cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
>  ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

函式參數

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)