---
title: VbaProjectFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo dự án VBA thông qua giao diện COM
type: docs
url: /vi/com.aspose.slides/vbaprojectfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IVbaProjectFactory](../../com.aspose.slides/ivbaprojectfactory)
```
public class VbaProjectFactory implements IVbaProjectFactory
```

Cho phép tạo dự án VBA thông qua giao diện COM
## Hàm khởi tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [VbaProjectFactory()](#VbaProjectFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInstance()](#getInstance--) | VBA project factory static instance. |
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


VBA project factory static instance. Chỉ đọc [VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory).

**Trả về:**
[VbaProjectFactory](../../com.aspose.slides/vbaprojectfactory)
### createVbaProject() {#createVbaProject--}
```
public final IVbaProject createVbaProject()
```


Tạo dự án VBA mới.

**Trả về:**
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

**Trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Đọc dự án VBA