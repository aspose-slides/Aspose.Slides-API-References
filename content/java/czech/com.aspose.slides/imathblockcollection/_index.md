---
title: IMathBlockCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Kolekce matematických bloků IMathBlock
type: docs
url: /cs/com.aspose.slides/imathblockcollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Kolekce matematických bloků (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Přidá IMathBlock na konec kolekce. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Vloží IMathBlock do kolekce na určeném indexu. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Odstraní první výskyt konkrétního objektu z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní položku na určeném indexu v kolekci. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Určuje, zda kolekce obsahuje konkrétní hodnotu. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Určuje index konkrétního IMathBlock v kolekci. |
| [getCount()](#getCount--) | Získá počet skutečně obsažených prvků v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Získá položku na určeném indexu. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Získá položku na určeném indexu. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
### add(IMMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Přidá IMathBlock na konec kolekce.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Matematický blok, který bude přidán na konec kolekce |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Vloží IMathBlock do kolekce na určeném indexu.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index, na kterém má být položka vložena. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock, který se má vložit. |

### remove(IMMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Odstraní první výskyt konkrétního objektu z kolekce.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objekt, který se má odstranit z kolekce. |

**Návratová hodnota:**
boolean - true pokud byl položka úspěšně odstraněna z kolekce; jinak false. Tato metoda také vrací false, pokud položka není v původní kolekci nalezena.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní položku na určeném indexu v kolekci.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky, která má být odstraněna. |

### contains(IMMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Určuje, zda kolekce obsahuje konkrétní hodnotu.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Objekt, který se má v kolekci vyhledat. |

**Návratová hodnota:**
boolean - true pokud je položka v kolekci nalezena; jinak false.

### indexOf(IMMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Určuje index konkrétního IMathBlock v kolekci.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Položka, která se má v kolekci vyhledat. |

**Návratová hodnota:**
int - Index položky, pokud je v kolekci nalezena; jinak -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet skutečně obsažených prvků v kolekci. Pouze pro čtení int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Návratová hodnota:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Získá položku na určeném indexu. Pouze pro čtení [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky, která má být získána. |

**Návratová hodnota:**
[IMathBlock](../../com.aspose.slides/imathblock) - Blok matematického textu.

### set_Item(int index, IMMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Získá položku na určeném indexu. Pouze pro čtení [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index položky, která má být nastavena. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Blok matematického textu. |

### clear() {#clear--}
```
public abstract void clear()
```

Odstraní všechny prvky z kolekce.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```