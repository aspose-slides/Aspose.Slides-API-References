---
title: IBehaviorCollection
second_title: Aspose.Slides for Android a Java API hivatkozás
description: A viselkedés hatásainak gyűjteményét reprezentálja.
type: docs
url: /hu/com.aspose.slides/ibehaviorcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

A viselkedés hatásainak gyűjteményét reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy viselkedést a megadott indexen. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Visszaad egy viselkedést a megadott indexen. |
| [getCount()](#getCount--) | Visszaadja a viselkedések számát a gyűjteményben. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Új viselkedést ad hozzá a gyűjteményhez. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Meghatározza egy adott elem indexét a Listában. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Új viselkedést szúr be a gyűjteménybe a megadott indexen. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Eltávolítja a megadott viselkedést a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy viselkedést a gyűjteményből a megadott indexen. |
| [clear()](#clear--) | Eltávolítja az összes viselkedést a gyűjteményből. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
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

Visszaadja a viselkedések számát a gyűjteményben. Csak olvasható int.

**Visszatér:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Új viselkedést ad hozzá a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A hozzáadandó viselkedés. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Meghatározza egy adott elem indexét a Listában.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a Listában keresnek. |

**Visszatér:**
int - Az elem indexe, ha megtalálható a listában; egyébként -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Új viselkedést szúr be a gyűjteménybe a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index, ahol az új viselkedést be kell szúrni. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | A beszúrandó viselkedés. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Eltávolítja a megadott viselkedést a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az eltávolítandó viselkedés. |

**Visszatér:**
boolean - Igaz, ha a viselkedés sikeresen eltávolításra került, boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy viselkedést a gyűjteményből a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó viselkedés indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes viselkedést a gyűjteményből.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Az objektum, amelyet a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban keresnek. |

**Visszatér:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.