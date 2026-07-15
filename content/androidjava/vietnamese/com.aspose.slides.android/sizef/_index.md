---
title: SizeF
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp mô tả kích thước chiều rộng và chiều cao theo một đơn vị bất kỳ với các giá trị dấu phẩy động.
type: docs
url: /vi/com.aspose.slides.android/sizef/
---
**Kế thừa:**
java.lang.Object
```
public class SizeF
```

Lớp mô tả kích thước chiều rộng và chiều cao theo một đơn vị tùy ý với các giá trị dấu phẩy động.
## Constructors

| Constructor | Mô tả |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Tạo một thể hiện SizeF mới. |
## Methods

| Method | Mô tả |
| --- | --- |
| [getWidth()](#getWidth--) | Lấy chiều rộng của kích thước. |
| [getHeight()](#getHeight--) | Lấy chiều cao của kích thước. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kiểm tra xem kích thước này có bằng với một kích thước khác hay không. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Trả về kích thước dưới dạng chuỗi với định dạng  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Tạo một thể hiện SizeF mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng của kích thước |
| height | float | Chiều cao của kích thước |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Lấy chiều rộng của kích thước.

**Trả về:**
float - width
### getHeight() {#getHeight--}
```
public float getHeight()
```


Lấy chiều cao của kích thước.

**Trả về:**
float - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Kiểm tra xem kích thước này có bằng với một kích thước khác hay không.

Hai kích thước bằng nhau nếu và chỉ nếu cả chiều rộng và chiều cao của chúng đều bằng nhau.

Cho mục đích này, các giá trị float của chiều rộng/chiều cao được coi là giống nhau nếu và chỉ nếu phương thức Float#floatToIntBits(float).floatToIntBits(float) trả về cùng một giá trị int khi áp dụng cho mỗi giá trị.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Trả về:**
boolean -  true  nếu các đối tượng bằng nhau,  false  nếu không
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Trả về:**
int
### toString() {#toString--}
```
public String toString()
```


Trả về kích thước dưới dạng chuỗi với định dạng  "WxH" 

**Trả về:**
java.lang.String - string representation of the size