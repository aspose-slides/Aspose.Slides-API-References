---
title: ColorOperationCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av färgtransformationsoperationer.
type: docs
url: /sv/com.aspose.slides/coloroperationcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Representerar en samling av färgtransformationsoperationer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet operationer i en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar eller anger operationen på det angivna indexet. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returnerar eller anger operationen på det angivna indexet. |
| [add(int operation, float parameter)](#add-int-float-) | Lägger till en ny operation i slutet av samlingen. |
| [add(int operation)](#add-int-) | Lägger till en ny operation i slutet av samlingen. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Infogar den nya operationen i en samling. |
| [insert(int position, int operation)](#insert-int-int-) | Infogar den nya operationen i en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort färgoperationen från en samling. |
| [clear()](#clear--) | Tar bort alla färgoperationer. |
| [iterator()](#iterator--) | Returnerar en uppräkning som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar en synkroniseringsrot. |
| [deepClone()](#deepClone--) | Skapar en kopia av en ColorOperationCollection-samling. |
| [cloneT()](#cloneT--) | Klonar aktuellt objekt |
### size() {#size--}
```
public final int size()
```

Returnerar antalet operationer i en samling. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Returnerar eller anger operationen på det angivna indexet. Läs/skriv [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Returnerar eller anger operationen på det angivna indexet. Läs/skriv [ColorOperation](../../com.aspose.slides/coloroperation).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Lägger till en ny operation i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operation | int | Operationstyp. |
| parameter | float | Operationens parameter. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Lagt till operation.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Lägger till en ny operation i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operation | int | Operationstyp. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Lagt till operation.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Infogar den nya operationen i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Index där operationen ska infogas. |
| operation | int | Operationstyp. |
| parameter | float | Operationens parameter. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Infogad operation.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Infogar den nya operationen i en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | int | Index där operationen ska infogas. |
| operation | int | Operationstyp. |

**Returnerar:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Infogad operation.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort färgoperationen från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en färgoperation att ta bort. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla färgoperationer.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Returnerar en uppräkning som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray. |
| index | int | Startindex i målarrayen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar en synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Skapar en kopia av en ColorOperationCollection-samling.

**Returnerar:**
java.lang.Object - Ny [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection)-samling.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Klonar aktuellt objekt

**Returnerar:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Klon