---
title: IMathBlockCollection
second_title: Aspose.Slides for Java API 参考
description: 数学块 IMathBlock 的集合
type: docs
url: /zh/com.aspose.slides/imathblockcollection/
---
**所有实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

数学块集合 (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | 将 IMathBlock 添加到集合的末尾。 |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | 将 IMathBlock 在指定索引处插入到集合中。 |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | 从集合中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的项。 |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | 确定集合是否包含特定值。 |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | 确定集合中特定 IMathBlock 的索引。 |
| [getCount()](#getCount--) | 获取集合实际包含的元素数量。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的项。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 获取指定索引处的项。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

将 IMathBlock 添加到集合的末尾。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 将被添加到集合末尾的数学块 |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

将 IMathBlock 在指定索引处插入到集合中。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应插入项的基于零的索引。 |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要插入的 IMathBlock。 |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

从集合中移除特定对象的第一次出现。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要从集合中移除的对象。 |

**返回值:**
boolean - 如果成功从集合中移除项则为 true；否则为 false。如果在原始集合中未找到该项，此方法也返回 false。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的项。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的项的基于零的索引。 |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

确定集合是否包含特定值。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的对象。 |

**返回值:**
boolean - 如果在集合中找到项则为 true；否则为 false。

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

确定集合中特定 IMathBlock 的索引。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的项。 |

**返回值:**
int - 如果在集合中找到该项，则返回其索引；否则返回 -1。

### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合实际包含的元素数量。只读 int。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**返回值:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

获取指定索引处的项。只读 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的项的基于零的索引。 |

**返回值:**
[IMathBlock](../../com.aspose.slides/imathblock) - 数学文本块。

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

获取指定索引处的项。只读 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要设置的项的基于零的索引。 |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 数学文本块。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有元素。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```