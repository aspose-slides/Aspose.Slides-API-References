---
title: VbaProject
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn dự án VBA với macro trình chiếu.
type: docs
url: /vi/com.aspose.slides/vbaproject/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IVbaProject](../../com.aspose.slides/ivbaproject)
```
public final class VbaProject implements IVbaProject
```

Biểu diễn dự án VBA với macro trình chiếu.
## Các hàm khởi tạo

| Constructor | Description |
| --- | --- |
| [VbaProject()](#VbaProject--) | Hàm khởi tạo này tạo dự án VBA mới từ đầu. |
| [VbaProject(byte[] data)](#VbaProject-byte---) | Hàm khởi tạo này tải dự án VBA từ biểu diễn nhị phân của container OLE. |
## Phương thức

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Trả về tên của dự án VBA. |
| [getModules()](#getModules--) | Trả về danh sách tất cả các mô-đun được chứa trong dự án VBA. |
| [getReferences()](#getReferences--) | Trả về danh sách tất cả các tham chiếu được chứa trong dự án VBA. |
| [toBinary()](#toBinary--) | Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE |
| [isPasswordProtected()](#isPasswordProtected--) | Cho biết VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. |
### VbaProject() {#VbaProject--}
```
public VbaProject()
```


Hàm khởi tạo này tạo dự án VBA mới từ đầu. Dự án sẽ được tạo trong 1252 Windows Latin 1 (ANSI) codepage

### VbaProject(byte[] data) {#VbaProject-byte---}
```
public VbaProject(byte[] data)
```


Hàm khởi tạo này tải dự án VBA từ biểu diễn nhị phân của container OLE.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] |  |

### getName() {#getName--}
```
public final String getName()
```


Trả về tên của dự án VBA. Chỉ đọc String.

**Giá trị trả về:**
java.lang.String
### getModules() {#getModules--}
```
public final IVbaModuleCollection getModules()
```


Trả về danh sách tất cả các mô-đun được chứa trong dự án VBA. Chỉ đọc [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Giá trị trả về:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public final IVbaReferenceCollection getReferences()
```


Trả về danh sách tất cả các tham chiếu được chứa trong dự án VBA. Chỉ đọc [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Giá trị trả về:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public final byte[] toBinary()
```


Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE

**Giá trị trả về:**
byte[] - Biểu diễn nhị phân của dự án VBA dưới dạng container OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Cho biết VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. Chỉ đọc  boolean .

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


**Giá trị trả về:**
boolean