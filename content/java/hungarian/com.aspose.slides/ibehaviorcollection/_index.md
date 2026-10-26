---
title: IBehaviorCollection
second_title: Aspose.Slides Java API Referencia
description: Viselkedés hatások gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/ibehaviorcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Viselkedés effektusok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy viselkedést a megadott indexen. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Visszaad egy viselkedést a megadott indexen. |
| [getCount()](#getCount--) | Visszaadja a viselkedések számát egy gyűjteményben. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Új viselkedést ad egy gyűjteményhez. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Új viselkedést szúr be egy gyűjteménybe a megadott indexen. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Eltávolítja a megadott viselkedést egy gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy viselkedést egy gyűjteményből a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes viselkedést egy gyűjteményből. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Visszaad egy viselkedést a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |

**Visszatérési érték:**
[IBehavior](../../com.aspose.slides/ibehavior) - Animációs viselkedés.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Visszaad egy viselkedést a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A visszaadandó viselkedés indexe. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja a viselkedések számát egy gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Új viselkedést ad egy gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Viselkedés, amelyet hozzáad. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a Listában keresünk. |

**Visszatérési érték:**
int - Az elem indexe, ha megtalálható a listában; egyébként -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Új viselkedést szúr be egy gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahová az új viselkedést be kell szúrni. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Beszúrandó viselkedés. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Eltávolítja a megadott viselkedést egy gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Eltávolítandó viselkedés. |

**Visszatérési érték:**
boolean - true, ha a viselkedés sikeresen eltávolításra került boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy viselkedést egy gyűjteményből a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A eltávolítandó viselkedés indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes viselkedést egy gyűjteményből.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresünk. |

**Visszatérési érték:**
boolean - true, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként false.