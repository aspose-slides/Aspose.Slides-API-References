---
title: IShapeStyle
second_title: Aspose.Slides for Java Tham chiếu API
description: Đại diện tham chiếu kiểu dáng hình.
type: docs
url: /vi/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Tham chiếu kiểu dáng của hình.
## Phương thức

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Trả về màu viền của hình. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Trả về hoặc đặt chỉ mục cột của đường trong ma trận kiểu dáng. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Trả về hoặc đặt chỉ mục cột của đường trong ma trận kiểu dáng. |
| [getFillColor()](#getFillColor--) | Trả về màu tô đầy của hình. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Trả về hoặc đặt chỉ mục cột tô đầy của hình trong ma trận kiểu dáng. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Trả về hoặc đặt chỉ mục cột tô đầy của hình trong ma trận kiểu dáng. |
| [getEffectColor()](#getEffectColor--) | Trả về màu hiệu ứng của hình. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Trả về hoặc đặt chỉ mục cột hiệu ứng của hình trong ma trận kiểu dáng. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Trả về hoặc đặt chỉ mục cột hiệu ứng của hình trong ma trận kiểu dáng. |
| [getFontColor()](#getFontColor--) | Trả về màu phông chữ của hình. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Trả về hoặc đặt chỉ mục phông chữ của hình trong bộ sưu tập phông. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Trả về hoặc đặt chỉ mục phông chữ của hình trong bộ sưu tập phông. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Trả về màu viền của hình. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Trả về hoặc đặt chỉ mục cột của đường trong ma trận kiểu dáng. Đọc/ghi int.

**Trả về:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Trả về hoặc đặt chỉ mục cột của đường trong ma trận kiểu dáng. Đọc/ghi int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Trả về màu tô đầy của hình. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Trả về hoặc đặt chỉ mục cột tô đầy của hình trong ma trận kiểu dáng. 0 có nghĩa là không tô, giá trị dương - chỉ mục trong kiểu tô của chủ đề, giá trị âm - chỉ mục trong kiểu nền của chủ đề. Đọc/ghi short.

**Trả về:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Trả về hoặc đặt chỉ mục cột tô đầy của hình trong ma trận kiểu dáng. 0 có nghĩa là không tô, giá trị dương - chỉ mục trong kiểu tô của chủ đề, giá trị âm - chỉ mục trong kiểu nền của chủ đề. Đọc/ghi short.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Trả về màu hiệu ứng của hình. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Trả về hoặc đặt chỉ mục cột hiệu ứng của hình trong ma trận kiểu dáng. Đọc/ghi long.

**Trả về:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Trả về hoặc đặt chỉ mục cột hiệu ứng của hình trong ma trận kiểu dáng. Đọc/ghi long.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Trả về màu phông chữ của hình. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Trả về hoặc đặt chỉ mục phông chữ của hình trong bộ sưu tập phông. Đọc/ghi [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Trả về:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Trả về hoặc đặt chỉ mục phông chữ của hình trong bộ sưu tập phông. Đọc/ghi [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |