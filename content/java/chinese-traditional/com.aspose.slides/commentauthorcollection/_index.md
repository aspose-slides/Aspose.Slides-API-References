---
title: CommentAuthorCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示一個評論作者的集合。
type: docs
url: /zh-hant/com.aspose.slides/commentauthorcollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面:**  
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)  
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

表示一個評論作者的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 取得實際包含於集合中的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 在集合末端新增作者。 |
| [toArray()](#toArray--) | 建立並傳回包含所有作者的陣列。 |
| [findByName(String name)](#findByName-java.lang.String-) | 依名稱在集合中尋找作者。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 依名稱與縮寫在集合中尋找作者。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的作者。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 移除集合中第一個出現的指定作者。 |
| [clear()](#clear--) | 移除集合中所有作者。 |
| [iterator()](#iterator--) | 傳回一個遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。唯讀 Object。 |

### size() {#size--}
```
public final int size()
```

取得實際包含於集合中的元素數量。唯讀 int.

**傳回值:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

取得指定索引處的元素。唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

在集合末端新增作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 新作者的名稱。 |
| initials | java.lang.String | 新作者的縮寫。 |

**傳回值:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新的 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 物件。

### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

建立並傳回包含所有作者的陣列。

**傳回值:**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) 陣列

### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

依名稱在集合中尋找作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要尋找的作者名稱。 |

**傳回值:**
com.aspose.slides.ICommentAuthor[] - 作者或 null。

### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

依名稱與縮寫在集合中尋找作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要尋找的作者名稱。 |
| initials | java.lang.String | 要尋找的作者縮寫。 |

**傳回值:**
com.aspose.slides.ICommentAuthor[] - 作者或 null。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

移除集合中第一個出現的指定作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要從集合中移除的作者。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中所有作者。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

傳回一個遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 整個集合的 java.util.Iterator。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回值:**
java.lang.Object