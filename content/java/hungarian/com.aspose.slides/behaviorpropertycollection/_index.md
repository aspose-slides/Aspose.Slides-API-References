---
title: BehaviorPropertyCollection
second_title: Aspose.Slides Java API hivatkozás
description: Az effektus viselkedésének időzítési tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Az effektus viselkedésének időzítési tulajdonságait képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [size()](#size--) | Visszaadja a gyűjteményben tárolt tulajdonságok számát. |
| [isReadOnly()](#isReadOnly--) | Megkap egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Új tulajdonságot ad hozzá a gyűjteményhez. |
| [add(String propertyValue)](#add-java.lang.String-) | Új tulajdonságot ad hozzá a gyűjteményhez. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Meghatározza egy adott elem indexét a Listában. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Meghatározza egy adott elem indexét a Listában a tulajdonság értéke alapján. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Beszúr egy új tulajdonságot a gyűjteménybe a megadott indexnél. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Beszúr egy új tulajdonságot (a megadott tulajdonságértékkel) a gyűjteménybe a megadott indexnél. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a tulajdonságot a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes tulajdonságot a gyűjteményből. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy tulajdonságot a megadott indexnél. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Beállít egy tulajdonságot a megadott indexnél. |
| [iterator()](#iterator--) | Visszaad egy felsorolót, amely végigiterál a gyűjteményen. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java iterátort az egész gyűjteményhez. |
### size() {#size--}
```
public final int size()
```

Visszaadja a gyűjteményben tárolt tulajdonságok számát. Csak olvasható int.

**Visszatérési érték:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Értéket ad, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Új tulajdonságot ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A hozzáadandó tulajdonság. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Új tulajdonságot ad hozzá a gyűjteményhez.

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
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A Listában keresett objektum. |

**Visszatérési érték:**
int - az elem indexe, ha megtalálható a listában; egyébként -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Meghatározza egy adott elem indexét a Listában a tulajdonság értéke alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |
**Visszatérési érték:**
int - a megadott értékű tulajdonság indexe
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Beszúr egy új tulajdonságot a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új tulajdonságot be kell szúrni. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A hozzáadandó tulajdonság. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Beszúr egy új tulajdonságot (a megadott tulajdonságértékkel) a gyűjteménybe a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új tulajdonságot be kell szúrni. |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Az egy-dimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeinek másolási célpontja. A tömbnek nullártatú indexeléssel kell rendelkeznie. |
| arrayIndex | int | A nullárral kezdődő index a tömbben, ahol a másolás kezdődik. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Eltávolítja a megadott tulajdonságot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Az eltávolítandó tulajdonság. |

**Visszatérési érték:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Eltávolítja a megadott tulajdonságot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A törlendő tulajdonság értéke. |

**Visszatérési érték:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a tulajdonságot a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő tulajdonság indexe. |

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
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | A [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresett tulajdonság. |

**Visszatérési érték:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresett tulajdonság értéke. |

**Visszatérési érték:**
boolean - igaz, ha a propertyValue megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Visszaad egy tulajdonságot a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó tulajdonság indexe. |

**Visszatérési érték:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animációs viselkedés tulajdonság.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Beállít egy tulajdonságot a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó tulajdonság indexe. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Visszaad egy felsorolót, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator amelyet a gyűjtemény bejárására lehet használni.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Visszatérési érték:**
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

**Visszatérési érték:**
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

**Visszatérési érték:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Visszaad egy java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Egy java.util.Iterator az egész gyűjteményhez.