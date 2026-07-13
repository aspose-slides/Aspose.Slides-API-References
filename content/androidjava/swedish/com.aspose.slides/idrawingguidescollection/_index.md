---
title: IDrawingGuidesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av de justerbara ritningsguiderna.
type: docs
url: /sv/com.aspose.slides/idrawingguidescollection/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Representerar en samling av de justerbara ritningsguiderna.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ritningsguiden efter index. |
| [add(byte orientation, float position)](#add-byte-float-) | Lägger till ritningsguiden i slutet av samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ritningsguiden på angivet index. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [getCount()](#getCount--) | Hämtar antalet alla element i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Returnerar ritningsguiden efter index. Skrivskyddad [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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

Lägger till ritningsguiden i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientation | byte | Orientering av ritningsguiden. |
| position | float | Position för ritningsguiden i punkter. |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort ritningsguiden på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ritningsguiden som ska raderas. |

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