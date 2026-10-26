---
title: CommentAuthorCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个评论作者的集合。
type: docs
url: /zh/com.aspose.slides/commentauthorcollection/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

表示一个评论作者的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [size()](#size--) | 获取集合实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 在集合末尾添加新作者。 |
| [toArray()](#toArray--) | 创建并返回包含所有作者的数组。 |
| [findByName(String name)](#findByName-java.lang.String-) | 通过名称在集合中查找作者。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 通过名称和首字母在集合中查找作者。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的作者。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 移除集合中指定作者的第一次出现。 |
| [clear()](#clear--) | 移除集合中的所有作者。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 将集合中的所有元素复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回一个指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
### size() {#size--}
```
public final int size()
```

获取集合实际包含的元素数量。只读 int。

**返回：**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```

获取指定索引处的元素。只读 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```

在集合末尾添加新作者。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 新作者的名称。 |
| initials | java.lang.String | 新作者的首字母。 |

**返回：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 对象。
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```

创建并返回包含所有作者的数组。

**返回：**
com.aspose.slides.ICommentAuthor[] - 由 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 组成的数组
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```

通过名称在集合中查找作者。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要查找的作者的名称。 |

**返回：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

通过名称和首字母在集合中查找作者。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要查找的作者的名称。 |
| initials | java.lang.String | 要查找的作者的首字母。 |

**返回：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引处的作者。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```

移除集合中指定作者的第一次出现。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要从集合中移除的作者。 |
### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有作者。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```

返回遍历集合的枚举器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - 用于整个集合的 java.util.Iterator。
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

将集合中的所有元素复制到指定数组。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目标数组。 |
| index | int | 目标数组的起始索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一个指示集合访问是否同步（线程安全）的值。只读 boolean。

**返回：**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回：**
java.lang.Object