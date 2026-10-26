---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides Androidra a Java API hivatkozással
description: Az effektus viselkedésének időzítési tulajdonságait ábrázolja.
type: docs
url: /hu/com.aspose.slides/ibehaviorpropertycollection/
---
**Az összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Az effektus viselkedésének időzítési tulajdonságait ábrázolja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Új tulajdonságot ad a gyűjteményhez. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Meghatározza egy adott elem indexét a lista tulajdonságértéke alapján. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Új tulajdonságot szúr be (a megadott tulajdonságértékkel) a gyűjteménybe a megadott indexen. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Új tulajdonságot ad a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Meghatározza egy adott elem indexét a lista tulajdonságértéke alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |

**Visszatérési érték:**
int - A megadott értékű tulajdonság indexe
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Új tulajdonságot szúr be (a megadott tulajdonságértékkel) a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új tulajdonságot be kell szúrni. |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Eltávolítja a megadott tulajdonságot a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | Az eltávolítandó tulajdonság értéke. |

**Visszatérési érték:**
boolean - True ha a tulajdonság sikeresen eltávolításra került boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A megtalálni kívánt tulajdonság értéke a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Visszatérési érték:**
boolean - true ha a propertyValue megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként false.