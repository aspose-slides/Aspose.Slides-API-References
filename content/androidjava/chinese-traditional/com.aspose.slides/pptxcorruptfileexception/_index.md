---
title: PptxCorruptFileException
second_title: Aspose.Slides for Android via Java API 參考文件
description: 當投影片檔案可能損壞時拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/pptxcorruptfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxReadException](../../com.aspose.slides/pptxreadexception)
```
public class PptxCorruptFileException extends PptxReadException
```

當投影片檔案可能損壞時拋出的例外。

## 建構函式

| Constructor | Description |
| --- | --- |
| [PptxCorruptFileException()](#PptxCorruptFileException--) | 預設建構函式。 |
| [PptxCorruptFileException(String message)](#PptxCorruptFileException-java.lang.String-) | 允許為此例外加入訊息的建構函式。 |
| [PptxCorruptFileException(String message, RuntimeException exception)](#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-) | 用於建立包含訊息與內嵌例外之例外的建構函式。 |
### PptxCorruptFileException() {#PptxCorruptFileException--}
```
public PptxCorruptFileException()
```


預設建構函式。

### PptxCorruptFileException(String message) {#PptxCorruptFileException-java.lang.String-}
```
public PptxCorruptFileException(String message)
```


允許將訊息加入此例外的建構函式。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxCorruptFileException(String message, RuntimeException exception) {#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-}
```
public PptxCorruptFileException(String message, RuntimeException exception)
```


用於建立包含訊息與內嵌例外之例外的建構函式。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | 原始例外 |