---
title: IMathElementCollection
second_title: Aspose.Slides for Java API referencia
description: Matematikai elemek (MathElement) gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imathelementcollection/
---
**Az összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Matematikai elemek (MathElement) gyűjteményét képviseli.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | A megadott indexű elemet adja vissza. |
| [getCount()](#getCount--) | A gyűjteményben ténylegesen tárolt elemek számát adja vissza. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Egy matematikai elemet ad a gyűjtemény végéhez. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Megállapítja egy adott matematikai elem indexét a gyűjteményben. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Beilleszt egy matematikai elemet a gyűjteménybe a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja a gyűjtemény összes elemét. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Megállapítja, hogy a gyűjtemény tartalmaz-e egy adott értéket. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Eltávolítja a gyűjteményből a megadott objektum első előfordulását. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Átmásolja a megadott tömbbe. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

A megadott indexű elemet adja vissza. Csak-olvasás [IMathElement](../../com.aspose.slides/imathelement).

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

A gyűjteményben ténylegesen tárolt elemek számát adja vissza. Csak-olvasás int.

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

Egy matematikai elemet ad a gyűjtemény végéhez.

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

Megállapítja egy adott matematikai elem indexét a gyűjteményben.

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
int - Az elem indexe, ha megtalálható a gyűjteményben; egyébként -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Beilleszt egy matematikai elemet a gyűjteménybe a megadott indexnél.

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
| index | int | A nulla alapú index, ahol az IMathElement be kell szúrni. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | A beszúrandó IMathElement. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja a gyűjtemény összes elemét.

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
boolean - igaz, ha az elem megtalálható a gyűjteményben; különben hamis.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Eltávolítja a gyűjteményből a megadott objektum első előfordulását.

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
boolean - igaz, ha az elem sikeresen eltávolításra került a gyűjteményből; különben hamis. Ez a metódus hamisat is visszaad, ha az elem nem található az eredeti gyűjteményben.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjtemény megadott indexű elemét.

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

Átmásolja a megadott tömbbe.

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