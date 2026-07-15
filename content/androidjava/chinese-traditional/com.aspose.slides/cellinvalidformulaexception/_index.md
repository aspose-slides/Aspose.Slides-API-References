---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Android via Java API 參考文件
description: 當計算公式不正確或未被解析時拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/cellinvalidformulaexception/
---
**繼承:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

當計算公式不正確或未被解析時拋出的例外。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例。 |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息。 |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息並參考導致此例外的內部例外。 |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | 初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息以及包含無效公式的儲存格參照。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getReference()](#getReference--) | 取得包含無效公式的儲存格參照。 |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例。

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息並參考導致此例外的內部例外。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| innerException | java.lang.RuntimeException | 導致目前例外的例外。 |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

初始化 [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) 類別的新實例，使用指定的錯誤訊息以及包含無效公式的儲存格參照。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| reference | java.lang.String | 描述對內部例外之參照的字串。 |

### getReference() {#getReference--}
```
public final String getReference()
```

取得包含無效公式的儲存格參照。

**傳回值:**
java.lang.String