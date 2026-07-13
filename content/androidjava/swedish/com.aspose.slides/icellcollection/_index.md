---
title: ICellCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling celler.
type: docs
url: /sv/com.aspose.slides/icellcollection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Representerar en samling celler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar en cell efter dess position. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Returnerar en cell efter dess position. Skrivskyddad [ICell](../../com.aspose.slides/icell).

--------------------

Ett CellEx-objekt kan returneras för flera index om cellen är sammanslagen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ICell](../../com.aspose.slides/icell)