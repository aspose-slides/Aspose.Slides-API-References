---
title: PptReadException
second_title: Aspose.Slides for Java API 參考
description: 表示在簡報讀取錯誤時拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/pptreadexception/
---
**繼承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception)
```
public class PptReadException extends PptException
```

表示在演示文稿讀取錯誤時拋出的例外。
## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [PptReadException()](#PptReadException--) | 預設建構式。 |
| [PptReadException(String message)](#PptReadException-java.lang.String-) | 允許向此例外添加訊息的建構式。 |
| [PptReadException(String message, Exception exception)](#PptReadException-java.lang.String-java.lang.Exception-) | 用於建立包含訊息與內嵌例外的例外的建構式。 |
### PptReadException() {#PptReadException--}
```
public PptReadException()
```


預設建構式。

### PptReadException(String message) {#PptReadException-java.lang.String-}
```
public PptReadException(String message)
```


允許向此例外添加訊息的建構式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | message |

### PptReadException(String message, Exception exception) {#PptReadException-java.lang.String-java.lang.Exception-}
```
public PptReadException(String message, Exception exception)
```


用於建立包含訊息與內嵌例外的例外的建構式。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.Exception | 原始例外 |