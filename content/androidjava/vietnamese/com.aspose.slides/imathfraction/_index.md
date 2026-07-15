---
title: IMathFraction
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Xác định đối tượng phân số bao gồm một tử số và mẫu số được tách bằng một thanh phân số.
type: docs
url: /vi/com.aspose.slides/imathfraction/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Xác định đối tượng phân số, bao gồm một tử số và mẫu số được tách bằng một thanh phân số. Thanh phân số có thể nằm ngang hoặc chéo, tùy thuộc vào thuộc tính của phân số. Đối tượng phân số cũng được sử dụng để biểu diễn hàm xếp chồng, đặt một phần tử trên phần tử khác, mà không có thanh phân số.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFractionType()](#getFractionType--) | Kiểu phân số Mặc định: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Kiểu phân số Mặc định: Bar |
| [getNumerator()](#getNumerator--) | Tử số |
| [getDenominator()](#getDenominator--) | Mẫu số |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Kiểu phân số Mặc định: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Giá trị trả về:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Kiểu phân số Mặc định: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Tử số

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Mẫu số

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)