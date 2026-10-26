---
title: CellInvalidReferenceException
second_title: Aspose.Slides 的 Java API 參考
description: 當遇到無效的儲存格參考時拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/cellinvalidreferenceexception/
---
**繼承關係：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

當遇到無效的儲存格參考時拋出的例外。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | 初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。 |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | 使用指定的錯誤訊息初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。 |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | 使用指定的錯誤訊息和導致此例外的內部例外參考來初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。 |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | 使用指定的錯誤訊息和無效的儲存格參考來初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getReference()](#getReference--) | 取得無效的儲存格參考。 |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

使用指定的錯誤訊息初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

使用指定的錯誤訊息和造成此例外的內部例外參考來初始化 [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) 類別的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| innerException | java.lang.RuntimeException | 造成目前例外的內部例外。 |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

使用指定的錯誤訊息和無效的儲存格參考來初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| reference | java.lang.String | 無效的儲存格參考。 |

### getReference() {#getReference--}
```
public final String getReference()
```

取得無效的儲存格參考。

**返回值：**
java.lang.String