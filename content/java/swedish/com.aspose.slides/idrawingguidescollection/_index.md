---
title: IDrawingGuidesCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av de justerbara ritguiderna.
type: docs
url: /sv/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Representerar en samling av de justerbara ritguiderna.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ritguiden enligt index. |
| [add(byte orientation, float position)](#add-byte-float-) | Lägger till ritguiden i slutet av samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ritguiden på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla element i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Returnerar ritguiden enligt index. Skrivskyddad [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Lägger till ritguiden i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientation | byte | Orientering av ritguiden. |
| position | float | Positionen för ritguiden i punkter. |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort ritguiden på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ritguiden som ska tas bort. |

### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla element från samlingen.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Hämtar antalet alla element i samlingen. Skrivskyddad int.

**Returnerar:**
int