---
title: IControlCollection
second_title: Aspose.Slides voor Java API-referentie
description: Een verzameling van ActiveX-besturingselementen.
type: docs
url: /nl/com.aspose.slides/icontrolcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Een verzameling van ActiveX-besturingselementen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Verwijdert een ActiveX-besturingselement uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX-besturingselement op de opgegeven positie uit de collectie. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een besturingselement op de opgegeven positie. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Maakt een nieuw besturingselement aan en voegt het toe aan de collectie. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Verwijdert een ActiveX-besturingselement uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Een te verwijderen besturingselement. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert een ActiveX-besturingselement op de opgegeven positie uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het te verwijderen besturingselement. |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle besturingselementen uit de collectie.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Retourneert een besturingselement op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een besturingselement. |

**Retour:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Maakt een nieuw besturingselement aan en voegt het toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlType | int | Type van het toe te voegen besturingselement. |
| x | float | De X-coördinaat van de linkerkant van het frame van de vorm. |
| y | float | De Y-coördinaat van de bovenkant van het frame van de vorm. |
| width | float | De breedte van het frame van de vorm. |
| height | float | De hoogte van het frame van de vorm. |

**Retour:**
[IControl](../../com.aspose.slides/icontrol) - Aangemaakt besturingselement [IControl](../../com.aspose.slides/icontrol).