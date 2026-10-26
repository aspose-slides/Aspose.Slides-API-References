---
title: ITabCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个制表符集合。
type: docs
url: /zh/com.aspose.slides/itabcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

表示一个制表符集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [add(double position, int align)](#add-double-int-) | 向集合中添加一个制表符。 |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | 向集合中添加一个制表符。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
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

**返回值：**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

向集合中添加一个制表符。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | double | 制表符位置。 |
| align | int | 制表符对齐方式。 |

**返回值：**
[ITab](../../com.aspose.slides/itab) - 已添加的制表符。
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

向集合中添加一个制表符。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | 要添加到集合末尾的制表符对象。 |

**返回值：**
int - 添加制表符的索引。
### clear() {#clear--}
```
public abstract void clear()
```

从集合中移除所有元素。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |