---
title: ControlCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Een collectie van ActiveX-besturingselementen.
type: docs
url: /nl/com.aspose.slides/controlcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Een collectie van ActiveX besturingselementen.
## Methoden

| Method | Description |
| --- | --- |
| [size()](#size--) | Retourneert het aantal objecten in de collectie. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Maakt een nieuw besturingselement aan en voegt het toe aan de collectie. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Verwijdert een ActiveX besturingselement uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX besturingselement dat zich op een opgegeven positie bevindt uit de collectie. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een besturingselement op de opgegeven positie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert de volledige collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Retourneert het aantal objecten in de collectie. Alleen-lezen int.

**Retourneert:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Maakt een nieuw besturingselement aan en voegt het toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlType | int | Type van een toe te voegen besturingselement. |
| x | float | De X-coördinaat voor de linkerkant van het vormkader. |
| y | float | De Y-coördinaat voor de bovenkant van het vormkader. |
| width | float | De breedte van het vormkader. |
| height | float | De hoogte van het vormkader. |

**Retourneert:**
[IControl](../../com.aspose.slides/icontrol) - Aangemaakt besturingselement.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Verwijdert een ActiveX besturingselement uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Een te verwijderen besturingselement. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een ActiveX besturingselement dat zich op een opgegeven positie bevindt uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een te verwijderen besturingselement. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle besturingselementen uit de collectie.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Retourneert een besturingselement op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een besturingselement. |

**Retourneert:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Een java.util.Iterator voor de volledige collectie.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert de volledige collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray |
| index | int | Index in de doelarray |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert het Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject