---
title: IColorOperationCollection
second_title: Aspose.Slides Androidhoz Java API Referencia
description: Színbeli transzformációs műveletek gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icoloroperationcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Színbeli transzformációs műveletek gyűjteményét képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Visszaadja vagy beállítja a műveletet a megadott indexnél. Olvasás/írás [IColorOperation](../../com.aspose.slides/icoloroperation).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Visszaadja vagy beállítja a műveletet a megadott indexnél. Olvasás/írás [IColorOperation](../../com.aspose.slides/icoloroperation).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Új műveletet ad a gyűjtemény végéhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Művelet típusa. |
| parameter | float | A művelet paramétere. |

**Visszatérési érték:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hozzáadott művelet.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Új műveletet ad a gyűjtemény végéhez.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Művelet típusa. |

**Visszatérési érték:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hozzáadott művelet.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Beszúrja az új műveletet a gyűjteménybe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Az index, ahová a művelet be lesz szúrva. |
| operation | int | Művelet típusa. |
| parameter | float | A művelet paramétere. |

**Visszatérési érték:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Beszúrt művelet.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Beszúrja az új műveletet a gyűjteménybe.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Az index, ahová a művelet be lesz szúrva. |
| operation | int | Művelet típusa. |

**Visszatérési érték:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Beszúrt művelet.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a színműveletet egy gyűjteményből.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A eltávolítandó színművelet indexe. |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes színműveletet.