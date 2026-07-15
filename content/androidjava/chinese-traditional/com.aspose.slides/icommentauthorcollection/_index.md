---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示評論作者的集合。
type: docs
url: /zh-hant/com.aspose.slides/icommentauthorcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

表示評論作者的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 在集合末端加入新作者。 |
| [toArray()](#toArray--) | 建立並返回包含所有作者的陣列。 |
| [findByName(String name)](#findByName-java.lang.String-) | 依名稱在集合中尋找作者。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 依名稱與縮寫在集合中尋找作者。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的作者。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 移除集合中指定作者的第一個出現項目。 |
| [clear()](#clear--) | 移除集合中所有作者。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
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
public abstract ICommentAuthor addAuthor(String name, String initials)
```

在集合末端加入新作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 新作者的名稱。 |
| initials | java.lang.String | 新作者的縮寫。 |

**傳回值:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新的 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 物件。
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

建立並返回包含所有作者的陣列。

**傳回值:**
com.aspose.slides.ICommentAuthor[] - 包含 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 的陣列
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
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
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
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
public abstract void removeAt(int index)
```

移除集合中指定索引處的作者。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的元素之零基索引。 |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

移除集合中指定作者的第一個出現項目。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要從集合中移除的作者。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中所有作者。