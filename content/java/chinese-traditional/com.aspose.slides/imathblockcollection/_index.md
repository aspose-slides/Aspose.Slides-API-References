---
title: IMathBlockCollection
second_title: Aspose.Slides for Java API 參考手冊
description: 數學區塊 IMathBlock 的集合
type: docs
url: /zh-hant/com.aspose.slides/imathblockcollection/
---
**全部已實作的介面:**
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

| 方法 | 說明 |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | 將 IMathBlock 新增至集合的末端。 |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | 在指定的索引處將 IMathBlock 插入集合。 |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | 從集合中移除第一個出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的項目。 |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | 判斷集合是否包含特定值。 |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | 確定特定 IMathBlock 在集合中的索引。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的項目。 |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | 取得指定索引處的項目。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


將 IMathBlock 加入集合的末端。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 將被新增至集合末端的數學區塊 |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


在指定的索引處將 IMathBlock 插入集合。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入項目的零基索引。 |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要插入的 IMathBlock。 |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


從集合中移除第一個出現的特定物件。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要從集合中移除的物件。 |

**返回:**
boolean - 若成功從集合中移除項目則返回 true；否則返回 false。如果在原始集合中未找到項目，亦返回 false。

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除集合中指定索引處的項目。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的項目的零基索引。 |

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
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的物件。 |

**返回:**
boolean - 若在集合中找到項目則返回 true；否則返回 false。

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


確定特定 IMathBlock 在集合中的索引。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | 要在集合中定位的項目。 |

**返回:**
int - 若在集合中找到項目，返回其索引；否則返回 -1。

### getCount() {#getCount--}
```
public abstract int getCount()
```


取得集合中實際包含的元素數量。唯讀 int。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```
**返回:**
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
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要取得的項目的零基索引。 |

**返回:**
[IMathBlock](../../com.aspose.slides/imathblock) - 數學文字區塊。

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
**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要設定的項目的零基索引。 |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | 數學文字區塊。 |

### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```