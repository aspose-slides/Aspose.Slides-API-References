---
title: IColorOperationCollection
second_title: Aspose.Slides for Android qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các thao tác biến đổi màu.
type: docs
url: /vi/com.aspose.slides/icoloroperationcollection/
---
**Tất cả Các Giao Diện Được Thực Thi:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Biểu diễn một bộ sưu tập các thao tác biến đổi màu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về hoặc đặt thao tác tại vị trí chỉ định. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Trả về hoặc đặt thao tác tại vị trí chỉ định. |
| [add(int operation, float parameter)](#add-int-float-) | Thêm một thao tác mới vào cuối bộ sưu tập. |
| [add(int operation)](#add-int-) | Thêm một thao tác mới vào cuối bộ sưu tập. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Chèn thao tác mới vào bộ sưu tập. |
| [insert(int position, int operation)](#insert-int-int-) | Chèn thao tác mới vào bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa thao tác màu khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các thao tác màu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Trả về hoặc đặt thao tác tại vị trí chỉ định. Đọc/ghi [IColorOperation](../../com.aspose.slides/icoloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Trả về hoặc đặt thao tác tại vị trí chỉ định. Đọc/ghi [IColorOperation](../../com.aspose.slides/icoloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Thêm một thao tác mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Kiểu thao tác. |
| parameter | float | Tham số của thao tác. |

**Giá trị trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã thêm.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Thêm một thao tác mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Kiểu thao tác. |

**Giá trị trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã thêm.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Chèn thao tác mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Vị trí mà thao tác sẽ được chèn. |
| operation | int | Kiểu thao tác. |
| parameter | float | Tham số của thao tác. |

**Giá trị trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã chèn.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Chèn thao tác mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Vị trí mà thao tác sẽ được chèn. |
| operation | int | Kiểu thao tác. |

**Giá trị trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã chèn.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa thao tác màu khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của thao tác màu cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các thao tác màu.