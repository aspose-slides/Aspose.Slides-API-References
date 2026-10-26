---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho kích thước và hướng của một slide.
type: docs
url: /vi/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Đại diện cho kích thước và hướng của một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSize()](#getSize--) | Lấy kích thước slide tính bằng điểm. |
| [getType()](#getType--) | Lấy loại kích thước slide. |
| [getOrientation()](#getOrientation--) | Lấy hoặc đặt hướng slide. |
| [setOrientation(int value)](#setOrientation-int-) | Lấy hoặc đặt hướng slide. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Đặt kích thước slide theo loại và tỷ lệ nội dung hiện có. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Đặt kích thước slide một cách rõ ràng và tỷ lệ nội dung hiện có. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Lấy kích thước slide tính bằng điểm.

--------------------

Gán một giá trị mới sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

Lấy loại kích thước slide.

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize theo các kích thước đã định sẵn, trong khi vẫn giữ nguyên \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Trả về:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Lấy hoặc đặt hướng slide.

--------------------

Thay đổi giá trị này sẽ hoán đổi chiều rộng và chiều cao của slide.

**Trả về:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Lấy hoặc đặt hướng slide.

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
| type | int | Kích thước slide đã định sẵn để áp dụng. |
| scaleType | int | Chế độ tỷ lệ nội dung cần sử dụng. |

--------------------

Gán bất kỳ giá trị nào khác [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) sẽ điều chỉnh \#getSize.getSize dựa trên loại đã chọn, trong khi bảo tồn \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

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
| scaleType | int | Chế độ tỷ lệ nội dung cần sử dụng. |

--------------------

Điều này sẽ đặt lại thuộc tính \#getType.getType thành [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) và thiết lập \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |