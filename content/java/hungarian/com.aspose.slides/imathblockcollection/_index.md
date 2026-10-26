---
title: IMathBlockCollection
second_title: Aspose.Slides Java API referenciája
description: Matematikai blokkok (IMathBlock) gyűjteménye
type: docs
url: /hu/com.aspose.slides/imathblockcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Matematikai blokk gyűjteménye (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Hozzáad egy IMathBlock-ot a gyűjtemény végéhez. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Beszúr egy IMathBlock-ot a megadott indexen a gyűjteménybe. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Eltávolítja egy adott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy elemet a megadott indexen a gyűjteményből. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Megállapítja egy adott IMathBlock indexét a gyűjteményben. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen lévő elemek számát. |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexen. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Lekéri az elemet a megadott indexen. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```


Hozzáad egy IMathBlock-ot a gyűjtemény végéhez.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Egy matematikai blokk, amely a gyűjtemény végéhez lesz hozzáadva |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```


Beszúr egy IMathBlock-ot a megadott indexen a gyűjteménybe.

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
| index | int | A nullától kezdődő index, ahol az elemet be kell szúrni. |
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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A gyűjteményből eltávolítandó objektum. |

**Visszatérési érték:**
boolean - igaz, ha az elem sikeresen eltávolításra került a gyűjteményből; egyébként hamis. Ez a metódus szintén hamisat ad vissza, ha az elem nem található az eredeti gyűjteményben.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolít egy elemet a megadott indexen a gyűjteményből.

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
| index | int | A nullától kezdődő index, amelynek elemet el kell távolítani. |

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A gyűjteményben keresendő objektum. |

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | A gyűjteményben keresendő elem. |

**Visszatérési érték:**
int - Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```


Lekéri a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

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


Lekéri az elemet a megadott indexen. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | A nullától kezdődő index, amelynek elemét le kell kérni. |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - A matematikai szöveg blokkja.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```


Lekéri az elemet a megadott indexen. Csak olvasható [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | A nullától kezdődő index, amelynek elemét be kell állítani. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | A matematikai szöveg blokkját.

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