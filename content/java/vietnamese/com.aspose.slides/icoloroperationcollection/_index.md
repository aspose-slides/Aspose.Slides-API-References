---
title: IColorOperationCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả một bộ sưu tập các phép biến đổi màu.
type: docs
url: /vi/com.aspose.slides/icoloroperationcollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Mô tả một bộ sưu tập các phép biến đổi màu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về hoặc đặt phép biến đổi tại chỉ mục được chỉ định. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Trả về hoặc đặt phép biến đổi tại chỉ mục được chỉ định. |
| [add(int operation, float parameter)](#add-int-float-) | Thêm một phép biến đổi mới vào cuối bộ sưu tập. |
| [add(int operation)](#add-int-) | Thêm một phép biến đổi mới vào cuối bộ sưu tập. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Chèn phép biến đổi mới vào bộ sưu tập. |
| [insert(int position, int operation)](#insert-int-int-) | Chèn phép biến đổi mới vào bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa phép biến đổi màu khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các phép biến đổi màu. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Trả về hoặc đặt phép biến đổi tại chỉ mục được chỉ định. Đọc/ghi [IColorOperation](../../com.aspose.slides/icoloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Trả về hoặc đặt phép biến đổi tại chỉ mục được chỉ định. Đọc/ghi [IColorOperation](../../com.aspose.slides/icoloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Thêm một phép biến đổi mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại phép biến đổi. |
| parameter | float | Tham số của phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã thêm.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Thêm một phép biến đổi mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã thêm.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Chèn phép biến đổi mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà phép biến đổi sẽ được chèn vào. |
| operation | int | Loại phép biến đổi. |
| parameter | float | Tham số của phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã chèn.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Chèn phép biến đổi mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà phép biến đổi sẽ được chèn vào. |
| operation | int | Loại phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã chèn.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phép biến đổi màu khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phép biến đổi màu cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phép biến đổi màu.