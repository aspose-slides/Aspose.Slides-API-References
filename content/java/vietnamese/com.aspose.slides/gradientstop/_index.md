---
title: GradientStop
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị định dạng gradient.
type: docs
url: /vi/com.aspose.slides/gradientstop/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IGradientStop](../../com.aspose.slides/igradientstop)
```
public final class GradientStop extends PVIObject implements IGradientStop
```

Biểu thị định dạng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. |
| [setPosition(float value)](#setPosition-float-) | Trả về hoặc đặt vị trí (0..1) của một gradient stop. |
| [getColor()](#getColor--) | Trả về màu của một gradient stop. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getPosition() {#getPosition--}
```
public final float getPosition()
```


Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float .

**Trả về:**
float
### setPosition(float value) {#setPosition-float-}
```
public final void setPosition(float value)
```


Trả về hoặc đặt vị trí (0..1) của một gradient stop. Đọc/ghi float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Trả về màu của một gradient stop. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)