---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Java API 參考
description: 當計算出的公式不正確或未能解析時拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/cellinvalidformulaexception/
---
**繼承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

當計算出的公式不正確或未能解析時拋出的例外。
## 建構函式

| Constructor | Description |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例。 |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並使用指定的錯誤訊息。 |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並提供指定的錯誤訊息以及導致此例外的內部例外參考。 |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並提供指定的錯誤訊息以及包含無效公式的儲存格參考。 |
## 方法

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | 取得包含無效公式的儲存格參考。 |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例。

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並使用指定的錯誤訊息。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並提供指定的錯誤訊息以及導致目前例外的內部例外。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| innerException | java.lang.RuntimeException | 導致目前例外的內部例外。 |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，並提供指定的錯誤訊息以及包含無效公式的儲存格參考。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| reference | java.lang.String | 描述內部例外參考的字串。 |

### getReference() {#getReference--}
```
public final String getReference()
```

取得包含無效公式的儲存格參考。

**回傳：**
java.lang.String