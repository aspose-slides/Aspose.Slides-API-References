---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Java API Tham chiếu
description: Cho phép tạo tham chiếu dự án VBA qua giao diện COM
type: docs
url: /vi/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Cho phép tạo tham chiếu dự án VBA qua giao diện COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tạo tham chiếu thư viện loại OLE Automation mới. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tạo tham chiếu thư viện loại OLE Automation mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của tham chiếu dự án VBA String |
| libid | java.lang.String | Mã định danh của một thư viện loại Automation String |

**Giá trị trả về:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Tham chiếu thư viện loại OLE Automation mới [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)