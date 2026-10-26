---
title: IMathBlockCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Collectie van wiskundige blokken IMathBlock
type: docs
url: /nl/com.aspose.slides/imathblockcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Collectie van wiskundige blokken (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Voegt IMathBlock toe aan het einde van de collectie. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Voegt IMathBlock in de collectie in op de opgegeven index. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Verwijdert de eerste instantie van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een item op de opgegeven index van de collectie. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Bepaalt of de collectie een specifieke waarde bevat. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Bepaalt de index van een specifiek IMathBlock in de collectie. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
| [get_Item(int index)](#get-Item-int-) | Haalt het item op op de opgegeven index. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Haalt het item op op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Voegt IMathBlock toe aan het einde van de collectie.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Een wiskundig blok dat aan het einde van de collectie wordt toegevoegd. |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Voegt IMathBlock in de collectie in op de opgegeven index.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop een item moet worden ingevoegd. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Het in te voegen IMathBlock. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Verwijdert de eerste instantie van een specifiek object uit de collectie.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Het object dat uit de collectie moet worden verwijderd. |

**Retour:**
boolean - true if item was successfully removed from the collection; otherwise, false. This method also returns false if item is not found in the original collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert een item op de opgegeven index van de collectie.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen item. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Bepaalt of de collectie een specifieke waarde bevat.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Het object dat gezocht wordt in de collectie. |

**Retour:**
boolean - true if item is found in the collection; otherwise, false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Bepaalt de index van een specifiek IMathBlock in de collectie.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Het item dat gezocht wordt in de collectie. |

**Retour:**
int - De index van item als het gevonden is in de collectie; anders -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Haalt het item op op de opgegeven index. Alleen-lezen [IMathBlock](../../com.aspose.slides/imathblock).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het item dat opgehaald moet worden. |

**Retour:**
[IMathBlock](../../com.aspose.slides/imathblock) - Het blok van een wiskundige tekst.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Haalt het item op op de opgegeven index. Alleen-lezen [IMathBlock](../../com.aspose.slides/imathblock).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het item dat ingesteld moet worden. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Het blok van een wiskundige tekst. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```