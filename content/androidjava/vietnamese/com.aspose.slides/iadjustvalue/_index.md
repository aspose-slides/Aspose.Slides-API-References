---
title: IAdjustValue
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /vi/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Biểu diễn giá trị điều chỉnh của hình dạng hình học. Các giá trị này ảnh hưởng đến hình dạng của hình.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getRawValue()](#getRawValue--) | Trả về hoặc thiết lập giá trị điều chỉnh "as is". |
| [setRawValue(long value)](#setRawValue-long-) | Trả về hoặc thiết lập giá trị điều chỉnh "as is". |
| [getAngleValue()](#getAngleValue--) | Trả về hoặc thiết lập giá trị, diễn giải nó dưới dạng góc tính bằng độ. |
| [setAngleValue(float value)](#setAngleValue-float-) | Trả về hoặc thiết lập giá trị, diễn giải nó dưới dạng góc tính bằng độ. |
| [getName()](#getName--) | Trả về tên của giá trị điều chỉnh này. |
| [getType()](#getType--) | Trả về kiểu của điều chỉnh hình dạng. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

Trả về hoặc thiết lập giá trị điều chỉnh "as is". Đọc/ghi long.

**Trả về:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

Trả về hoặc thiết lập giá trị điều chỉnh "as is". Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

Trả về hoặc thiết lập giá trị, diễn giải nó dưới dạng góc tính bằng độ. Đọc/ghi float.

**Trả về:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

Trả về hoặc thiết lập giá trị, diễn giải nó dưới dạng góc tính bằng độ. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

Trả về tên của giá trị điều chỉnh này. Chỉ đọc String.

**Trả về:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

Trả về kiểu của điều chỉnh hình dạng. Chỉ đọc [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Trả về:**
int