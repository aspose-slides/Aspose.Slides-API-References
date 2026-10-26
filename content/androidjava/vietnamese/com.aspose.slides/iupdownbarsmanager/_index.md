---
title: IUpDownBarsManager
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu.
type: docs
url: /vi/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu.
## Phương thức

| Method | Description |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | Trả về định dạng của các thanh lên. |
| [getDownBarsFormat()](#getDownBarsFormat--) | Trả về định dạng của các thanh xuống. |
| [hasUpDownBars()](#hasUpDownBars--) | Xác định xem biểu đồ có các thanh lên/xuống hay không. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | Xác định xem biểu đồ có các thanh lên/xuống hay không. |
| [getGapWidth()](#getGapWidth--) | Trả về hoặc đặt độ rộng khoảng cách. |
| [setGapWidth(int value)](#setGapWidth-int-) | Trả về hoặc đặt độ rộng khoảng cách. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```

Trả về định dạng của các thanh lên. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```

Trả về định dạng của các thanh xuống. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Xác định xem biểu đồ có các thanh lên/xuống hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```

Xác định xem biểu đồ có các thanh lên/xuống hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Trả về hoặc đặt độ rộng khoảng cách. Đọc/ghi int.

**Trả về:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Trả về hoặc đặt độ rộng khoảng cách. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |