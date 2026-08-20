---
title: IGradientStop
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn một định dạng gradient.
type: docs
url: /vi/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Biểu diễn một định dạng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float. |
| [setPosition(float value)](#setPosition-float-) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float. |
| [getColor()](#getColor--) | Trả về màu của một gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float.

**Trả về:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Trả về màu của một gradient stop. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)