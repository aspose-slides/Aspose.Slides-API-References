---
title: IMarker
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn dấu của một biểu đồ.
type: docs
url: /vi/com.aspose.slides/imarker/
---```
public interface IMarker
```

Biểu diễn dấu của một biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSymbol()](#getSymbol--) | Represents the marker style in a line chart, scatter chart, or radar chart. |
| [setSymbol(int value)](#setSymbol-int-) | Represents the marker style in a line chart, scatter chart, or radar chart. |
| [getFormat()](#getFormat--) | Gets the marker fill. |
| [getSize()](#getSize--) | Represents the marker size in a line chart, scatter chart, or radar chart. |
| [setSize(int value)](#setSize-int-) | Represents the marker size in a line chart, scatter chart, or radar chart. |
### getSymbol() {#getSymbol--}
```
public abstract int getSymbol()
```

Biểu diễn kiểu dấu trong biểu đồ đường, biểu đồ phân tán hoặc biểu đồ radar. Đọc/ghi [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Trả về:**
int
### setSymbol(int value) {#setSymbol-int-}
```
public abstract void setSymbol(int value)
```

Biểu diễn kiểu dấu trong biểu đồ đường, biểu đồ phân tán hoặc biểu đồ radar. Đọc/ghi [MarkerStyleType](../../com.aspose.slides/markerstyletype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Lấy màu nền của dấu. Chỉ-đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getSize() {#getSize--}
```
public abstract int getSize()
```

Biểu diễn kích thước dấu trong biểu đồ đường, biểu đồ phân tán hoặc biểu đồ radar. Đọc/ghi int.

**Trả về:**
int
### setSize(int value) {#setSize-int-}
```
public abstract void setSize(int value)
```

Biểu diễn kích thước dấu trong biểu đồ đường, biểu đồ phân tán hoặc biểu đồ radar. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |