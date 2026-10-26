---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /vi/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Đối tượng bất biến chứa các thuộc tính định dạng khung văn bản hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [ITextFrameFormat](../../com.aspose.slides/itextframeformat) để trả về các giá trị định dạng hiệu quả đã áp dụng kế thừa.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Trả về kiểu định dạng văn bản hiệu quả. |
| [getMarginLeft()](#getMarginLeft--) | Trả về lề trái (điểm) trong TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về lề phải (điểm) trong TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về lề trên (điểm) trong TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về lề dưới (điểm) trong TextFrame. |
| [getWrapText()](#getWrapText--) | Trả về liệu văn bản có được bao quanh ở các lề của TextFrame hay không. |
| [getAnchoringType()](#getAnchoringType--) | Trả về văn bản neo dọc trong TextFrame. |
| [getCenterText()](#getCenterText--) | Trả về liệu văn bản có nên được căn giữa trong hộp theo chiều ngang hay không. |
| [getTextVerticalType()](#getTextVerticalType--) | Trả về hướng văn bản. |
| [getAutofitType()](#getAutofitType--) | Trả về chế độ tự động vừa khít văn bản. |
| [getColumnCount()](#getColumnCount--) | Xác định số cột văn bản trong hình chữ nhật bao quanh. |
| [getColumnSpacing()](#getColumnSpacing--) | Xác định khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Trả về kiểu định dạng văn bản hiệu quả. Chỉ đọc [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Trả về:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Trả về lề trái (điểm) trong TextFrame. Chỉ đọc double.

**Trả về:**
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Trả về lề phải (điểm) trong TextFrame. Chỉ đọc double.

**Trả về:**
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Trả về lề trên (điểm) trong TextFrame. Chỉ đọc double.

**Trả về:**
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Trả về lề dưới (điểm) trong TextFrame. Chỉ đọc double.

**Trả về:**
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Trả về liệu văn bản có được bao quanh ở các lề của TextFrame hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Trả về văn bản neo dọc trong TextFrame. Chỉ đọc [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Trả về liệu văn bản có nên được căn giữa trong hộp theo chiều ngang hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Trả về hướng văn bản. Chỉ đọc [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Trả về chế độ tự động vừa khít văn bản. Chỉ đọc [TextAutofitType](../../com.aspose.slides/textautofittype).

**Trả về:**
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Xác định số cột văn bản trong hình chữ nhật bao quanh. Chỉ đọc int.

**Trả về:**
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Xác định khoảng cách giữa các cột văn bản trong khu vực văn bản (đơn vị điểm). Chỉ đọc float.

**Trả về:**
float