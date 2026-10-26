---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho định dạng của một ô bảng.
type: docs
url: /vi/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Đại diện cho định dạng của một ô bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Trả về một đối tượng thuộc tính tô đầy ô. |
| [getBorderLeft()](#getBorderLeft--) | Trả về một đối tượng thuộc tính đường viền bên trái. |
| [getBorderTop()](#getBorderTop--) | Trả về một đối tượng thuộc tính đường viền trên. |
| [getBorderRight()](#getBorderRight--) | Trả về một đối tượng thuộc tính đường viền bên phải. |
| [getBorderBottom()](#getBorderBottom--) | Trả về một đối tượng thuộc tính đường viền dưới. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Trả về một đối tượng thuộc tính đường chéo từ trên-trái đến dưới-phải. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Trả về một đối tượng thuộc tính đường chéo từ dưới-trái đến trên-phải. |
| [getTransparency()](#getTransparency--) | Lấy hoặc đặt độ trong suốt của màu tô đầy. |
| [setTransparency(float value)](#setTransparency-float-) | Lấy hoặc đặt độ trong suốt của màu tô đầy. |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng ô bảng hiệu quả với kế thừa và áp dụng kiểu bảng. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Trả về một đối tượng thuộc tính tô đầy ô. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Trả về một đối tượng thuộc tính đường viền bên trái. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Trả về một đối tượng thuộc tính đường viền trên. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Trả về một đối tượng thuộc tính đường viền bên phải. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Trả về một đối tượng thuộc tính đường viền dưới. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Trả về một đối tượng thuộc tính đường chéo từ trên-trái đến dưới-phải. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Trả về một đối tượng thuộc tính đường chéo từ dưới-trái đến trên-phải. Chỉ đọc [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Lấy hoặc đặt độ trong suốt của màu tô đầy. Đọc/ghi  float .

**Trả về:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Lấy hoặc đặt độ trong suốt của màu tô đầy. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Lấy các thuộc tính định dạng ô bảng hiệu quả với kế thừa và áp dụng kiểu bảng.

**Trả về:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - Một [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).