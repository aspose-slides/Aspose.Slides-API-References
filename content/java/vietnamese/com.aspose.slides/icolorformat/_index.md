---
title: IColorFormat
second_title: Aspose.Slides cho Tham chiếu API Java
description: Đại diện cho một màu được sử dụng trong bản trình bày.
type: docs
url: /vi/com.aspose.slides/icolorformat/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Đại diện cho một màu được sử dụng trong bản trình bày.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorType()](#getColorType--) | Trả về hoặc đặt phương thức định nghĩa màu. |
| [setColorType(int value)](#setColorType-int-) | Trả về hoặc đặt phương thức định nghĩa màu. |
| [getColor()](#getColor--) | Trả về màu kết quả (với tất cả các chuyển đổi màu đã được áp dụng). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Trả về màu kết quả (với tất cả các chuyển đổi màu đã được áp dụng). |
| [getPresetColor()](#getPresetColor--) | Trả về hoặc đặt cài đặt màu. |
| [setPresetColor(int value)](#setPresetColor-int-) | Trả về hoặc đặt cài đặt màu. |
| [getSystemColor()](#getSystemColor--) | Trả về hoặc đặt màu được xác định bởi bảng màu hệ thống. |
| [setSystemColor(int value)](#setSystemColor-int-) | Trả về hoặc đặt màu được xác định bởi bảng màu hệ thống. |
| [getSchemeColor()](#getSchemeColor--) | Trả về hoặc đặt màu được xác định bởi một sơ đồ màu. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Trả về hoặc đặt màu được xác định bởi một sơ đồ màu. |
| [getR()](#getR--) | Trả về hoặc đặt thành phần màu đỏ của một màu. |
| [setR(byte value)](#setR-byte-) | Trả về hoặc đặt thành phần màu đỏ của một màu. |
| [getG()](#getG--) | Trả về hoặc đặt thành phần màu xanh lá của một màu. |
| [setG(byte value)](#setG-byte-) | Trả về hoặc đặt thành phần màu xanh lá của một màu. |
| [getB()](#getB--) | Trả về hoặc đặt thành phần màu xanh dương của một màu. |
| [setB(byte value)](#setB-byte-) | Trả về hoặc đặt thành phần màu xanh dương của một màu. |
| [getFloatR()](#getFloatR--) | Trả về hoặc đặt thành phần màu đỏ của một màu. |
| [setFloatR(float value)](#setFloatR-float-) | Trả về hoặc đặt thành phần màu đỏ của một màu. |
| [getFloatG()](#getFloatG--) | Trả về hoặc đặt thành phần màu xanh lá của một màu. |
| [setFloatG(float value)](#setFloatG-float-) | Trả về hoặc đặt thành phần màu xanh lá của một màu. |
| [getFloatB()](#getFloatB--) | Trả về hoặc đặt thành phần màu xanh dương của một màu. |
| [setFloatB(float value)](#setFloatB-float-) | Trả về hoặc đặt thành phần màu xanh dương của một màu. |
| [getHue()](#getHue--) | Trả về hoặc đặt thành phần hue của một màu trong biểu diễn HSL. |
| [setHue(float value)](#setHue-float-) | Trả về hoặc đặt thành phần hue của một màu trong biểu diễn HSL. |
| [getSaturation()](#getSaturation--) | Trả về hoặc đặt thành phần độ bão hòa của một màu trong biểu diễn HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Trả về hoặc đặt thành phần độ bão hòa của một màu trong biểu diễn HSL. |
| [getLuminance()](#getLuminance--) | Trả về hoặc đặt thành phần độ sáng của một màu trong biểu diễn HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Trả về hoặc đặt thành phần độ sáng của một màu trong biểu diễn HSL. |
| [getColorTransform()](#getColorTransform--) | Trả về bộ sưu tập các chuyển đổi màu được áp dụng cho một màu. |
| [toString(int format)](#toString-int-) | Trả về một String đại diện cho định dạng màu hiện tại. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Sao chép định dạng màu từ “color”. |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Trả về hoặc đặt phương thức định nghĩa màu. Đọc/ghi [ColorType](../../com.aspose.slides/colortype).

**Trả về:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Trả về hoặc đặt phương thức định nghĩa màu. Đọc/ghi [ColorType](../../com.aspose.slides/colortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Trả về màu kết quả (với tất cả các chuyển đổi màu đã được áp dụng). Đặt màu RGB và xóa mọi chuyển đổi màu. Đọc/ghi java.awt.Color.

**Trả về:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Trả về màu kết quả (với tất cả các chuyển đổi màu đã được áp dụng). Đặt màu RGB và xóa mọi chuyển đổi màu. Đọc/ghi java.awt.Color.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Trả về hoặc đặt cài đặt màu. Đọc/ghi [PresetColor](../../com.aspose.slides/presetcolor).

**Trả về:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Trả về hoặc đặt cài đặt màu. Đọc/ghi [PresetColor](../../com.aspose.slides/presetcolor).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Trả về hoặc đặt màu được xác định bởi bảng màu hệ thống. Đọc/ghi [SystemColor](../../com.aspose.slides/systemcolor).

**Trả về:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Trả về hoặc đặt màu được xác định bởi bảng màu hệ thống. Đọc/ghi [SystemColor](../../com.aspose.slides/systemcolor).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Trả về hoặc đặt màu được xác định bởi một sơ đồ màu. Đọc/ghi [SchemeColor](../../com.aspose.slides/schemecolor).

**Trả về:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Trả về hoặc đặt màu được xác định bởi một sơ đồ màu. Đọc/ghi [SchemeColor](../../com.aspose.slides/schemecolor).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Trả về hoặc đặt thành phần màu đỏ của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Trả về:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Trả về hoặc đặt thành phần màu đỏ của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Trả về hoặc đặt thành phần màu xanh lá của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Trả về:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Trả về hoặc đặt thành phần màu xanh lá của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Trả về hoặc đặt thành phần màu xanh dương của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Trả về:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Trả về hoặc đặt thành phần màu xanh dương của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Trả về hoặc đặt thành phần màu đỏ của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Trả về hoặc đặt thành phần màu đỏ của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Trả về hoặc đặt thành phần màu xanh lá của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Trả về hoặc đặt thành phần màu xanh lá của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Trả về hoặc đặt thành phần màu xanh dương của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Trả về hoặc đặt thành phần màu xanh dương của một màu. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Trả về hoặc đặt thành phần hue của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Trả về hoặc đặt thành phần hue của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Trả về hoặc đặt thành phần độ bão hòa của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Trả về hoặc đặt thành phần độ bão hòa của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Trả về hoặc đặt thành phần độ sáng của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Trả về:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Trả về hoặc đặt thành phần độ sáng của một màu trong biểu diễn HSL. Tất cả các chuyển đổi màu bị bỏ qua. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Trả về bộ sưu tập các chuyển đổi màu được áp dụng cho một màu. Chỉ đọc [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Trả về:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Trả về một String đại diện cho định dạng màu hiện tại.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| format | int | Một kiểu định dạng chuỗi màu. |

**Trả về:**
java.lang.String - Một chuỗi đại diện cho định dạng màu hiện tại.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Sao chép định dạng màu từ "color".

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |