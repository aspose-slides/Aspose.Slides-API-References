---
title: IMathBlockCollection
second_title: Aspose.Slides for Java API Reference
description: Collection of math blocks IMathBlock
type: docs
weight: 885
url: /java/com.aspose.slides/imathblockcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Collection of math blocks (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Methods

| Method | Description |
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


Adds IMathBlock to the end of collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A mathematical block that will be added to the end of the collection |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


Inserts IMathBlock into the collection at the specified index.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which an item should be inserted. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The IMathBlock to insert. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```


Removes the first occurrence of a specific object from the collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The object to remove from the collection. |

**Returns:**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes an item at the specified index of the collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to remove. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```


Determines whether the collection contains a specific value.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The object to locate in the collection. |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```


Determines the index of a specific IMathBlock in collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | The item to locate in the collection. |

**Returns:**
int - The index of item if found in the collection; otherwise, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Read-only int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Gets the item at the specified index. Read-only [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to get. |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - The block of a mathematical text.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Gets the item at the specified index. Read-only [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the item to set. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | The block of a mathematical text. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```

