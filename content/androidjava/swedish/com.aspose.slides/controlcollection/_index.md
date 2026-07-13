---
title: ControlCollection
second_title: Aspose.Slides för Android via Java API-referens
description: En samling av ActiveX-kontroller.
type: docs
url: /sv/com.aspose.slides/controlcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

En samling av ActiveX-kontroller.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Returnerar antalet objekt i samlingen. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Skapar och lägger till en ny kontroll i samlingen. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Tar bort en ActiveX-kontroll från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en ActiveX-kontroll lagrad på angiven position från samlingen. |
| [clear()](#clear--) | Tar bort alla kontroller från samlingen. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en kontroll på den angivna positionen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar hela samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Returnerar antalet objekt i samlingen. Skrivskyddad int.

**Returnerar:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Skapar och lägger till en ny kontroll i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| controlType | int | Typ av kontroll att lägga till. |
| x | float | X-koordinaten för vänstra sidan av formens ram. |
| y | float | Y-koordinaten för övre sidan av formens ram. |
| width | float | Bredden på formens ram. |
| height | float | Höjden på formens ram. |

**Returnerar:**
[IControl](../../com.aspose.slides/icontrol) - Skapad kontroll.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Tar bort en ActiveX-kontroll från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | En kontroll att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort en ActiveX-kontroll lagrad på angiven position från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en kontroll att ta bort. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla kontroller från samlingen.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Returnerar en kontroll på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en kontroll. |

**Returnerar:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - En java.util.Iterator för hela samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar hela samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarray |
| index | int | Index i målarrayen. |

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

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject