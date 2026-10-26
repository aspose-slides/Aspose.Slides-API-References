---
title: IGradientStopCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các điểm dừng gradient.
type: docs
url: /vi/com.aspose.slides/igradientstopcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Đại diện cho một tập hợp các điểm dừng gradient.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dừng gradient theo chỉ mục. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điểm dừng gradient tại vị trí chỉ định. |
| [clear()](#clear--) | Xóa tất cả các điểm dừng gradient khỏi tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Trả về điểm dừng gradient theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.lang.Integer | Màu của điểm dừng gradient mới. |

**Giá trị trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong tập hợp.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu của điểm dừng gradient mới. |

**Giá trị trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong tập hợp.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Tạo điểm dừng gradient mới và thêm nó vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu của điểm dừng gradient mới. |

**Giá trị trả về:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Chỉ mục của điểm dừng gradient mới trong tập hợp.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong tập hợp nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| color | java.lang.Integer | Màu của điểm dừng gradient mới. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong tập hợp nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| presetColor | int | Màu của điểm dừng gradient mới. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Tạo điểm dừng gradient mới và chèn nó vào vị trí chỉ định trong tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục trong tập hợp nơi điểm dừng gradient mới sẽ được chèn. |
| position | float | Vị trí của điểm dừng gradient mới. |
| schemeColor | int | Màu của điểm dừng gradient mới. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một điểm dừng gradient tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điểm dừng gradient cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các điểm dừng gradient khỏi tập hợp.