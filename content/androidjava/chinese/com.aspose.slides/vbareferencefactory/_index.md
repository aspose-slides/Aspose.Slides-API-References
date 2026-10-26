---
title: VbaReferenceFactory
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 允许通过 COM 接口创建 VBA 项目引用
type: docs
url: /zh/com.aspose.slides/vbareferencefactory/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

允许通过 COM 接口创建 VBA 项目引用
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getInstance()](#getInstance--) | VBA 项目引用工厂的静态实例。 |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | 创建新的 OLE Automation 类型库引用。 |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


VBA 项目引用工厂的静态实例。只读 [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)。

**返回：**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


创建新的 OLE Automation 类型库引用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**返回：**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - 新的 OLE Automation 类型库引用