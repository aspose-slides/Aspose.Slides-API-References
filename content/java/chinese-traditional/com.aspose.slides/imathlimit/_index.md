---
title: IMathLimit
second_title: Aspose.Slides 的 Java API 參考
description: 指定 Limit 物件，由基線上的文字以及緊接其上方或下方的縮小文字組成。
type: docs
url: /zh-hant/com.aspose.slides/imathlimit/
---
**已實作的介面:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

指定 Limit 物件，由基線上的文字以及緊接其上方或下方的縮小文字組成。

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getLimit()](#getLimit--) | 限制參數 |
| [getUpperLimit()](#getUpperLimit--) | 指定上限或下限 |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | 指定上限或下限 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基礎參數

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**傳回:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

限制參數

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**傳回:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

指定上限或下限

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**傳回:**  
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

指定上限或下限

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
