---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides Java API referencia
description: Az effektus viselkedésének időzítési tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ibehaviorpropertycollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Az effektus viselkedéséhez tartozó időzítési tulajdonságokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Új tulajdonságot ad hozzá a gyűjteményhez. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Meghatározza egy konkrét elem indexét a tulajdonságérték alapján a Listában. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Új tulajdonságot szúr be (a megadott tulajdonságértékkel) a gyűjteménybe a megadott indexen. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Eltávolítja a megadott tulajdonságot a gyűjteményből. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Új tulajdonságot ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A hozzáadandó tulajdonság értéke. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Meghatározza egy konkrét elem indexét a tulajdonságérték alapján a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | a tulajdonság értéke |

**Visszatérési érték:**
int - A megadott értékkel rendelkező tulajdonság indexe
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
| propertyValue | java.lang.String | A eltávolítandó tulajdonság értéke. |

**Visszatérési érték:**
boolean - true, ha a tulajdonság sikeresen eltávolítva; boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| propertyValue | java.lang.String | A tulajdonság értéke, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben keresni kell. |

**Visszatérési érték:**
boolean - true, ha a propertyValue megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként false.