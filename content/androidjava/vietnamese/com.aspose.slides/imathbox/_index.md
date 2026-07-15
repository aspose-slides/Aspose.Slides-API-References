---
title: IMathBox
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Xác định việc đóng gói hộp logic của phần tử toán học.
type: docs
url: /vi/com.aspose.slides/imathbox/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getOperatorEmulator()](#getOperatorEmulator--) | Trình giả lập toán tử. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Trình giả lập toán tử. |
| [getNoBreak()](#getNoBreak--) | Không ngắt. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Không ngắt. |
| [getDifferential()](#getDifferential--) | Vi phân. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Vi phân. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Khi đúng, trình giả lập toán tử này đóng vai trò là một điểm căn chỉnh; nghĩa là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Khi đúng, trình giả lập toán tử này đóng vai trò là một điểm căn chỉnh; nghĩa là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. |
| [getExplicitBreak()](#getExplicitBreak--) | Ngắt rõ ràng chỉ định liệu có ngắt dòng ở đầu đối tượng Box hay không, để dòng được gói quanh đầu đối tượng box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Ngắt rõ ràng chỉ định liệu có ngắt dòng ở đầu đối tượng Box hay không, để dòng được gói quanh đầu đối tượng box. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Đối số cơ sở

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Trình giả lập toán tử. Khi đúng, hộp và nội dung của nó hoạt động như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. Điều này có nghĩa là, ví dụ, ký tự có thể đóng vai trò là một điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Trình giả lập toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp để tạo thành một toán tử, chẳng hạn như '=='. Giá trị mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Trả về:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Trình giả lập toán tử. Khi đúng, hộp và nội dung của nó hoạt động như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. Điều này có nghĩa là, ví dụ, ký tự có thể đóng vai trò là một điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Trình giả lập toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp để tạo thành một toán tử, chẳng hạn như '=='. Giá trị mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. Khi đúng, không có ngắt dòng nào xảy ra bên trong hộp. Điều này có thể quan trọng đối với các trình giả lập toán tử bao gồm nhiều hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, ngắt dòng có thể xảy ra bên trong hộp. Mặc định: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Trả về:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. Khi đúng, không có ngắt dòng nào xảy ra bên trong hộp. Điều này có thể quan trọng đối với các trình giả lập toán tử bao gồm nhiều hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, ngắt dòng có thể xảy ra bên trong hộp. Mặc định: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Vi phân. Khi đúng, hộp hoạt động như một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Trả về:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Vi phân. Khi đúng, hộp hoạt động như một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

Khi đúng, trình giả lập toán tử này đóng vai trò là một điểm căn chỉnh; nghĩa là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Trả về:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Khi đúng, trình giả lập toán tử này đóng vai trò là một điểm căn chỉnh; nghĩa là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Ngắt rõ ràng chỉ định liệu có ngắt dòng ở đầu đối tượng Box hay không, để dòng được gói quanh đầu đối tượng box. Xác định số của toán tử trên dòng trước của văn bản toán học sẽ được sử dụng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học. Các giá trị khả dụng: 1..255 Mặc định: 0 (không có ngắt rõ ràng)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Trả về:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Ngắt rõ ràng chỉ định liệu có ngắt dòng ở đầu đối tượng Box hay không, để dòng được gói quanh đầu đối tượng box. Xác định số của toán tử trên dòng trước của văn bản toán học sẽ được sử dụng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học. Các giá trị khả dụng: 1..255 Mặc định: 0 (không có ngắt rõ ràng)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |