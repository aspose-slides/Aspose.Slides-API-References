---
title: ICellCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Stellt eine Sammlung von Zellen dar.
type: docs
url: /de/com.aspose.slides/icellcollection/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Stellt eine Sammlung von Zellen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Zelle anhand ihrer Position zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Gibt eine Zelle anhand ihrer Position zurück. Nur-Lesen [ICell](../../com.aspose.slides/icell).

--------------------

Ein CellEx-Objekt kann für mehrere Indizes zurückgegeben werden, falls die Zelle zusammengeführt ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ICell](../../com.aspose.slides/icell)