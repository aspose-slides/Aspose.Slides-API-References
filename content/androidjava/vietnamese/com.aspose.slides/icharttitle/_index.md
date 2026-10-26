---
title: IChartTitle
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho các thuộc tính tiêu đề biểu đồ.
type: docs
url: /vi/com.aspose.slides/icharttitle/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Đại diện cho các thuộc tính tiêu đề biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOverlay()](#getOverlay--) | Xác định xem các phần tử biểu đồ khác có được phép chồng lên tiêu đề hay không. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Xác định xem các phần tử biểu đồ khác có được phép chồng lên tiêu đề hay không. |
| [getFormat()](#getFormat--) | Trả về các kiểu tô, đường viền và hiệu ứng của tiêu đề. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Xác định xem các phần tử biểu đồ khác có được phép chồng lên tiêu đề hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Xác định xem các phần tử biểu đồ khác có được phép chồng lên tiêu đề hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Trả về các kiểu tô, đường viền và hiệu ứng của tiêu đề. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)