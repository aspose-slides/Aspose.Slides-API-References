---
title: FontSubstRuleCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示字體替換的集合。
type: docs
url: /zh-hant/com.aspose.slides/fontsubstrulecollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)  
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

表示字體替換的集合。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | 將新的字體替換規則加入集合 |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | 移除集合中第一個出現的特定物件。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java.util.Iterator。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值，指示集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回值：**  
int

### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

將新的字體替換規則加入集合

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

移除集合中第一個出現的特定物件。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | 要從集合中移除的字體替換規則。 |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

取得指定索引處的元素。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值：**  
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

傳回遍歷集合的列舉器。

**傳回值：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

傳回整個集合的 java.util.Iterator。

**傳回值：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - 整個集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值，指示集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**傳回值：**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值：**  
java.lang.Object