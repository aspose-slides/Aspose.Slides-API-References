---
title: MathFraction
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định đối tượng phân số bao gồm tử số và mẫu được tách bằng thanh phân số.
type: docs
url: /vi/com.aspose.slides/mathfraction/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Xác định đối tượng phân số, bao gồm tử và mẫu được tách bằng thanh phân số. Thanh phân số có thể nằm ngang hoặc chéo, tùy thuộc vào các thuộc tính của phân số. Đối tượng phân số cũng được sử dụng để đại diện cho hàm chồng, đặt một phần tử lên trên phần tử khác mà không có thanh phân số.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Khởi tạo MathFraction với tử số, mẫu và kiểu được chỉ định |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Khởi tạo một MathFraction loại 'Bar' với tử số và mẫu được chỉ định |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFractionType()](#getFractionType--) | Kiểu phân số Mặc định: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Kiểu phân số Mặc định: Bar |
| [getNumerator()](#getNumerator--) | Tử số |
| [getDenominator()](#getDenominator--) | Mẫu |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Khởi tạo MathFraction với tử số, mẫu và kiểu được chỉ định

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu |
| fractionType | int | Kiểu phân số |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Khởi tạo một MathFraction loại 'Bar' với tử số và mẫu được chỉ định

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Tham số:**
| Parameter | Type | Mô tả |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Tử số |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mẫu |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Kiểu phân số Mặc định: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Kết quả trả về:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
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
| Parameter | Type | Mô tả |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Tử số

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Kết quả trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Mẫu

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Kết quả trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Kết quả trả về:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Thuộc tính ký tự điều khiển

**Kết quả trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps