---
title: IMathBlockCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Samling av matematiska block IMathBlock
type: docs
url: /sv/com.aspose.slides/imathblockcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Samling av matematiska block (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Metoder

| Metod | Beskrivning |
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

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Ett matematiskt block som kommer att läggas till i slutet av samlingen |

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


**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där ett objekt ska infogas. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock som ska infogas. |

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

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet som ska tas bort från samlingen. |

**Returnerar:**
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


**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index för objektet som ska tas bort. |

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

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet att söka efter i samlingen. |

**Returnerar:**
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

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet att söka efter i samlingen. |

**Returnerar:**
int - The index of item if found in the collection; otherwise, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements actually contained in the collection. Endast läsbar int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```


Gets the item at the specified index. Endast läsbar [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index för objektet som ska hämtas. |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blocken av en matematisk text.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Gets the item at the specified index. Endast läsbar [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index för objektet som ska sättas. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Blocken av en matematisk text. |

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