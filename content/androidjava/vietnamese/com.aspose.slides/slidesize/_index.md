---
title: SlideSize
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn kích thước và hướng của một trang trình chiếu.
type: docs
url: /vi/com.aspose.slides/slidesize/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Biểu diễn kích thước và hướng của một trang trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSize()](#getSize--) | Lấy kích thước trang trình chiếu tính bằng điểm. |
| [getType()](#getType--) | Lấy loại kích thước trang trình chiếu. |
| [getOrientation()](#getOrientation--) | Lấy hoặc đặt hướng của trang trình chiếu. |
| [setOrientation(int value)](#setOrientation-int-) | Lấy hoặc đặt hướng của trang trình chiếu. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Đặt kích thước trang trình chiếu theo loại và thay đổi tỷ lệ nội dung hiện có. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Đặt kích thước trang trình chiếu một cách rõ ràng và thay đổi tỷ lệ nội dung hiện có. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Lấy kích thước trang trình chiếu tính bằng điểm.

--------------------

Gán một giá trị mới sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và đặt \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Lấy loại kích thước trang trình chiếu.

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize theo các kích thước được định trước, trong khi vẫn giữ nguyên \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Lấy hoặc đặt hướng của trang trình chiếu.

--------------------

Thay đổi giá trị này sẽ đổi chỗ chiều rộng và chiều cao của trang trình chiếu.

**Trả về:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Lấy hoặc đặt hướng của trang trình chiếu.

--------------------

Thay đổi giá trị này sẽ đổi chỗ chiều rộng và chiều cao của trang trình chiếu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Đặt kích thước trang trình chiếu theo loại và thay đổi tỷ lệ nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kích thước trang trình chiếu được định trước để áp dụng. |
| scaleType | int | Chế độ thay đổi tỷ lệ nội dung cần sử dụng. |

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize dựa trên loại đã chọn, trong khi vẫn giữ \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Đặt kích thước trang trình chiếu một cách rõ ràng và thay đổi tỷ lệ nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng trang trình chiếu mới, tính bằng điểm. |
| height | float | Chiều cao trang trình chiếu mới, tính bằng điểm. |
| scaleType | int | Chế độ thay đổi tỷ lệ nội dung cần sử dụng. |

--------------------

Điều này sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và đặt \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |