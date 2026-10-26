---
title: ICellCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Cellák gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/icellcollection/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Cellák gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy cellát a pozíciója alapján. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Visszaad egy cellát a pozíciója alapján. Csak olvasható [ICell](../../com.aspose.slides/icell).

--------------------

Több indexhez is visszatérhet egy CellEx objektum, ha a cella össze van vonva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ICell](../../com.aspose.slides/icell)