---
title: MathBox
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định việc đóng gói logic của phần tử toán học.
type: docs
url: /vi/com.aspose.slides/mathbox/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Xác định việc đóng gói (boxing) logic của phần tử toán học. Ví dụ, một đối tượng được đóng gói có thể hoạt động như một bộ mô phỏng toán tử có hoặc không có điểm căn chỉnh, có thể hoạt động như một điểm ngắt dòng, hoặc được nhóm lại để không cho phép ngắt dòng bên trong. Ví dụ, toán tử "==" nên được đóng gói để ngăn ngắt dòng.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Khởi tạo MathBox với phần tử được chỉ định làm đối số |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getOperatorEmulator()](#getOperatorEmulator--) | Bộ mô phỏng toán tử. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Bộ mô phỏng toán tử. |
| [getNoBreak()](#getNoBreak--) | Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. |
| [getDifferential()](#getDifferential--) | Vi phân Khi true, hộp đóng vai trò là một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Vi phân Khi true, hộp đóng vai trò là một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Khi true, bộ mô phỏng toán tử này phục vụ như một điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Khi true, bộ mô phỏng toán tử này phục vụ như một điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. |
| [getExplicitBreak()](#getExplicitBreak--) | Ngắt rõ ràng chỉ định liệu có một ngắt dòng ở đầu đối tượng Box không; nếu có, dòng sẽ gập lại ở đầu đối tượng box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Ngắt rõ ràng chỉ định liệu có một ngắt dòng ở đầu đối tượng Box không; nếu có, dòng sẽ gập lại ở đầu đối tượng box. |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Khởi tạo MathBox với phần tử được chỉ định làm đối số

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ sở mà hộp được áp dụng. Có thể null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Đối số cơ sở

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Giá trị trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Bộ mô phỏng toán tử. Khi true, hộp và nội dung của nó hoạt động như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. Điều này có nghĩa, ví dụ, ký tự có thể phục vụ như một điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Bộ mô phỏng toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp thành một toán tử, như '=='. Giá trị mặc định: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Giá trị trả về:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Bộ mô phỏng toán tử. Khi true, hộp và nội dung của nó hoạt động như một toán tử duy nhất và kế thừa các thuộc tính của một toán tử. Điều này có nghĩa, ví dụ, ký tự có thể phục vụ như một điểm ngắt dòng và có thể được căn chỉnh với các toán tử khác. Bộ mô phỏng toán tử thường được sử dụng khi một hoặc nhiều glyph kết hợp thành một toán tử, như '=='. Giá trị mặc định: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. Khi true, không có ngắt dòng nào có thể xảy ra bên trong hộp. Điều này có thể quan trọng đối với các bộ mô phỏng toán tử gồm hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, có thể xảy ra ngắt trong hộp. Mặc định: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Giá trị trả về:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Không ngắt. Thuộc tính này xác định thuộc tính "unbreakable" trên hộp đối tượng. Khi true, không có ngắt dòng nào có thể xảy ra bên trong hộp. Điều này có thể quan trọng đối với các bộ mô phỏng toán tử gồm hơn một toán tử nhị phân. Khi phần tử này không được chỉ định, có thể xảy ra ngắt trong hộp. Mặc định: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Vi phân Khi true, hộp đóng vai trò là một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
```

**Giá trị trả về:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```


Vi phân Khi true, hộp đóng vai trò là một vi phân (ví dụ, \\ud835\\udc51\\ud835\\udc65 trong một tích phân), và nhận khoảng cách ngang thích hợp cho vi phân toán học. Mặc định: false

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
public final boolean getAlignmentPoint()
```


Khi true, bộ mô phỏng toán tử này phục vụ như một điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Giá trị trả về:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Khi true, bộ mô phỏng toán tử này phục vụ như một điểm căn chỉnh; tức là, các điểm căn chỉnh được chỉ định trong các phương trình khác có thể được căn chỉnh với nó. Mặc định: false

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
public final byte getExplicitBreak()
```


Ngắt rõ ràng chỉ định liệu có một ngắt dòng ở đầu đối tượng Box không; nếu có, dòng sẽ gập lại ở đầu đối tượng box. Xác định số thứ tự của toán tử trên dòng trước của văn bản toán học sẽ được dùng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học. Giá trị khả dụng: 1..255 Mặc định: 0 (không có ngắt rõ ràng)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Giá trị trả về:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Ngắt rõ ràng chỉ định liệu có một ngắt dòng ở đầu đối tượng Box không; nếu có, dòng sẽ gập lại ở đầu đối tượng box. Xác định số thứ tự của toán tử trên dòng trước của văn bản toán học sẽ được dùng làm điểm căn chỉnh cho dòng hiện tại của văn bản toán học. Giá trị khả dụng: 1..255 Mặc định: 0 (không có ngắt rõ ràng)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Giá trị trả về:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Thuộc tính ký tự điều khiển

**Giá trị trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps