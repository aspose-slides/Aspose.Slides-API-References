---
title: MathPhantom
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đ đại diện cho một đối tượng toán học ảo ltmphantgt ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó.
type: docs
url: /vi/com.aspose.slides/mathphantom/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Đại diện cho một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết hiển thị nó. Một phantom có thể ẩn biểu thức cơ sở trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dự trữ không gian. Khả năng hiển thị và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ẩn nội dung
>  phantom.setZeroWidth(false);     // Giữ nguyên chiều rộng
```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp [MathPhantom](../../com.aspose.slides/mathphantom) sử dụng phần tử toán học cơ bản được chỉ định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getShow()](#getShow--) | Lấy hoặc đặt một giá trị cho biết liệu phần tử cơ bản có được hiển thị hay không. |
| [setShow(boolean value)](#setShow-boolean-) | Lấy hoặc đặt một giá trị cho biết liệu phần tử cơ bản có được hiển thị hay không. |
| [getZeroWidth()](#getZeroWidth--) | Lấy hoặc đặt một giá trị cho biết liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Lấy hoặc đặt một giá trị cho biết liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getZeroAsc()](#getZeroAsc--) | Lấy hoặc đặt một giá trị cho biết liệu độ cao trên đường cơ sở (ascent) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Lấy hoặc đặt một giá trị cho biết liệu độ cao trên đường cơ sở (ascent) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getZeroDesc()](#getZeroDesc--) | Lấy hoặc đặt một giá trị cho biết liệu độ sâu dưới đường cơ sở (descent) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Lấy hoặc đặt một giá trị cho biết liệu độ sâu dưới đường cơ sở (descent) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getTransp()](#getTransp--) | Lấy hoặc đặt một giá trị cho biết liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [setTransp(boolean value)](#setTransp-boolean-) | Lấy hoặc đặt một giá trị cho biết liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```


Khởi tạo một thể hiện mới của lớp [MathPhantom](../../com.aspose.slides/mathphantom) sử dụng phần tử toán học cơ bản được chỉ định.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cơ bản [IMathElement](../../com.aspose.slides/imathelement) mà khả năng hiển thị và bố cục sẽ được phantom kiểm soát. Phần tử này xác định nội dung có thể bị ẩn hoặc hiển thị, trong khi vẫn ảnh hưởng đến việc căn chỉnh hình học của các công thức xung quanh. |

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Đối số cơ sở

--------------------

**Trả về:**
boolean
### getShow() {#getShow--}
```
public final boolean getShow()
```


Lấy hoặc đặt một giá trị cho biết liệu phần tử cơ bản có được hiển thị hay không.

--------------------

Khi sai, phần tử cơ bản bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các thiết lập phantom khác. Tương ứng với thuộc tính OMML m:show.

**Trả về:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```


Lấy hoặc đặt một giá trị cho biết liệu phần tử cơ bản có được hiển thị hay không.

--------------------

Khi sai, phần tử cơ bản bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các thiết lập phantom khác. Tương ứng với thuộc tính OMML m:show.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```


Lấy hoặc đặt một giá trị cho biết liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không dự trữ không gian ngang cho phần tử cơ bản. Tương ứng với thuộc tính OMML m:zeroWid.

**Trả về:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```


Lấy hoặc đặt một giá trị cho biết liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không dự trữ không gian ngang cho phần tử cơ bản. Tương ứng với thuộc tính OMML m:zeroWid.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```


Lấy hoặc đặt một giá trị cho biết liệu độ cao trên đường cơ sở (ascent) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không nâng đường cơ sở của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Trả về:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```


Lấy hoặc đặt một giá trị cho biết liệu độ cao trên đường cơ sở (ascent) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không nâng đường cơ sở của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```


Lấy hoặc đặt một giá trị cho biết liệu độ sâu dưới đường cơ sở (descent) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không hạ đường cơ sở của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Trả về:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```


Lấy hoặc đặt một giá trị cho biết liệu độ sâu dưới đường cơ sở (descent) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi đúng, phantom không hạ đường cơ sở của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```


Lấy hoặc đặt một giá trị cho biết liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi đúng, các toán tử và ký hiệu bên trong phantom vẫn ảnh hưởng đến khoảng cách toán học xung quanh phantom (giống như khi chúng hiển thị). Khi sai, khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

**Trả về:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```


Lấy hoặc đặt một giá trị cho biết liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi đúng, các toán tử và ký hiệu bên trong phantom vẫn ảnh hưởng đến khoảng cách toán học xung quanh phantom (giống như khi chúng hiển thị). Khi sai, khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Thuộc tính ký tự điều khiển

**Trả về:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Lấy các phần tử con

**Trả về:**
com.aspose.slides.IMathElement[]