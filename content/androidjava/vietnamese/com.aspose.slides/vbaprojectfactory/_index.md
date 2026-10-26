---
title: VbaProjectFactory
second_title: Tham khảo API Java cho Aspose.Slides cho Android
description: Cho phép tạo dự án VBA thông qua giao diện COM
type: docs
url: /vi/com.aspose.slides/vbaprojectfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Cho phép tạo dự án VBA thông qua giao diện COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInstance()](#getInstance--) | Thực thể tĩnh của nhà máy dự án VBA. |
| [createVbaProject()](#createVbaProject--) | Tạo dự án VBA mới. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Đọc dự án VBA từ container OLE. |
### VbaProjectFactory() {#VbaProjectFactory--}
```
public VbaProjectFactory()
```


### getInstance() {#getInstance--}
```
public static VbaProjectFactory getInstance()
```


Thực thể tĩnh của nhà máy dự án VBA. Chỉ đọc [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Giá trị trả về:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Tạo dự án VBA mới.

**Giá trị trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Dự án VBA mới
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public final IVbaProject readVbaProject(byte[] data)
```


Đọc dự án VBA từ container OLE.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] |  |

**Giá trị trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Đọc dự án VBA