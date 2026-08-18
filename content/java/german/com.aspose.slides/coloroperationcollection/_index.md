---
title: ColorOperationCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung von Farbtransformationsoperationen dar.
type: docs
url: /de/com.aspose.slides/coloroperationcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Stellt eine Sammlung von Farbtransformationsoperationen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Vorgänge in einer Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt die Operation am angegebenen Index zurück oder legt sie fest. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Gibt die Operation am angegebenen Index zurück oder legt sie fest. |
| [add(int operation, float parameter)](#add-int-float-) | Fügt einen neuen Vorgang am Ende der Sammlung hinzu. |
| [add(int operation)](#add-int-) | Fügt einen neuen Vorgang am Ende der Sammlung hinzu. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Fügt den neuen Vorgang in eine Sammlung ein. |
| [insert(int position, int operation)](#insert-int-int-) | Fügt den neuen Vorgang in eine Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Farboperation aus einer Sammlung. |
| [clear()](#clear--) | Entfernt alle Farboperationen. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |
| [deepClone()](#deepClone--) | Erstellt eine Kopie einer ColorOperationCollection-Sammlung. |
| [cloneT()](#cloneT--) | Klont das aktuelle Objekt |

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der Vorgänge in einer Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Gibt die Operation am angegebenen Index zurück oder legt sie fest. Lese-/Schreib [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Gibt die Operation am angegebenen Index zurück oder legt sie fest. Lese-/Schreib [ColorOperation](../../com.aspose.slides/coloroperation).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Fügt einen neuen Vorgang am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operation | int | Operationstyp. |
| parameter | float | Parameter der Operation. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hinzugefügte Operation.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Fügt einen neuen Vorgang am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| operation | int | Operationstyp. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Hinzugefügte Operation.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Fügt den neuen Vorgang in eine Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Der Index, an dem die Operation eingefügt wird. |
| operation | int | Operationstyp. |
| parameter | float | Parameter der Operation. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eingefügte Operation.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Fügt den neuen Vorgang in eine Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | int | Der Index, an dem die Operation eingefügt wird. |
| operation | int | Operationstyp. |

**Rückgabe:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Eingefügte Operation.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die Farboperation aus einer Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu entfernenden Farboperation. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Farboperationen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Ein java.util.Iterator für die gesamte Sammlung.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray. |
| index | int | Startindex im Zielarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lese boolean.

**Rückgabe:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur-Lese Object.

**Rückgabe:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Erstellt eine Kopie einer ColorOperationCollection-Sammlung.

**Rückgabe:**
java.lang.Object - Neue [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) Sammlung.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Klonen des aktuellen Objekts

**Rückgabe:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klon