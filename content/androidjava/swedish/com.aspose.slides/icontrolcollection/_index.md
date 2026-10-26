---
title: IControlCollection
second_title: Aspose.Slides för Android via Java API-referens
description: En samling av ActiveX-kontroller.
type: docs
url: /sv/com.aspose.slides/icontrolcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

En samling av ActiveX-kontroller.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Tar bort en ActiveX-kontroll från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en ActiveX-kontroll som lagras på angiven position från samlingen. |
| [clear()](#clear--) | Tar bort alla kontroller från samlingen. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en kontroll på den angivna positionen. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Skapar och lägger till en ny kontroll i samlingen. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Tar bort en ActiveX-kontroll från samlingen.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | En kontroll att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort en ActiveX-kontroll som lagras på angiven position från samlingen.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Index för en kontroll att ta bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla kontroller från samlingen.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Returnerar en kontroll på den angivna positionen.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| index | int | Index för en kontroll. |

**Returnerar:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Skapar och lägger till en ny kontroll i samlingen.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| controlType | int | Typ av kontroll att lägga till. |
| x | float | X-koordinaten för en vänster sida av figurens ram. |
| y | float | Y-koordinaten för en övre sida av figurens ram. |
| width | float | Bredden på figurens ram. |
| height | float | Höjden på figurens ram. |

**Returnerar:**
[IControl](../../com.aspose.slides/icontrol) - Skapad kontroll [IControl](../../com.aspose.slides/icontrol).