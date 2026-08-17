---
title: IColorOperationCollection
second_title: Aspose.Slides for Java API 参考
description: 表示一个颜色变换操作的集合。
type: docs
url: /zh/com.aspose.slides/icoloroperationcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

表示一个颜色变换操作的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回或设置指定索引处的操作。 |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | 返回或设置指定索引处的操作。 |
| [add(int operation, float parameter)](#add-int-float-) | 向集合末尾添加新操作。 |
| [add(int operation)](#add-int-) | 向集合末尾添加新操作。 |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | 向集合中插入新操作。 |
| [insert(int position, int operation)](#insert-int-int-) | 向集合中插入新操作。 |
| [removeAt(int index)](#removeAt-int-) | 从集合中移除颜色操作。 |
| [clear()](#clear--) | 移除所有颜色操作。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

返回或设置指定索引处的操作。读/写 [IColorOperation](../../com.aspose.slides/icoloroperation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

返回或设置指定索引处的操作。读/写 [IColorOperation](../../com.aspose.slides/icoloroperation)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

向集合末尾添加新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

**返回：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已添加的操作。
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

向集合末尾添加新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operation | int | 操作类型。 |

**返回：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已添加的操作。
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

向集合中插入新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 将插入操作的索引。 |
| operation | int | 操作类型。 |
| parameter | float | 操作的参数。 |

**返回：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

向集合中插入新操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | int | 将插入操作的索引。 |
| operation | int | 操作类型。 |

**返回：**
[IColorOperation](../../com.aspose.slides/icoloroperation) - 已插入的操作。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

从集合中移除颜色操作。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的颜色操作的索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除所有颜色操作。