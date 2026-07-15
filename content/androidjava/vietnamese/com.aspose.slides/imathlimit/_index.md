---
title: IMathLimit
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng Limit bao gồm văn bản trên đường cơ sở và văn bản thu nhỏ ngay phía trên hoặc phía dưới nó.
type: docs
url: /vi/com.aspose.slides/imathlimit/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

Xác định đối tượng Limit, bao gồm văn bản trên đường cơ sở và văn bản thu nhỏ ngay phía trên hoặc dưới nó.

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số Base |
| [getLimit()](#getLimit--) | Đối số Limit |
| [getUpperLimit()](#getUpperLimit--) | Chỉ định giới hạn trên hoặc dưới |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Chỉ định giới hạn trên hoặc dưới |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Đối số Base

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

Đối số Limit

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

Chỉ định giới hạn trên hoặc dưới

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Trả về:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

Chỉ định giới hạn trên hoặc dưới

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |