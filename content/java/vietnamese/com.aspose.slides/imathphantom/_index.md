---
title: IMathPhantom
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một đối tượng toán học ảo ltmphantgt, ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó.
type: docs
url: /vi/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Biểu diễn một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một phantom có thể ẩn biểu thức cơ bản trong khi giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dự trữ không gian. Tính năng hiển thị và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ẩn nội dung
>  phantom.setZeroWidth(false);     // Giữ lại độ rộng
```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Tham số cơ bản |
| [getShow()](#getShow--) | Lấy hoặc đặt giá trị chỉ ra liệu phần tử cơ bản có được hiển thị hay không. |
| [setShow(boolean value)](#setShow-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu phần tử cơ bản có được hiển thị hay không. |
| [getZeroWidth()](#getZeroWidth--) | Lấy hoặc đặt giá trị chỉ ra liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getZeroAsc()](#getZeroAsc--) | Lấy hoặc đặt giá trị chỉ ra liệu độ lên (chiều cao trên đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu độ lên (chiều cao trên đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getZeroDesc()](#getZeroDesc--) | Lấy hoặc đặt giá trị chỉ ra liệu độ hạ (độ sâu dưới đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu độ hạ (độ sâu dưới đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không. |
| [getTransp()](#getTransp--) | Lấy hoặc đặt giá trị chỉ ra liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [setTransp(boolean value)](#setTransp-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Tham số cơ bản

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Trả về:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```


Lấy hoặc đặt giá trị chỉ ra liệu phần tử cơ bản có được hiển thị hay không.

--------------------

Khi false, phần tử cơ bản bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các cài đặt phantom khác. Tương ứng với thuộc tính OMML m:show.

**Trả về:**  
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu phần tử cơ bản có được hiển thị hay không.

--------------------

Khi false, phần tử cơ bản bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các cài đặt phantom khác. Tương ứng với thuộc tính OMML m:show.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


Lấy hoặc đặt giá trị chỉ ra liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không giữ lại không gian ngang cho phần tử cơ bản. Tương ứng với thuộc tính OMML m:zeroWid.

**Trả về:**  
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu chiều rộng của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không giữ lại không gian ngang cho phần tử cơ bản. Tương ứng với thuộc tính OMML m:zeroWid.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


Lấy hoặc đặt giá trị chỉ ra liệu độ lên (chiều cao trên đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không nâng đường cơ sở của dòng toán xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Trả về:**  
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu độ lên (chiều cao trên đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không nâng đường cơ sở của dòng toán xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


Lấy hoặc đặt giá trị chỉ ra liệu độ hạ (độ sâu dưới đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không hạ đường cơ sở của dòng toán xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Trả về:**  
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu độ hạ (độ sâu dưới đường cơ sở) của phần tử cơ bản có được coi là bằng 0 hay không.

--------------------

Khi true, phantom không hạ đường cơ sở của dòng toán xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


Lấy hoặc đặt giá trị chỉ ra liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi true, các toán tử và ký hiệu bên trong phantom vẫn ảnh hưởng đến khoảng cách toán học xung quanh phantom (giống như khi chúng hiển thị). Khi false, quy tắc khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

**Trả về:**  
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu phantom có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi true, các toán tử và ký hiệu bên trong phantom vẫn ảnh hưởng đến khoảng cách toán học xung quanh phantom (giống như khi chúng hiển thị). Khi false, quy tắc khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |