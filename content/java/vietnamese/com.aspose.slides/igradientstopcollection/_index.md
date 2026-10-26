---
title: IGradientStopCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các điểm dừng gradient.
type: docs
url: /vi/com.aspose.slides/igradientstopcollection/
---
**Tất cả các giao diện được triển khai:**  
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Biểu diễn một bộ sưu tập các điểm dừng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dừng gradient theo chỉ mục. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điểm dừng gradient tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các điểm dừng gradient khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Trả về điểm dừng gradient theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.awt.Color | Màu của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu của điểm dừng gradient mới. |

**Trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong bộ sưu tập.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.awt.Color | Màu của điểm dừng gradient mới. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu của điểm dừng gradient mới. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí đã chỉ định trong bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong bộ sưu tập nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu của điểm dừng gradient mới. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một điểm dừng gradient tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điểm dừng gradient cần xóa. |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các điểm dừng gradient khỏi bộ sưu tập.