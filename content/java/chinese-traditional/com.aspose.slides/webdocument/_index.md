---
title: WebDocument
second_title: Aspose.Slides for Java API 參考
description: 代表演示文稿的過渡形式，用於儲存為 Web 格式。
type: docs
url: /zh-hant/com.aspose.slides/webdocument/
---
**繼承：**
java.lang.Object
```
public class WebDocument
```

代表演示文稿的過渡形式，用於儲存為 Web 格式。
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) 建構子。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [save()](#save--) | 儲存文件輸出。 |
| [getInput()](#getInput--) | 返回文件的輸入元素（模板）集合。 |
| [getOutput()](#getOutput--) | 返回文件的輸出元素集合。 |
| [getGlobal()](#getGlobal--) | 返回文件的全域儲存。 |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) 建構子。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | 文件的選項設定。 |

### save() {#save--}
```
public final void save()
```


儲存文件輸出。

### getInput() {#getInput--}
```
public final Input getInput()
```


返回文件的輸入元素（模板）集合。唯讀 [Input](../../com.aspose.slides/input)(\#getInput.getInput)。

**返回：**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


返回文件的輸出元素集合。唯讀 [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)。

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // 放入 "slideMargin" 屬性以供模板使用
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... 設定文件的其他選項，然後保存文件
>   document.save();
> ```

**返回：**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


返回文件的全域儲存。唯讀 [Storage](../../com.aspose.slides/storage)。

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // 放入 "slideMargin" 屬性以供模板使用
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... 設定文件的其他選項，然後保存文件
>   document.save();
> ```

**返回：**
[Storage](../../com.aspose.slides/storage)