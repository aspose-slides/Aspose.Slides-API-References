---
title: ICellCollection
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een verzameling cellen voor.
type: docs
url: /nl/com.aspose.slides/icellcollection/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Stelt een verzameling cellen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert een cel op basis van zijn positie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Retourneert een cel op basis van zijn positie. Alleen-lezen [ICell](../../com.aspose.slides/icell).

--------------------

Een CellEx-object kan voor meerdere indexen worden geretourneerd als de cel is samengevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ICell](../../com.aspose.slides/icell)