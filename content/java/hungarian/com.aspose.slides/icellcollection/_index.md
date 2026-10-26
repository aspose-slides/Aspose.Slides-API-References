---
title: ICellCollection
second_title: Aspose.Slides Java API referencia
description: Cellákat tartalmazó gyűjteményt reprezentál.
type: docs
url: /hu/com.aspose.slides/icellcollection/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Cellákat tartalmazó gyűjteményt reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy cellát a pozíciója alapján. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Visszaad egy cellát a pozíciója alapján. Csak olvasható [ICell](../../com.aspose.slides/icell).

--------------------

Egy CellEx objektum több indexhez is visszaadható, ha a cella egyesítve van.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ICell](../../com.aspose.slides/icell)