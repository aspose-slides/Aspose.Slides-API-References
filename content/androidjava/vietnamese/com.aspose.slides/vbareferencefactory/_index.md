---
title: VbaReferenceFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo tham chiếu dự án VBA thông qua giao diện COM
type: docs
url: /vi/com.aspose.slides/vbareferencefactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Cho phép tạo tham chiếu dự án VBA thông qua giao diện COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInstance()](#getInstance--) | Thực thể tĩnh của nhà máy tham chiếu dự án VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tạo tham chiếu thư viện kiểu OLE Automation mới. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Thực thể tĩnh của nhà máy tham chiếu dự án VBA. Chỉ đọc [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Trả về:**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tạo tham chiếu thư viện kiểu OLE Automation mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Trả về:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Tham chiếu thư viện kiểu OLE Automation mới