---
title: IMathBlockCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 數學區塊 IMathBlock 的集合
type: docs
url: /zh-hant/com.aspose.slides/imathblockcollection/
---
**已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

數學區塊集合 (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## 方法

| 方法 | 描述 |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Adds IMathBlock to the end of collection. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Inserts IMathBlock into the collection at the specified index. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes an item at the specified index of the collection. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Determines whether the collection contains a specific value. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Determines the index of a specific IMathBlock in collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the item at the specified index. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Gets the item at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


將 IMathBlock 加到集合的末端。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A mathematical block that will be added to the end of the collection |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


在指定索引處將 IMathBlock 插入集合。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | The zero-based index at which an item should be inserted. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The IMathBlock to insert. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


從集合中移除指定物件的第一次出現。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The object to remove from the collection. |

**傳回值：**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


在指定索引處移除集合中的項目。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


判斷集合是否包含特定值。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```


**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The object to locate in the collection. |

**傳回值：**
boolean - true if item is found in the collection; otherwise, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


判斷特定 IMathBlock 在集合中的索引。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The item to locate in the collection. |

**傳回值：**
int - The index of item if found in the collection; otherwise, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合實際包含的元素數量。唯讀 int。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**傳回值：**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


取得指定索引處的項目。唯讀 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | The zero-based index of the item to get. |

**傳回值：**
[IMathBlock](../../com.aspose.slides/imathblock) - The block of a mathematical text.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


取得指定索引處的項目。唯讀 [IMathBlock](../../com.aspose.slides/imathblock)。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | The zero-based index of the item to set. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | The block of a mathematical text. |

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