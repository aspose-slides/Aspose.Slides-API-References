---
title: ControlCollection
second_title: Aspose.Slides voor Java API-referentie
description: Een verzameling ActiveX-besturingselementen.
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

Een verzameling ActiveX besturingselementen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Geeft een aantal objecten in de collectie terug. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Maakt een nieuw besturingselement aan en voegt het toe aan de collectie. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Verwijdert een ActiveX-besturingselement uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX-besturingselement dat op de opgegeven positie is opgeslagen uit de collectie. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [get_Item(int index)](#get-Item-int-) | Geeft een besturingselement op de opgegeven positie terug. |
| [iterator()](#iterator--) | Geeft een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Geeft een java-iterator voor de volledige collectie terug. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert de volledige collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). |
| [getSyncRoot()](#getSyncRoot--) | Geeft een synchronisatieroot terug. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Geeft een aantal objecten in de collectie terug. Alleen-lezen int.

**Retour:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Maakt een nieuw besturingselement aan en voegt het toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlType | int | Type van het toe te voegen besturingselement. |
| x | float | De X-coördinaat voor de linkerkant van het frame van de vorm. |
| y | float | De Y-coördinaat voor de bovenkant van het frame van de vorm. |
| width | float | De breedte van het frame van de vorm. |
| height | float | De hoogte van het frame van de vorm. |

**Retour:**
[IControl](../../com.aspose.slides/icontrol) - Aangemaakt besturingselement.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Verwijdert een ActiveX-besturingselement uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Een besturingselement om te verwijderen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert een ActiveX-besturingselement dat op de opgegeven positie is opgeslagen uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het te verwijderen besturingselement. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle besturingselementen uit de collectie.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Geeft een besturingselement op de opgegeven positie terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een besturingselement. |

**Retour:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Geeft een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Geeft een java-iterator voor de volledige collectie terug.

**Retour:**
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
| index | int | Index in de doelarray. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Geeft een waarde terug die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-veilig). Alleen-lezen boolean.

**Retour:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Geeft een synchronisatieroot terug. Alleen-lezen Object.

**Retour:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft een Parent_Immediate-object terug. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject