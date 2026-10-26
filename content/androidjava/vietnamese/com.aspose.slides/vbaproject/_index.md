---
title: VbaProject
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn dự án VBA với các macro trình chiếu.
type: docs
url: /vi/com.aspose.slides/vbaproject/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Biểu diễn dự án VBA với các macro trình chiếu.
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [VbaProject()](#VbaProject--) | Hàm khởi tạo này tạo dự án VBA mới từ đầu. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Hàm khởi tạo này tải dự án VBA từ biểu diễn nhị phân của container OLE. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Trả về tên của dự án VBA. |
| [getModules()](#getModules--) | Trả về danh sách tất cả các mô-đun được chứa trong dự án VBA. |
| [getReferences()](#getReferences--) | Trả về danh sách tất cả các tham chiếu được chứa trong dự án VBA. |
| [toBinary()](#toBinary--) | Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Chỉ ra liệu VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Hàm khởi tạo này tạo dự án VBA mới từ đầu. Dự án sẽ được tạo trong bảng mã 1252 Windows Latin 1 (ANSI).

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Hàm khởi tạo này tải dự án VBA từ biểu diễn nhị phân của container OLE.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Trả về tên của dự án VBA. String chỉ đọc.

**Trả về:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Trả về danh sách tất cả các mô-đun được chứa trong dự án VBA. [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection) chỉ đọc.

**Trả về:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Trả về danh sách tất cả các tham chiếu được chứa trong dự án VBA. [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection) chỉ đọc.

**Trả về:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE

**Trả về:**
byte[] - Biểu diễn nhị phân của dự án VBA dưới dạng container OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Chỉ ra liệu VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. boolean chỉ đọc.

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptm");
>  try {
>      if (presentation.getVbaProject().isPasswordProtected())
>          System.out.println("The VBAProject '" + presentation.getVbaProject().getName() +
>              "' is protected by password to view project properties.");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
boolean