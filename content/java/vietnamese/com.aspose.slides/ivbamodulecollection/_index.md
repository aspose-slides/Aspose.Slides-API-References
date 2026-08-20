---
title: IVbaModuleCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một bộ sưu tập các mô-đun dự án VBA.
type: docs
url: /vi/com.aspose.slides/ivbamodulecollection/
---
**Tất cả các giao diện được thực hiện:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Biểu diễn một bộ sưu tập các mô-đun dự án VBA.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Thêm một mô-đun trống mới vào Dự án VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Thêm một mô-đun trống mới vào Dự án VBA.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của mô-đun |

**Giá trị trả về:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Mô-đun đã thêm.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Mô-đun cần xóa khỏi bộ sưu tập. |