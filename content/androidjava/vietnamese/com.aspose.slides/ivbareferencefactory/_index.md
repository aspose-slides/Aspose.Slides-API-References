---
title: IVbaReferenceFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create VBA project references via COM interface
type: docs
url: /vi/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Cho phép tạo tham chiếu dự án VBA thông qua giao diện COM

## Phương thức

| Method | Description |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Tạo mới OLE Automation type library reference. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Tạo mới OLE Automation type library reference.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Tên của VBA project reference String |
| libid | java.lang.String | Mã định danh của Automation type library String |

**Trả về:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - New OLE Automation type library reference [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)