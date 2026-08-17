---
title: IMathElementCollection
second_title: Aspose.Slides Java API 参考
description: 表示一个数学元素 MathElement 的集合。
type: docs
url: /zh/com.aspose.slides/imathelementcollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

表示一个数学元素集合 (MathElement)。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的元素。 |
| [getCount()](#getCount--) | 获取集合实际包含的元素数量。 |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | 在集合末尾添加一个数学元素。 |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | 确定集合中特定数学元素的索引。 |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | 在指定索引处向集合插入一个数学元素。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | 确定集合是否包含特定值。 |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | 从集合中移除特定对象的第一次出现。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引处的元素。 |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

获取指定索引处的元素。只读 [IMathElement](../../com.aspose.slides/imathelement)。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要获取的项的零基索引 |

**返回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

获取集合实际包含的元素数量。只读 int。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**返回值:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

在集合末尾添加一个数学元素。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要添加到集合末尾的 IMathElement。 |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

确定集合中特定数学元素的索引。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的元素。 |

**返回值:**
int - 如果在集合中找到项，则返回其索引；否则返回 -1。
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

在指定索引处向集合插入一个数学元素。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应插入 IMathElement 的零基索引。 |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要插入的 IMathElement。 |

### clear() {#clear--}
```
public abstract void clear()
```

移除集合中的所有元素。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

确定集合是否包含特定值。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要在集合中定位的对象。 |

**返回值:**
boolean - 如果在集合中找到项则为 true；否则为 false。
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

从集合中移除特定对象的第一次出现。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | 要从集合中移除的对象。 |

**返回值:**
boolean - 如果成功从集合中移除项则为 true；否则为 false。如果在原始集合中未找到项，该方法也返回 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引处的元素。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的元素的零基索引。 |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

复制到指定数组。

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | 要复制到的数组。 |
| arrayIndex | int | 开始复制的索引。 |