---
title: ITabCollection
second_title: Aspose.Slides Java API 参考
description: 表示 Tab 的集合。
type: docs
url: /zh/com.aspose.slides/itabcollection/
---
**全部已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

表示 Tab 的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(double position, int align)](#add-double-int-) | 向集合中添加一个 Tab。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 向集合中添加一个 Tab。 |
| [clear()](#clear--) | 移除集合中所有元素。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


获取指定索引处的元素。只读 [ITab](../../com.aspose.slides/itab)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


向集合中添加一个 Tab。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | double | Tab 位置。 |
| align | int | Tab 对齐方式。 |

**返回：**
[ITab](../../com.aspose.slides/itab) - 已添加的 Tab。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


向集合中添加一个 Tab。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 要添加到集合末尾的 Tab 对象。 |

**返回：**
int - 添加 Tab 的索引。
### clear() {#clear--}
```
public abstract void clear()
```


移除集合中所有元素。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |