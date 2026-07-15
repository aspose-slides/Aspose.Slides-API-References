---
title: MathPhantom
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một đối tượng toán học ảo ltmphantgt ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó.
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

Đại diện cho một đối tượng toán học ảo (<m:phant>) ảnh hưởng đến bố cục của phần tử con mà không nhất thiết phải hiển thị nó. Một đối tượng ảo có thể ẩn biểu thức cơ sở của mình trong khi vẫn giữ nguyên chiều rộng, chiều cao hoặc độ sâu để căn chỉnh công thức hoặc dành chỗ. Tính hiển thị và hành vi hình học được điều khiển bởi các thuộc tính như Show, ZeroWid, ZeroAsc, ZeroDesc và Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Ẩn nội dung
>  phantom.setZeroWidth(false);     // Giữ nguyên chiều rộng
> ```
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Khởi tạo một thể hiện mới của lớp [MathPhantom](../../com.aspose.slides/mathphantom) sử dụng phần tử toán học cơ sở được chỉ định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getBase()](#getBase--) | Đối số cơ sở |
| [getShow()](#getShow--) | Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [setShow(boolean value)](#setShow-boolean-) | Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không. |
| [getZeroWidth()](#getZeroWidth--) | Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở có nên được coi là zero hay không. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở có nên được coi là zero hay không. |
| [getZeroAsc()](#getZeroAsc--) | Lấy hoặc đặt giá trị cho biết độ lên (chiều cao trên baseline) của phần tử cơ sở có nên được coi là zero hay không. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Lấy hoặc đặt giá trị cho biết độ lên (chiều cao trên baseline) của phần tử cơ sở có nên được coi là zero hay không. |
| [getZeroDesc()](#getZeroDesc--) | Lấy hoặc đặt giá trị cho biết độ hạ (độ sâu dưới baseline) của phần tử cơ sở có nên được coi là zero hay không. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Lấy hoặc đặt giá trị cho biết độ hạ (độ sâu dưới baseline) của phần tử cơ sở có nên được coi là zero hay không. |
| [getTransp()](#getTransp--) | Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [setTransp(boolean value)](#setTransp-boolean-) | Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Thuộc tính ký tự điều khiển |
| [getChildren()](#getChildren--) | Lấy các phần tử con |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Khởi tạo một thể hiện mới của lớp [MathPhantom](../../com.aspose.slides/mathphantom) sử dụng phần tử toán học cơ sở được chỉ định.

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Biểu thức cơ sở [IMathElement](../../com.aspose.slides/imathelement) mà tính hiển thị và bố cục sẽ được điều khiển bởi đối tượng ảo. Phần tử này định nghĩa nội dung có thể bị ẩn hoặc hiển thị, đồng thời vẫn ảnh hưởng đến căn chỉnh hình học của các công thức xung quanh. |

Phần tử ảo được sử dụng để dự trữ hoặc loại bỏ không gian hiển thị của biểu thức cơ sở mà không nhất thiết phải hiển thị nó. Nó tương ứng với phần tử OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final boolean getShow()
```

Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không.

--------------------

Khi false, phần tử cơ sở bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các cài đặt ảo khác. Tương ứng với thuộc tính OMML m:show.

**Trả về:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Lấy hoặc đặt giá trị cho biết phần tử cơ sở có được hiển thị hay không.

--------------------

Khi false, phần tử cơ sở bị ẩn nhưng vẫn có thể chiếm không gian tùy thuộc vào các cài đặt ảo khác. Tương ứng với thuộc tính OMML m:show.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không dự trữ không gian ngang cho phần tử cơ sở. Tương ứng với thuộc tính OMML m:zeroWid.

**Trả về:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Lấy hoặc đặt giá trị cho biết chiều rộng của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không dự trữ không gian ngang cho phần tử cơ sở. Tương ứng với thuộc tính OMML m:zeroWid.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Lấy hoặc đặt giá trị cho biết độ lên (chiều cao trên baseline) của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không nâng baseline của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Trả về:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Lấy hoặc đặt giá trị cho biết độ lên (chiều cao trên baseline) của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không nâng baseline của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroAsc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Lấy hoặc đặt giá trị cho biết độ hạ (độ sâu dưới baseline) của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không hạ baseline của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Trả về:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Lấy hoặc đặt giá trị cho biết độ hạ (độ sâu dưới baseline) của phần tử cơ sở có nên được coi là zero hay không.

--------------------

Khi true, đối tượng ảo không hạ baseline của dòng toán học xung quanh. Tương ứng với thuộc tính OMML m:zeroDesc.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi true, các toán tử và ký hiệu bên trong đối tượng ảo vẫn ảnh hưởng đến khoảng cách toán học xung quanh (giống như khi hiển thị). Khi false, khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

**Trả về:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Lấy hoặc đặt giá trị cho biết đối tượng ảo có trong suốt đối với các quy tắc khoảng cách dựa trên lớp hay không.

--------------------

Khi true, các toán tử và ký hiệu bên trong đối tượng ảo vẫn ảnh hưởng đến khoảng cách toán học xung quanh (giống như khi hiển thị). Khi false, khoảng cách dựa trên lớp bị bỏ qua. Tương ứng với thuộc tính OMML m:transp.

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