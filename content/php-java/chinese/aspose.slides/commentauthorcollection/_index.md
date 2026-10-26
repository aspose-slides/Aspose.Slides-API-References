---
title: CommentAuthorCollection
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/commentauthorcollection/
---
## CommentAuthorCollection 类

 表示评论作者的集合。
 
### addAuthor {#addAuthor}

| 名称 | 描述 |
| --- | --- |
| addAuthor (String, String) | 在集合末尾添加新作者。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 新作者的名称。 |
| initials | String | 新作者的首字母。 |

 **返回值：**
[CommentAuthor](../commentauthor)

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxEditException | 已经添加了相同名称和首字母的作者时抛出。 |


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有作者。 |

 **返回值：**
void


---


### findByName {#findByName}

| 名称 | 描述 |
| --- | --- |
| findByName (String) | 通过名称在集合中查找作者。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要查找的作者的名称。 |

 **返回值：**
[CommentAuthor](../commentauthor)


---


### findByNameAndInitials {#findByNameAndInitials}

| 名称 | 描述 |
| --- | --- |
| findByNameAndInitials (String, String) | 通过名称和首字母在集合中查找作者。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| name | String | 要查找的作者的名称。 |
| initials | String | 要查找的作者的首字母。 |

 **返回值：**
[CommentAuthor](../commentauthor)


---


### getSyncRoot {#getSyncRoot}

| 名称 | 描述 |
| --- | --- |
| getSyncRoot () | 返回同步根。只读 Object。 |

 **返回值：**
Object


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 获取指定索引处的元素。只读 ICommentAuthor。 |

 **返回值：**
[CommentAuthor](../commentauthor)


---


### isSynchronized {#isSynchronized}

| 名称 | 描述 |
| --- | --- |
| isSynchronized () | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 boolean。 |

 **返回值：**
boolean


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回遍历集合的枚举器。 |

 **返回值：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

 **返回值：**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([CommentAuthor](../commentauthor)) | 移除集合中指定作者的首次出现。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| author | [CommentAuthor](../commentauthor) | 要从集合中移除的作者。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxEditException | 作者已被移除时抛出。 |


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除集合中指定索引处的作者。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

 **返回值：**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | PptxEditException | 作者已被移除时抛出。 |


---


### size {#size}

| 名称 | 描述 |
| --- | --- |
| size () | 获取集合中实际包含的元素数量。只读 int。 |

 **返回值：**
int


---


### toArray {#toArray}

| 名称 | 描述 |
| --- | --- |
| toArray () | 创建并返回包含所有作者的数组。 |

 **返回值：**
[CommentAuthor](../commentauthor)