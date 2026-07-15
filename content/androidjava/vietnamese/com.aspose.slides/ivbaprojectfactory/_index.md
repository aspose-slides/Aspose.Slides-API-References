---
title: IVbaProjectFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo dự án VBA thông qua giao diện COM
type: docs
url: /vi/com.aspose.slides/ivbaprojectfactory/
---```
public interface IVbaProjectFactory
```

Cho phép tạo dự án VBA thông qua giao diện COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createVbaProject()](#createVbaProject--) | Tạo dự án VBA mới. |
| [readVbaProject(byte[] data)](#readVbaProject-byte---) | Đọc dự án VBA từ container OLE. |
### createVbaProject() {#createVbaProject--}
```
public abstract IVbaProject createVbaProject()
```

Tạo dự án VBA mới.

**Trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Dự án VBA mới
### readVbaProject(byte[] data) {#readVbaProject-byte---}
```
public abstract IVbaProject readVbaProject(byte[] data)
```

Đọc dự án VBA từ container OLE.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Dữ liệu Ole byte[] |

**Trả về:**
[IVbaProject](../../com.aspose.slides/ivbaproject) - Đọc dự án VBA