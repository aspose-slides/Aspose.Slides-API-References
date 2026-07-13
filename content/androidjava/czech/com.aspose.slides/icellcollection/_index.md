---
title: ICellCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci buněk.
type: docs
url: /cs/com.aspose.slides/icellcollection/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Představuje kolekci buněk.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací buňku podle její pozice. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Vrací buňku podle její pozice. Jen pro čtení [ICell](../../com.aspose.slides/icell).

--------------------

Objekt CellEx může být vrácen pro několik indexů v případě, že je buňka sloučena.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ICell](../../com.aspose.slides/icell)