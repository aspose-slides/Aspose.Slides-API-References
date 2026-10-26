---
title: IVbaProject
second_title: Aspose.Slides cho Tham chiếu API Java
description: Biểu diễn dự án VBA với macro bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/ivbaproject/
---```
public interface IVbaProject
```

Biểu diễn dự án VBA với macro bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Trả về tên của dự án VBA. |
| [getModules()](#getModules--) | Trả về danh sách tất cả các mô-đun có trong dự án VBA. |
| [getReferences()](#getReferences--) | Trả về danh sách tất cả các tham chiếu có trong dự án VBA. |
| [toBinary()](#toBinary--) | Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE. |
| [isPasswordProtected()](#isPasswordProtected--) | Cho biết liệu VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. |
### getName() {#getName--}
```
public abstract String getName()
```

Trả về tên của dự án VBA. Chỉ đọc String.

**Trả về:**
java.lang.String
### getModules() {#getModules--}
```
public abstract IVbaModuleCollection getModules()
```

Trả về danh sách tất cả các mô-đun có trong dự án VBA. Chỉ đọc [IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection).

**Trả về:**
[IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
### getReferences() {#getReferences--}
```
public abstract IVbaReferenceCollection getReferences()
```

Trả về danh sách tất cả các tham chiếu có trong dự án VBA. Chỉ đọc [IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection).

**Trả về:**
[IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
### toBinary() {#toBinary--}
```
public abstract byte[] toBinary()
```

Trả về biểu diễn nhị phân của dự án VBA dưới dạng container OLE. Chỉ đọc byte[].

**Trả về:**
byte[] - Biểu diễn nhị phân của dự án VBA dưới dạng container OLE
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Cho biết liệu VBAProject có được bảo vệ bằng mật khẩu để xem thuộc tính dự án hay không. Chỉ đọc boolean.

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