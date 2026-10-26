---
title: IBackground
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị nền của một slide.
type: docs
url: /vi/com.aspose.slides/ibackground/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Biểu thị nền của một slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về một kiểu nền. |
| [setType(byte value)](#setType-byte-) | Trả về một kiểu nền. |
| [getFillFormat()](#getFillFormat--) | Trả về một FillFormat cho BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | Trả về một EffectFormat cho BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | Trả về một ColorFormat cho BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | Trả về chỉ mục của BackgroundType.Themed trong bộ sưu tập theme nền. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Trả về chỉ mục của BackgroundType.Themed trong bộ sưu tập theme nền. |
| [getEffective()](#getEffective--) | Lấy dữ liệu nền hiệu quả với tính kế thừa được áp dụng. |
### getType() {#getType--}
```
public abstract byte getType()
```


Trả về một kiểu nền. Đọc/ghi [BackgroundType](../../com.aspose.slides/backgroundtype).

**Trả về:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Trả về một kiểu nền. Đọc/ghi [BackgroundType](../../com.aspose.slides/backgroundtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Trả về một FillFormat cho BackgroundType.OwnBackground. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


Trả về một EffectFormat cho BackgroundType.OwnBackground. Chỉ đọc [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Trả về:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


Trả về một ColorFormat cho BackgroundType.Themed. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Trả về một chỉ mục của BackgroundType.Themed trong bộ sưu tập theme nền. 0 có nghĩa là không có nền. 1..999 - chỉ mục. Đọc/ghi int.

**Trả về:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Trả về một chỉ mục của BackgroundType.Themed trong bộ sưu tập theme nền. 0 có nghĩa là không có nền. 1..999 - chỉ mục. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Lấy dữ liệu nền hiệu quả với tính kế thừa được áp dụng.

**Trả về:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).