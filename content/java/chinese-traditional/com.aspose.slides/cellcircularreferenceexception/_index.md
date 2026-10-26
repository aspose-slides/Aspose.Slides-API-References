---
title: CellCircularReferenceException
second_title: Aspose.Slides for Java API 參考
description: 當偵測到一個或多個循環參照，且公式直接或間接參照其自身儲存格時，拋出的例外。
type: docs
url: /zh-hant/com.aspose.slides/cellcircularreferenceexception/
---
**繼承:**  
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

當偵測到一個或多個循環引用，且公式直接或間接參照自己的儲存格時，拋出的例外。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | 初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 使用指定的錯誤訊息初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 使用指定的錯誤訊息和導致此例外的內部例外參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 使用指定的錯誤訊息和循環儲存格參照，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getReference()](#getReference--) | 取得循環儲存格參照。 |

### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

使用指定的錯誤訊息初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

使用指定的錯誤訊息和導致此例外的內部例外參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| innerException | java.lang.RuntimeException | 導致目前例外的例外。 |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

使用指定的錯誤訊息和循環儲存格參照，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| reference | java.lang.String | 一個循環儲存格參照。 |

### getReference() {#getReference--}
```
public final String getReference()
```

取得循環儲存格參照。

**傳回值:**
java.lang.String