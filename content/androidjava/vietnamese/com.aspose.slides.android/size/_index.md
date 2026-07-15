---
title: Size
second_title: Aspose.Slides for Android qua Java API Reference
description: Lớp dùng để mô tả các kích thước chiều rộng và chiều cao bằng một đơn vị tùy ý.
type: docs
url: /vi/com.aspose.slides.android/size/
---
**Kế thừa:**
java.lang.Object
```
public class Size
```

Lớp dùng để mô tả các kích thước chiều rộng và chiều cao bằng một đơn vị tùy ý.
## Các hàm khởi tạo

| Hành tạo | Mô tả |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Tạo một thể hiện Size mới. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWidth()](#getWidth--) | Lấy chiều rộng của kích thước. |
| [getHeight()](#getHeight--) | Lấy chiều cao của kích thước. |
| [equals(Object obj)](#equals-java.lang.Object-) | Kiểm tra xem kích thước này có bằng một kích thước khác không. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Trả về kích thước dưới dạng chuỗi với định dạng "WxH" |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Tạo một thể hiện Size mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | int | Chiều rộng của kích thước |
| height | int | Chiều cao của kích thước |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Lấy chiều rộng của kích thước.

**Trả về:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```

Lấy chiều cao của kích thước.

**Trả về:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kiểm tra xem kích thước này có bằng một kích thước khác không.

Hai kích thước bằng nhau nếu và chỉ nếu cả chiều rộng và chiều cao của chúng đều bằng nhau.

Đối tượng Size không bao giờ bằng với bất kỳ loại đối tượng nào khác.

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

Trả về kích thước dưới dạng chuỗi với định dạng "WxH"

**Trả về:**
java.lang.String - đại diện chuỗi của kích thước