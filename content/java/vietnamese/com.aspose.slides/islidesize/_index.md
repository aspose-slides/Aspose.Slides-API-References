---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn kích thước và hướng của một slide.
type: docs
url: /vi/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Biểu diễn kích thước và hướng của một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


Lấy kích thước slide tính bằng điểm.

--------------------

Gán một giá trị mới sẽ đặt lại thuộc tính \#getType.getType về [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```


Lấy loại kích thước slide.

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize theo các kích thước đã định sẵn, đồng thời giữ nguyên \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) hiện tại.

**Trả về:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


Lấy hoặc thiết lập hướng của slide.

--------------------

Thay đổi giá trị này sẽ hoán đổi chiều rộng và chiều cao của slide.

**Trả về:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


Lấy hoặc thiết lập hướng của slide.

--------------------

Thay đổi giá trị này sẽ hoán đổi chiều rộng và chiều cao của slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


Đặt kích thước slide theo loại và tỷ lệ nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Kích thước slide được định sẵn sẽ áp dụng. |
| scaleType | int | Chế độ tỷ lệ nội dung sẽ sử dụng. |

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize dựa trên loại đã chọn, đồng thời bảo tồn \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


Đặt kích thước slide một cách rõ ràng và tỷ lệ nội dung hiện có.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| width | float | Chiều rộng slide mới, tính bằng điểm. |
| height | float | Chiều cao slide mới, tính bằng điểm. |
| scaleType | int | Chế độ tỷ lệ nội dung sẽ sử dụng. |

--------------------

Điều này sẽ đặt lại thuộc tính \#getType.getType về [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |