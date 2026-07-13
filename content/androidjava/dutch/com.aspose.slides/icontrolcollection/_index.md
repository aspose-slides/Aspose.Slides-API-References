---
title: IControlCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Een verzameling ActiveX-besturingselementen.
type: docs
url: /nl/com.aspose.slides/icontrolcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Een verzameling ActiveX-besturingselementen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Verwijdert een ActiveX-besturingselement uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een ActiveX-besturingselement dat op een opgegeven positie in de collectie is opgeslagen. |
| [clear()](#clear--) | Verwijdert alle besturingselementen uit de collectie. |
| [get_Item(int index)](#get-Item-int-) | Geeft een besturingselement op de opgegeven positie terug. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Maakt een nieuw besturingselement aan en voegt dit toe aan de collectie. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

Verwijdert een ActiveX-besturingselement uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Een besturingselement om te verwijderen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert een ActiveX-besturingselement dat op een opgegeven positie in de collectie is opgeslagen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een besturingselement om te verwijderen. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle besturingselementen uit de collectie.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

Geeft een besturingselement op de opgegeven positie terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een besturingselement. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

Maakt een nieuw besturingselement aan en voegt dit toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlType | int | Type van een toe te voegen besturingselement. |
| x | float | De X-coördinaat voor de linkerkant van het vormkader. |
| y | float | De Y-coördinaat voor de bovenkant van het vormkader. |
| width | float | De breedte van het vormkader. |
| height | float | De hoogte van het vormkader. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol) - Aangemaakt besturingselement [IControl](../../com.aspose.slides/icontrol).