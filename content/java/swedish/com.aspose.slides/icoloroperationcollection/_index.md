---
title: IColorOperationCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av färgtransformationsoperationer.
type: docs
url: /sv/com.aspose.slides/icoloroperationcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Representerar en samling av färgtransformationsoperationer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar eller anger operationen på det specificerade indexet. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returnerar eller anger operationen på det specificerade indexet. |
| [add(int operation, float parameter)](#add-int-float-) | Lägger till en ny operation i slutet av samlingen. |
| [add(int operation)](#add-int-) | Lägger till en ny operation i slutet av samlingen. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Infogar den nya operationen i en samling. |
| [insert(int position, int operation)](#insert-int-int-) | Infogar den nya operationen i en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort färgoperationen från en samling. |
| [clear()](#clear--) | Tar bort alla färgoperationer. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Returnerar eller anger operationen på det specificerade indexet. Läs/skriv [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Returnerar eller anger operationen på det specificerade indexet. Läs/skriv [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Lägger till en ny operation i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operation | int | Operationstyp. |
| parameter | float | Operationsparameter. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Tillagd operation.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Lägger till en ny operation i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operation | int | Operationstyp. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Tillagd operation.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```


Infogar den nya operationen i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Indexet där operationen ska infogas. |
| operation | int | Operationstyp. |
| parameter | float | Operationsparameter. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Infogad operation.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```


Infogar den nya operationen i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Indexet där operationen ska infogas. |
| operation | int | Operationstyp. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Infogad operation.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort färgoperationen från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en färgoperation att ta bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla färgoperationer.