---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho các thuộc tính định dạng cho các yếu tố văn bản biểu đồ.
type: docs
url: /vi/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Đại diện cho các thuộc tính định dạng cho các yếu tố văn bản biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Trả về hoặc đặt văn bản neo dọc trong một TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Trả về hoặc đặt văn bản neo dọc trong một TextFrame. |
| [getCenterText()](#getCenterText--) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [setCenterText(byte value)](#setCenterText-byte-) | Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. |
| [getTextVerticalType()](#getTextVerticalType--) | Xác định định hướng văn bản. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Xác định định hướng văn bản. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [getWrapText()](#getWrapText--) | True nếu văn bản được bọc quanh tại các lề của TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True nếu văn bản được bọc quanh tại các lề của TextFrame. |
| [getAutofitType()](#getAutofitType--) | Trả về hoặc đặt chế độ tự động vừa khít của văn bản. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Trả về hoặc đặt chế độ tự động vừa khít của văn bản. |
| [getRotationAngle()](#getRotationAngle--) | Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp bao quanh. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp bao quanh. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Trả về hoặc đặt văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Trả về hoặc đặt văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Nếu NullableBool.True thì văn bản nên được căn giữa trong hộp theo chiều ngang. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Xác định định hướng văn bản. Giá trị kết quả của góc quay trực quan được tóm tắt từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Xác định định hướng văn bản. Giá trị kết quả của góc quay trực quan được tóm tắt từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Trả về:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Trả về:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Trả về:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Trả về:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True nếu văn bản được bọc quanh tại các lề của TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2007/2013). Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True nếu văn bản được bọc quanh tại các lề của TextFrame. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2007/2013). Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Trả về hoặc đặt chế độ tự động vừa khít của văn bản. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Trả về:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Trả về hoặc đặt chế độ tự động vừa khít của văn bản. Việc thay đổi thuộc tính này chỉ có thể tạo ra một ảnh hưởng nhất định đối với các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có hiệu lực khi render). Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp bao quanh. Nếu không chỉ định, góc quay của hình dạng kèm theo sẽ được sử dụng. Nếu được chỉ định, thì nó được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng biệt ngoài góc quay của văn bản. Giá trị kết quả của góc quay trực quan được tóm tắt từ thuộc tính này và kiểu dọc được xác định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Trả về:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Chỉ định góc quay tùy chỉnh được áp dụng cho văn bản trong hộp bao quanh. Nếu không chỉ định, góc quay của hình dạng kèm theo sẽ được sử dụng. Nếu được chỉ định, thì nó được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có góc quay riêng biệt ngoài góc quay của văn bản. Giá trị kết quả của góc quay trực quan được tóm tắt từ thuộc tính này và kiểu dọc được xác định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |