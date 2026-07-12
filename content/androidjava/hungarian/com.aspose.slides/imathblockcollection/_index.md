---
title: IMathBlockCollection
second_title: Aspose.Slides Androidra a Java API referencia
description: Matematikai blokkok gyűjteménye (IMathBlock)
type: docs
url: /hu/com.aspose.slides/imathblockcollection/
---
**Összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Matematikai blokkok gyűjteménye (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Hozzáad egy IMathBlock elemet a gyűjtemény végéhez. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Beszúr egy IMathBlock elemet a gyűjteménybe a megadott indexnél. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy elemet a gyűjtemény megadott indexén. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Meghatározza, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Meghatározza egy adott IMathBlock indexét a gyűjteményben. |
| [getCount()](#getCount--) | Visszaadja a gyűjteményben ténylegesen található elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a megadott indexű elemet. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Visszaadja a megadott indexű elemet. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Hozzáadja az IMathBlock elemet a gyűjtemény végéhez.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A matematikai blokk, amely a gyűjtemény végéhez lesz hozzáadva |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Beszúrja az IMathBlock elemet a gyűjteménybe a megadott indexnél.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, amelynél egy elemet kell beszúrni. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A beszúrandó IMathBlock. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Eltávolítja egy adott objektum első előfordulását a gyűjteményből.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Az objektum, amelyet el kell távolítani a gyűjteményből. |

**Visszatérési érték:**
boolean - igaz, ha az elemet sikeresen eltávolították a gyűjteményből; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha az elem nem található az eredeti gyűjteményben.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy elemet a gyűjtemény megadott indexén.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, amely a törlendő elemet jelöli. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Az objektum, amelyet a gyűjteményben keresni kell. |

**Visszatérési érték:**
boolean - igaz, ha az elem megtalálható a gyűjteményben; egyébként hamis.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Megállapítja egy adott IMathBlock indexét a gyűjteményben.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Az elem, amelyet a gyűjteményben keresni kell. |

**Visszatérési érték:**
int - Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a gyűjteményben ténylegesen található elemek számát. Csak olvasható int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Visszatérési érték:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Visszaadja a megadott indexű elemet. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, amely a lekérdezendő elemet jelöli. |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - A matematikai szöveg blokkja.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Visszaadja a megadott indexű elemet. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulláralapú index, amely a beállítandó elemet jelöli. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | A matematikai szöveg blokkja. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```