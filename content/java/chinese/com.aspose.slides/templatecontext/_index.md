---
title: TemplateContext
second_title: Aspose.Slides Java API 参考
description: 表示模板引擎的模型对象接口。
type: docs
url: /zh/com.aspose.slides/templatecontext/
---
**Inheritance:**
java.lang.Object
```
public final class TemplateContext<TObject>
```

表示模板引擎的模型对象接口。

## 方法

| 方法 | 描述 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | 创建子模板上下文。 |
| [getObject()](#getObject--) | 返回模型对象。 |
| [getOutput()](#getOutput--) | 返回宿主文档的输出元素集合。 |
| [getLocal()](#getLocal--) | 返回当前模板上下文的本地存储。 |
| [getGlobal()](#getGlobal--) | 返回宿主文档的全局存储。 |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

创建子模板上下文。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subModel | TSubModel | 子模型对象。 |

**返回:**
[TemplateContext](../../com.aspose.slides/templatecontext) - 新的模板上下文，使用给定的模型以及父级的输出集合和全局存储。
### getObject() {#getObject--}
```
public final TObject getObject()
```

返回模型对象。只读 Object.

**返回:**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

返回宿主文档的输出元素集合。只读 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**返回:**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

返回当前模板上下文的本地存储。只读 [Storage](../../com.aspose.slides/storage).

**返回:**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

返回宿主文档的全局存储。只读 [Storage](../../com.aspose.slides/storage).

**返回:**
[Storage](../../com.aspose.slides/storage)