---
title: IMathNaryOperator
second_title: Tham chiếu API Java của Aspose.Slides
description: Xác định một đối tượng toán học N-ary như Summation và Integral.
type: docs
url: /vi/com.aspose.slides/imathnaryoperator/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Xác định một đối tượng toán học N-ary, chẳng hạn như Summation và Integral. Nó bao gồm một toán tử, một cơ sở (hoặc toán hạng), và các giới hạn trên và dưới tùy chọn. Các ví dụ của các toán tử N-ary là: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Tham số cơ sở |
| [getSubscript()](#getSubscript--) | Xác định một đối số chỉ số phụ mà, ví dụ, trong trường hợp của một integral, đặt giới hạn dưới |
| [getSuperscript()](#getSuperscript--) | Xác định một đối số chỉ số cao mà, ví dụ, trong trường hợp của một integral, đặt giới hạn trên |
### getBase() {#getBase--}
> ```
public abstract IMathElement getBase()
```

Tham số cơ sở

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Xác định một đối số chỉ số phụ mà, ví dụ, trong trường hợp của một integral, đặt giới hạn dưới

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

Xác định một đối số chỉ số cao mà, ví dụ, trong trường hợp của một integral, đặt giới hạn trên

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)