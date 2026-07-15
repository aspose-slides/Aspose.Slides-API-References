---
title: CommentAuthorCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示一個評論作者的集合。
type: docs
url: /zh-hant/com.aspose.slides/commentauthorcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**全部已實作的介面：**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

表示一個評論作者的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 在集合末尾新增作者。 |
| [toArray()](#toArray--) | 建立並返回包含所有作者的陣列。 |
| [findByName(String name)](#findByName-java.lang.String-) | 依名稱在集合中尋找作者。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 依名稱與姓名縮寫在集合中尋找作者。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的作者。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 移除集合中第一個出現的指定作者。 |
| [clear()](#clear--) | 移除集合中的所有作者。 |
| [iterator()](#iterator--) | 返回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**返回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

取得指定索引處的元素。唯讀 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

在集合末尾新增作者。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 新作者的名稱。 |
| initials | java.lang.String | 新作者的縮寫。 |

**返回值：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新的 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 物件。
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

建立並返回包含所有作者的陣列。

**返回值：**
com.aspose.slides.ICommentAuthor[] - Array of [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

依名稱在集合中尋找作者。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要尋找的作者名稱。 |

**返回值：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

依名稱與姓名縮寫在集合中尋找作者。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要尋找的作者名稱。 |
| initials | java.lang.String | 要尋找的作者縮寫。 |

**返回值：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的作者。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

移除集合中第一個出現的指定作者。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要從集合中移除的作者。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有作者。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

返回遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 整個集合的 java.util.Iterator。
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

返回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回值：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**返回值：**
java.lang.Object