---
title: IGradientStop
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a gradient format.
type: docs
url: /vi/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

Biểu diễn định dạng gradient.
## Phương thức

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. |
| [getColor()](#getColor--) | Trả về màu của một gradient stop. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float.

**Giá trị trả về:**
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

**Giá trị trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)