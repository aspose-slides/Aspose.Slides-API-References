---
title: ICellCollection
second_title: Aspose.Slides pro Java – referenční příručka API
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
| [get_Item(int index)](#get-Item-int-) | Vrátí buňku podle její pozice. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Vrátí buňku podle její pozice. Pouze pro čtení [ICell](../../com.aspose.slides/icell).

--------------------

Jedna instance CellEx může být vrácena pro několik indexů, pokud je buňka sloučena.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrácená hodnota:**
[ICell](../../com.aspose.slides/icell)