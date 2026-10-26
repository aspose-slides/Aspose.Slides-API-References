---
title: IVbaReferenceFactory
second_title: Aspose.Slides 适用于 Android 的 Java API 参考
description: 允许通过 COM 接口创建 VBA 项目引用
type: docs
url: /zh/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

允许通过 COM 接口创建 VBA 项目引用
## 方法

| 方法 | 描述 |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 创建新的 OLE Automation 类型库引用。 |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


创建新的 OLE Automation 类型库引用。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | VBA 项目引用的名称 String |
| libid | java.lang.String | Automation 类型库的标识符 String |

**返回值:**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新的 OLE Automation 类型库引用 [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)