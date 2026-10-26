---
title: IMathElementCollection
second_title: Aspose.Slides Androidra vonatkozó Java API-referencia
description: A matematikai elemek (MathElement) gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imathelementcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Matematikai elemek (MathElement) gyűjteményét ábrázolja.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri a megadott indexen lévő elemet. |
| [getCount()](#getCount--) | Lekéri a gyűjteményben ténylegesen lévő elemek számát. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Math elemet ad a gyűjtemény végéhez. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Megállapítja egy adott math elem indexét a gyűjteményben. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Math elemet szúr be a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet a gyűjteményből. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Eltávolítja a megadott objektum első előfordulását a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a megadott indexen lévő elemet a gyűjteményből. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Copy to specified array. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Lekéri a megadott indexen lévő elemet. Csak olvasható [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A lekérendő elem nulla alapú indexe |

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lekéri a gyűjteményben ténylegesen lévő elemek számát. Csak olvasható int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Visszatérési érték:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Math elemet ad a gyűjtemény végéhez.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A gyűjtemény végéhez hozzáadandó IMathElement. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Megállapítja egy adott math elem indexét a gyűjteményben.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A gyűjteményben keresendő elem. |

**Visszatérési érték:**
int – Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Math elemet szúr be a gyűjteménybe a megadott indexnél.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az a nulla alapú index, ahová az IMathElement be lesz szúrva. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A beszúrandó IMathElement. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet a gyűjteményből.

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

Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A gyűjteményben keresendő objektum. |

**Visszatérési érték:**
boolean – igaz, ha az elem megtalálható a gyűjteményben; egyébként hamis.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Eltávolítja a megadott objektum első előfordulását a gyűjteményből.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A gyűjteményből eltávolítandó objektum. |

**Visszatérési érték:**
boolean – igaz, ha az elem sikeresen eltávolításra került a gyűjteményből; egyébként hamis. A metódus hamisat is visszaad, ha az elem nem található az eredeti gyűjteményben.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexen lévő elemet.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó elem nulla alapú indexe. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Másolás a megadott tömbbe.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | A cél tömb. |
| arrayIndex | int | A másolás kezdő indexe. |