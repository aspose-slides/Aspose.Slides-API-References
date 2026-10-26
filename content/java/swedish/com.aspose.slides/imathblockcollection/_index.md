---
title: IMathBlockCollection
second_title: Aspose.Slides för Java API-referens
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

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Lägger till IMathBlock i slutet av samlingen. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Infogar IMathBlock i samlingen på angivet index. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett objekt vid angivet index i samlingen. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Bestämmer indexet för ett specifikt IMathBlock i samlingen. |
| [getCount()](#getCount--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar objektet vid angivet index. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Hämtar objektet vid angivet index. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Lägger till IMathBlock i slutet av samlingen.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Ett matematiskt block som kommer att läggas till i slutet av samlingen |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Infogar IMathBlock i samlingen på angivet index.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där ett objekt ska infogas. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock att infoga. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet som ska tas bort från samlingen. |

**Returnerar:**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort ett objekt vid angivet index i samlingen.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för objektet som ska tas bort. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Bestämmer om samlingen innehåller ett specifikt värde.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet att söka i samlingen. |

**Returnerar:**
boolean - true if item is found in the collection; otherwise, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Bestämmer indexet för ett specifikt IMathBlock i samlingen.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objektet att hitta i samlingen. |

**Returnerar:**
int - The index of item if found in the collection; otherwise, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

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

Hämtar objektet vid angivet index. Skrivskyddad [IMathBlock](../../com.aspose.slides/imathblock).

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för objektet som ska hämtas. |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - Block av en matematisk text.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Hämtar objektet vid angivet index. Skrivskyddad [IMathBlock](../../com.aspose.slides/imathblock).

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för objektet som ska sättas. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Block av en matematisk text. |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```