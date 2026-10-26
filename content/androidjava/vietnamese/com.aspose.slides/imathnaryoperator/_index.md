---
title: IMathNaryOperator
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định một đối tượng toán học N-ary như Tổng và Tích phân.
type: docs
url: /vi/com.aspose.slides/imathnaryoperator/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Xác định một đối tượng toán học N-ary, chẳng hạn như Tổng và Tích phân. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ về toán tử N-ary bao gồm: Tổng, Hợp, Giao, Tích phân

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getSubscript()](#getSubscript--) | Xác định một đối số chỉ số dưới, ví dụ trong trường hợp một tích phân, đặt giới hạn dưới |
| [getSuperscript()](#getSuperscript--) | Xác định một đối số chỉ số trên, ví dụ trong trường hợp một tích phân, đặt giới hạn trên |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Đối số cơ sở

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Xác định một đối số chỉ số dưới, ví dụ trong trường hợp một tích phân, đặt giới hạn dưới

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Xác định một đối số chỉ số trên, ví dụ trong trường hợp một tích phân, đặt giới hạn trên

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)