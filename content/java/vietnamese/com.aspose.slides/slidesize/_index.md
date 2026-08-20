---
title: SlideSize
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn kích thước và hướng của slide.
type: docs
url: /vi/com.aspose.slides/slidesize/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Biểu diễn kích thước và hướng của slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSize()](#getSize--) | Lấy kích thước slide tính bằng điểm. |
| [getType()](#getType--) | Lấy loại kích thước slide. |
| [getOrientation()](#getOrientation--) | Lấy hoặc đặt hướng của slide. |
| [setOrientation(int value)](#setOrientation-int-) | Lấy hoặc đặt hướng của slide. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Đặt kích thước slide theo loại và thu phóng nội dung hiện có. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Đặt kích thước slide một cách rõ ràng và thu phóng nội dung hiện có. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Lấy kích thước slide tính bằng điểm.

--------------------

Gán một giá trị mới sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


Lấy loại kích thước slide.

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize theo các kích thước đã định nghĩa trước, đồng thời giữ nguyên \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) hiện tại.

**Trả về:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Lấy hoặc đặt hướng của slide.

--------------------

Thay đổi giá trị này sẽ hoán đổi chiều rộng và chiều cao của slide.

**Trả về:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Lấy hoặc đặt hướng của slide.

--------------------

Thay đổi giá trị này sẽ hoán đổi chiều rộng và chiều cao của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Đặt kích thước slide theo loại và thu phóng nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại kích thước slide đã định sẵn để áp dụng. |
| scaleType | int | Chế độ thu phóng nội dung cần sử dụng. |

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize dựa trên loại đã chọn, đồng thời bảo tồn \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Đặt kích thước slide một cách rõ ràng và thu phóng nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng slide mới, tính bằng điểm. |
| height | float | Chiều cao slide mới, tính bằng điểm. |
| scaleType | int | Chế độ thu phóng nội dung cần sử dụng. |

--------------------

Điều này sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |