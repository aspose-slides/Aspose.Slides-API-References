---
title: IColorOperationCollection
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine Sammlung von Farbtransformationsoperationen dar.
type: docs
url: /de/com.aspose.slides/icoloroperationcollection/
---
**Alle implementierten Schnittstellen:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Stellt eine Sammlung von Farbtransformationsoperationen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Operation am angegebenen Index zurück oder setzt sie. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Gibt die Operation am angegebenen Index zurück oder setzt sie. |
| [add(int operation, float parameter)](#add-int-float-) | Fügt der Sammlung eine neue Operation am Ende hinzu. |
| [add(int operation)](#add-int-) | Fügt der Sammlung eine neue Operation am Ende hinzu. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Fügt die neue Operation in eine Sammlung ein. |
| [insert(int position, int operation)](#insert-int-int-) | Fügt die neue Operation in eine Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Farboperation aus einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Farboperationen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

Gibt die Operation am angegebenen Index zurück oder setzt sie. Lesen/Schreiben [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

Gibt die Operation am angegebenen Index zurück oder setzt sie. Lesen/Schreiben [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

Fügt der Sammlung eine neue Operation am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operation | int | Operationstyp. |
| parameter | float | Parameter der Operation. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – Hinzugefügte Operation.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

Fügt der Sammlung eine neue Operation am Ende hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operation | int | Operationstyp. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – Hinzugefügte Operation.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

Fügt die neue Operation in eine Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Der Index, an dem die Operation eingefügt wird. |
| operation | int | Operationstyp. |
| parameter | float | Parameter der Operation. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – Eingefügte Operation.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

Fügt die neue Operation in eine Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Der Index, an dem die Operation eingefügt wird. |
| operation | int | Operationstyp. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) – Eingefügte Operation.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt die Farboperation aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index einer zu entfernenden Farboperation. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Farboperationen.