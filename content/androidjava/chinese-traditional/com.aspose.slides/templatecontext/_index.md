---
title: TemplateContext
second_title: Aspose.Slides Android 版 Java API 參考
description: 表示模板引擎的模型物件介面。
type: docs
url: /zh-hant/com.aspose.slides/templatecontext/
---
**繼承：**
java.lang.Object
```
public final class TemplateContext<TObject>
```

表示模板引擎的模型物件介面。
## 方法

| 方法 | 描述 |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | 建立子範本上下文。 |
| [getObject()](#getObject--) | 傳回模型物件。 |
| [getOutput()](#getOutput--) | 傳回主文件的輸出元素集合。 |
| [getLocal()](#getLocal--) | 傳回當前範本上下文的本機儲存區。 |
| [getGlobal()](#getGlobal--) | 傳回主文件的全域儲存區。 |
### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```


建立子範本上下文。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| subModel | TSubModel | 子模型物件。 |

**傳回：**
[TemplateContext](../../com.aspose.slides/templatecontext) - 新的範本上下文，使用給定的模型以及父範本的輸出集合和全域儲存區。
### getObject() {#getObject--}
```
public final TObject getObject()
```


傳回模型物件。唯讀 Object。

**傳回：**
TObject
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


傳回主文件的輸出元素集合。唯讀 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

**傳回：**
[Output](../../com.aspose.slides/output)
### getLocal() {#getLocal--}
```
public final Storage getLocal()
```


傳回當前範本上下文的本機儲存區。唯讀 [Storage](../../com.aspose.slides/storage)。

**傳回：**
[Storage](../../com.aspose.slides/storage)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


傳回主文件的全域儲存區。唯讀 [Storage](../../com.aspose.slides/storage)。

**傳回：**
[Storage](../../com.aspose.slides/storage)