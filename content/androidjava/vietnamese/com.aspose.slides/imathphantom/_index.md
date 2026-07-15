---
title: IMathPhantom
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng toán học ảo ltmphantgt ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó.
type: docs
url: /vi/com.aspose.slides/imathphantom/
---
**Tất cả các Giao Diện Được Thực Hiện:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Đại diện cho một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ sở trong khi vẫn giữ nguyên độ rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dự trữ không gian. Tầm nhìn và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ẩn nội dung
>  phantom.setZeroWidth(false);     // Giữ nguyên độ rộng
> ```

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getShow()](#getShow--) | Lấy hoặc đặt một giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [setShow(boolean value)](#setShow-boolean-) | Lấy hoặc đặt một giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [getZeroWidth()](#getZeroWidth--) | Lấy hoặc đặt một giá trị cho biết độ rộng của phần tử cơ sở nên được coi là 0. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Lấy hoặc đặt một giá trị cho biết độ rộng của phần tử cơ sở nên được coi là 0. |
| [getZeroAsc()](#getZeroAsc--) | Lấy hoặc đặt một giá trị cho biết phần lên (chiều cao trên đường cơ bản) của phần tử cơ sở nên được coi là 0. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Lấy hoặc đặt một giá trị cho biết phần lên (chiều cao trên đường cơ bản) của phần tử cơ sở nên được coi là 0. |
| [getZeroDesc()](#getZeroDesc--) | Lấy hoặc đặt một giá trị cho biết phần hạ (độ sâu dưới đường cơ bản) của phần tử cơ sở nên được coi là 0. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Lấy hoặc đặt một giá trị cho biết phần hạ (độ sâu dưới đường cơ bản) của phần tử cơ sở nên được coi là 0. |
| [getTransp()](#getTransp--) | Lấy hoặc đặt một giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [setTransp(boolean value)](#setTransp-boolean-) | Lấy hoặc đặt một giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Đối số cơ sở

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


Lấy hoặc đặt một giá trị cho biết phần tử cơ sở có được hiển thị hay không.

--------------------

Khi giá trị là false, phần tử cơ sở bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các thiết lập ảo khác. Trực thuộc thuộc tính OMML m:show.

**Trả về:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```


Lấy hoặc đặt một giá trị cho biết phần tử cơ sở có được hiển thị hay không.

--------------------

Khi giá trị là false, phần tử cơ sở bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các thiết lập ảo khác. Trực thuộc thuộc tính OMML m:show.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```


Lấy hoặc đặt một giá trị cho biết độ rộng của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không dành không gian theo chiều ngang cho phần tử cơ sở. Trực thuộc thuộc tính OMML m:zeroWid.

**Trả về:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```


Lấy hoặc đặt một giá trị cho biết độ rộng của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không dành không gian theo chiều ngang cho phần tử cơ sở. Trực thuộc thuộc tính OMML m:zeroWid.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```


Lấy hoặc đặt một giá trị cho biết phần lên (chiều cao trên đường cơ bản) của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không nâng baseline của dòng toán xung quanh. Trực thuộc thuộc tính OMML m:zeroAsc.

**Trả về:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```


Lấy hoặc đặt một giá trị cho biết phần lên (chiều cao trên đường cơ bản) của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không nâng baseline của dòng toán xung quanh. Trực thuộc thuộc tính OMML m:zeroAsc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```


Lấy hoặc đặt một giá trị cho biết phần hạ (độ sâu dưới đường cơ bản) của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không hạ baseline của dòng toán xung quanh. Trực thuộc thuộc tính OMML m:zeroDesc.

**Trả về:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```


Lấy hoặc đặt một giá trị cho biết phần hạ (độ sâu dưới đường cơ bản) của phần tử cơ sở nên được coi là 0.

--------------------

Khi giá trị là true, đối tượng ảo không hạ baseline của dòng toán xung quanh. Trực thuộc thuộc tính OMML m:zeroDesc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```


Lấy hoặc đặt một giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi giá trị là true, các toán tử và ký hiệu bên trong đối tượng ảo vẫn ảnh hưởng đến khoảng cách toán học xung quanh (giống như khi chúng hiển thị). Khi giá trị là false, quy tắc khoảng cách dựa trên lớp bị bỏ qua. Trực thuộc thuộc tính OMML m:transp.

**Trả về:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```


Lấy hoặc đặt một giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi giá trị là true, các toán tử và ký hiệu bên trong đối tượng ảo vẫn ảnh hưởng đến khoảng cách toán học xung quanh (giống như khi chúng hiển thị). Khi giá trị là false, quy tắc khoảng cách dựa trên lớp bị bỏ qua. Trực thuộc thuộc tính OMML m:transp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |