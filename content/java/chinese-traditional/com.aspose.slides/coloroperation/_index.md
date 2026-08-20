---
title: ColorOperation
second_title: Aspose.Slides for Java API 參考
description: 表示用於顏色轉換的不同顏色操作。
type: docs
url: /zh-hant/com.aspose.slides/coloroperation/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

表示用於顏色轉換的不同顏色操作。不可變物件。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 建立新的顏色變換操作。 |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 建立新的顏色變換操作。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getOperationType()](#getOperationType--) | 傳回或設定操作的類型。 |
| [getParameter()](#getParameter--) | 傳回操作的參數。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 ColorOperation 實例是否相等。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式，可用於雜湊演算法與類似雜湊表的資料結構。 |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

建立新的顏色變換操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| op | int | 操作類型。 |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

建立新的顏色變換操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| op | int | 操作類型。 |
| parameter | float | 操作參數。 |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

傳回或設定操作的類型。唯讀 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)。

**傳回值:**
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

傳回操作的參數。唯讀 float。

**傳回值:**
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 ColorOperation 實例是否相等。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前 ColorOperation 比較的 ColorOperation。 |

**傳回值:**
boolean - **true** if the specified ColorOperation is equal to the current ColorOperation; otherwise, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式，可用於雜湊演算法與類似雜湊表的資料結構。

**傳回值:**
int