---
title: PptxException
second_title: Aspose.Slides for Java API 參考
description: 表示一種標準的內部例外類型。
type: docs
url: /zh-hant/com.aspose.slides/pptxexception/
---
**繼承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception)
```
public class PptxException extends OOXMLException
```

表示一種標準的內部例外類型。
## 建構函式

| 建構子 | 描述 |
| --- | --- |
| [PptxException()](#PptxException--) | 預設建構子。 |
| [PptxException(String message)](#PptxException-java.lang.String-) | 允許將訊息加入此例外的建構子。 |
| [PptxException(String message, RuntimeException exception)](#PptxException-java.lang.String-java.lang.RuntimeException-) | 包含訊息與內嵌例外的建構子。 |
### PptxException() {#PptxException--}
```
public PptxException()
```

預設建構子。

### PptxException(String message) {#PptxException-java.lang.String-}
```
public PptxException(String message)
```

允許將訊息加入此例外的建構子。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 訊息 |

### PptxException(String message, RuntimeException exception) {#PptxException-java.lang.String-java.lang.RuntimeException-}
```
public PptxException(String message, RuntimeException exception)
```

包含訊息與內嵌例外的建構子。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 訊息 |
| exception | java.lang.RuntimeException | 原始例外 |