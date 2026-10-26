---
title: CellCircularReferenceException
second_title: Aspose.Slides for Android via Java API 參考文件
description: 當檢測到一個或多個循環參考時拋出的例外，該情況下公式直接或間接引用了自身的儲存格。
type: docs
url: /zh-hant/com.aspose.slides/cellcircularreferenceexception/
---
**繼承：**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

當檢測到一個或多個循環參考時拋出的例外，該情況下公式直接或間接引用了自身的儲存格。
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | 初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | 使用指定的錯誤訊息初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | 使用指定的錯誤訊息和導致此例外的內部例外參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | 使用指定的錯誤訊息和循環儲存格參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getReference()](#getReference--) | 取得循環儲存格參考。 |
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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

使用指定的錯誤訊息和導致此例外的內部例外參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| innerException | java.lang.RuntimeException | 導致目前例外的例外。 |
### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

使用指定的錯誤訊息和循環儲存格參考，初始化 [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) 類別的新執行個體。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| message | java.lang.String | 描述錯誤的字串。 |
| reference | java.lang.String | 循環儲存格參考。 |
### getReference() {#getReference--}
```
public final String getReference()
```

取得循環儲存格參考。

**回傳：**
java.lang.String