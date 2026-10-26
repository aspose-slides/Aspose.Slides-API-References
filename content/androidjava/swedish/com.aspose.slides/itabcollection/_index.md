---
title: ITabCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling tabbar.
type: docs
url: /sv/com.aspose.slides/itabcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Representerar en samling Tab.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [add(double position, int align)](#add-double-int-) | Lägger till en Tab i samlingen. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Lägger till en Tab i samlingen. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [ITab](../../com.aspose.slides/itab).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Lägger till en Tab i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| position | double | Tab-position. |
| align | int | Tab-justering. |

**Returnerar:**
[ITab](../../com.aspose.slides/itab) - Tillagd Tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Lägger till en Tab i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Det Tab-objekt som ska läggas till i slutet av samlingen. |

**Returnerar:**
int - Indexet där Tab lades till.
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |