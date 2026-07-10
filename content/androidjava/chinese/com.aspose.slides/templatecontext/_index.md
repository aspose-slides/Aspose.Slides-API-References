---
title: TemplateContext
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示模板引擎的模型对象接口。
type: docs
url: /zh/com.aspose.slides/templatecontext/
---
**继承：**
java.lang.Object
```
public final class TemplateContext<TObject>
```

表示模板引擎的模型对象接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | Creates a child template context. |
| [getObject()](#getObject--) | Returns the model object. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the host document. |
| [getLocal()](#getLocal--) | Returns local storage of the current template context. |
| [getGlobal()](#getGlobal--) | Returns global storage of the host document. |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


创建子模板上下文。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subModel | TSubModel | 子模型对象。 |

**返回值：**
[TemplateContext](../../com.aspose.slides/templatecontext) - 使用给定模型以及父级的输出集合和全局存储的新模板上下文。
### getObject() {#getObject--}
```
public final TObject getObject()
```


返回模型对象。只读 Object。

**返回值：**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


返回主文档的输出元素集合。只读 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

**返回值：**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


返回当前模板上下文的本地存储。只读 [Storage](../../com.aspose.slides/storage)。

**返回值：**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


返回主文档的全局存储。只读 [Storage](../../com.aspose.slides/storage)。

**返回值：**
[Storage](../../com.aspose.slides/storage)