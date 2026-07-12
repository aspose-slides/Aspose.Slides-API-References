---
title: BehaviorPropertyCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Ábrázolja az effektus viselkedésének időzítési tulajdonságait.
type: docs
url: /hu/com.aspose.slides/behaviorpropertycollection/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Ábrázolja az effektus viselkedésének időzítési tulajdonságait.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben tárolt tulajdonságok számát. |
| [isReadOnly()](#isReadOnly--) | Lekérdezi azt az értéket, amely azt jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Új tulajdonságot ad a gyűjteményhez. |
| [add(String propertyValue)](#add-java.lang.String-) | Új tulajdonságot ad a gyűjteményhez. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Meghatározza egy adott elem indexét a Listában. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Meghatározza egy adott elem indexét a Listában a tulajdonság értéke alapján. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Új tulajdonságot szúr be a gyűjteménybe a megadott indexnél. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Új tulajdonságot (a megadott tulajdonságértékkel) szúr be a gyűjteménybe a megadott indexnél. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy Array-be másolja, egy adott Array indexnél kezdve. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a tulajdonságot a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot a gyűjteményből. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy tulajdonságot a megadott indexen. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Beállít egy tulajdonságot a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort a teljes gyűjteményhez. |

### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben tárolt tulajdonságok számát. Csak olvasható int.

**Visszatér:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lekérdezi azt az értéket, amely azt jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatér:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Új tulajdonságot ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A hozzáadandó tulajdonság. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Új tulajdonságot ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A keresendő objektum a Listában. |

**Visszatér:**
int - A Listában található elem indexe; ha nincs, -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Meghatározza egy adott elem indexét a Listában a tulajdonság értéke alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |

**Visszatér:**
int - A megadott értékű tulajdonság indexe

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Új tulajdonságot szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új tulajdonságot be kell szúrni. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A hozzáadandó tulajdonság. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Új tulajdonságot (a megadott tulajdonságértékkel) szúr be a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új tulajdonságot be kell szúrni. |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

A [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy Array-be másolja, egy adott Array indexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Az egy-dimenziós Array, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból másolt elemek célja. Az Array-nak nulláralapú indexelése van. |
| arrayIndex | int | A nulláralapú index az array-ben, ahol a másolás kezdődik. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Eltávolítja a megadott tulajdonságot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Az eltávolítandó tulajdonság. |

**Visszatér:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Eltávolítja a megadott tulajdonságot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | Az eltávolítandó tulajdonság értéke. |

**Visszatér:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy tulajdonságot a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A tulajdonság indexe, amelyet törölni kell. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes tulajdonságot a gyűjteményből.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A keresett tulajdonság a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben; egyébként hamis.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A keresett tulajdonság értéke a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben. |

**Visszatér:**
boolean - igaz, ha a propertyValue megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben; egyébként hamis.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Visszaad egy tulajdonságot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó tulajdonság indexe. |

**Visszatér:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animációs viselkedés tulajdonság.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Beállít egy tulajdonságot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A beállítandó tulajdonság indexe. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Visszatér:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Visszatér:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Visszatér:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Visszaad egy java iterátort a teljes gyűjteményhez.

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Egy java.util.Iterator a teljes gyűjteményhez.