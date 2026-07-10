---
title: WebDocument
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示用于保存为 Web 格式的演示文稿的过渡形式。
type: docs
url: /zh/com.aspose.slides/webdocument/
---
**继承：**
java.lang.Object
```
public class WebDocument
```

表示用于保存为 Web 格式的演示文稿的过渡形式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) 构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [save()](#save--) | 保存文档输出。 |
| [getInput()](#getInput--) | 返回文档的输入元素（模板）集合。 |
| [getOutput()](#getOutput--) | 返回文档的输出元素集合。 |
| [getGlobal()](#getGlobal--) | 返回文档的全局存储。 |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) 构造函数。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | 文档的选项设置。 |

### save() {#save--}
```
public final void save()
```


保存文档输出。

### getInput() {#getInput--}
```
public final Input getInput()
```


返回文档的输入元素（模板）集合。只读 [Input](../../com.aspose.slides/input)(\#getInput.getInput)。

**返回值:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


返回文档的输出元素集合。只读 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // put "slideMargin" property to use from templates
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... set up other options of the document and then save the document
>   document.save();
> ```

**Returns:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()

返回文档的全局存储。只读 [Storage](../../com.aspose.slides/storage).


--------------------

> ```
> 使用此 (#getGlobal.getGlobal) 属性（实现 [Storage](../../com.aspose.slides/storage) 接口）后，
>   可以在模板中稍后使用该属性：
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // put "slideMargin" property to use from templates
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... set up other options of the document and then save the document
>   document.save();
> ```

**返回值:**
[Storage](../../com.aspose.slides/storage)