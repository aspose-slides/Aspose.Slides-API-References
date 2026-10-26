---
title: ILegend
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn các thuộc tính chú giải của biểu đồ.
type: docs
url: /vi/com.aspose.slides/ilegend/
---
**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Biểu diễn các thuộc tính của chú giải biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOverlay()](#getOverlay--) | Xác định xem các thành phần biểu đồ khác có được phép chồng lên chú giải hay không. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Xác định xem các thành phần biểu đồ khác có được phép chồng lên chú giải hay không. |
| [getPosition()](#getPosition--) | Xác định vị trí của chú giải trên biểu đồ. |
| [setPosition(int value)](#setPosition-int-) | Xác định vị trí của chú giải trên biểu đồ. |
| [getFormat()](#getFormat--) | Trả về định dạng của chú giải. |
| [getEntries()](#getEntries--) | Lấy các mục của chú giải. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Xác định xem các thành phần biểu đồ khác có được phép chồng lên chú giải hay không. Đọc/ghi boolean.

**Returns:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Xác định xem các thành phần biểu đồ khác có được phép chồng lên chú giải hay không. Đọc/ghi boolean.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Xác định vị trí của chú giải trên biểu đồ. Các giá trị khác NaN của các thuộc tính X, Y, Width, Heigt ghi đè hiệu lực của thuộc tính này. Đọc/ghi [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Xác định vị trí của chú giải trên biểu đồ. Các giá trị khác NaN của các thuộc tính X, Y, Width, Heigt ghi đè hiệu lực của thuộc tính này. Đọc/ghi [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Trả về định dạng của chú giải. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Returns:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Lấy các mục của chú giải. Chỉ đọc [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Returns:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)