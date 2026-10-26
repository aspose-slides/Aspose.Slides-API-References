---
title: ICommentAuthorCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示评论作者的集合。
type: docs
url: /zh/com.aspose.slides/icommentauthorcollection/
---
**所有实现的接口**：
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

表示评论作者的集合。

## 方法

| 方法 | 说明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | 在集合末尾添加新作者。 |
| [toArray()](#toArray--) | 创建并返回包含所有作者的数组。 |
| [findByName(String name)](#findByName-java.lang.String-) | 通过名称在集合中查找作者。 |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | 通过名称和首字母在集合中查找作者。 |
| [removeAt(int index)](#removeAt-int-) | 删除集合中指定索引处的作者。 |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | 删除集合中指定作者的第一次出现。 |
| [clear()](#clear--) | 删除集合中的所有作者。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

获取指定索引处的元素。只读 [ICommentAuthor](../../com.aspose.slides/icommentauthor)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

在集合末尾添加新作者。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| name | java.lang.String | 新作者的名称。 |
| initials | java.lang.String | 新作者的首字母。 |

**返回值：**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - 新的 [ICommentAuthor](../../com.aspose.slides/icommentauthor) 对象。
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

创建并返回包含所有作者的数组。

**返回值：**
com.aspose.slides.ICommentAuthor[] - [ICommentAuthor](../../com.aspose.slides/icommentauthor) 的数组
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

通过名称在集合中查找作者。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| name | java.lang.String | 要查找的作者的名称。 |

**返回值：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

通过名称和首字母在集合中查找作者。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| name | java.lang.String | 要查找的作者的名称。 |
| initials | java.lang.String | 要查找的作者的首字母。 |

**返回值：**
com.aspose.slides.ICommentAuthor[] - 作者或 null。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除集合中指定索引处的作者。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| index | int | 要删除的元素的零基索引。 |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

删除集合中指定作者的第一次出现。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 要从集合中删除的作者。 |
### clear() {#clear--}
```
public abstract void clear()
```

删除集合中的所有作者。