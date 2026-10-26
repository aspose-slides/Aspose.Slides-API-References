---
title: ILegend
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các thuộc tính chú giải của biểu đồ.
type: docs
url: /vi/com.aspose.slides/ilegend/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Biểu diễn các thuộc tính chú giải của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOverlay()](#getOverlay--) | Determines whether other chart elements shall be allowed to overlap legend. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Determines whether other chart elements shall be allowed to overlap legend. |
| [getPosition()](#getPosition--) | Specifies the position of the legend on a chart. |
| [setPosition(int value)](#setPosition-int-) | Specifies the position of the legend on a chart. |
| [getFormat()](#getFormat--) | Returns the format of a legend. |
| [getEntries()](#getEntries--) | Gets legend entries. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Xác định liệu các phần tử biểu đồ khác có được phép chồng lên chú giải hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Xác định liệu các phần tử biểu đồ khác có được phép chồng lên chú giải hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Xác định vị trí của chú giải trên biểu đồ. Các giá trị không phải NaN của các thuộc tính X, Y, Width, Heigt sẽ ghi đè tác dụng của thuộc tính này. Đọc/ghi [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Trả về:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Xác định vị trí của chú giải trên biểu đồ. Các giá trị không phải NaN của các thuộc tính X, Y, Width, Heigt sẽ ghi đè tác dụng của thuộc tính này. Đọc/ghi [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Trả về định dạng của một chú giải. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Lấy các mục chú giải. Chỉ đọc [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Trả về:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)