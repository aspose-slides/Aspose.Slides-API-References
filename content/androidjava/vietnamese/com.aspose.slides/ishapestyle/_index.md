---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /vi/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Tham chiếu style của hình dạng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLineColor()](#getLineColor--) | Trả về màu viền của hình dạng. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Trả về hoặc đặt chỉ mục cột của đường trong ma trận style. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Trả về hoặc đặt chỉ mục cột của đường trong ma trận style. |
| [getFillColor()](#getFillColor--) | Trả về màu nền của hình dạng. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Trả về hoặc đặt chỉ mục cột của nền trong ma trận style. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Trả về hoặc đặt chỉ mục cột của nền trong ma trận style. |
| [getEffectColor()](#getEffectColor--) | Trả về màu hiệu ứng của hình dạng. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Trả về hoặc đặt chỉ mục cột của hiệu ứng trong ma trận style. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Trả về hoặc đặt chỉ mục cột của hiệu ứng trong ma trận style. |
| [getFontColor()](#getFontColor--) | Trả về màu phông chữ của hình dạng. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Trả về hoặc đặt chỉ mục phông chữ trong một bộ sưu tập phông chữ. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Trả về hoặc đặt chỉ mục phông chữ trong một bộ sưu tập phông chữ. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```


Trả về màu viền của hình dạng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```


Trả về hoặc đặt chỉ mục cột của đường trong ma trận style. Có thể đọc/ghi int.

**Trả về:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```


Trả về hoặc đặt chỉ mục cột của đường trong ma trận style. Có thể đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```


Trả về màu nền của hình dạng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```


Trả về hoặc đặt chỉ mục cột của nền trong ma trận style. 0 nghĩa là không có nền, giá trị dương – chỉ mục trong các style nền của chủ đề, giá trị âm – chỉ mục trong các style nền nền của chủ đề. Có thể đọc/ghi short.

**Trả về:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```


Trả về hoặc đặt chỉ mục cột của nền trong ma trận style. 0 nghĩa là không có nền, giá trị dương – chỉ mục trong các style nền của chủ đề, giá trị âm – chỉ mục trong các style nền nền của chủ đề. Có thể đọc/ghi short.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```


Trả về màu hiệu ứng của hình dạng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```


Trả về hoặc đặt chỉ mục cột của hiệu ứng trong ma trận style. Có thể đọc/ghi long.

**Trả về:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```


Trả về hoặc đặt chỉ mục cột của hiệu ứng trong ma trận style. Có thể đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```


Trả về màu phông chữ của hình dạng. Chỉ đọc [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```


Trả về hoặc đặt chỉ mục phông chữ trong một bộ sưu tập phông chữ. Có thể đọc/ghi [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Trả về:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```


Trả về hoặc đặt chỉ mục phông chữ trong một bộ sưu tập phông chữ. Có thể đọc/ghi [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |