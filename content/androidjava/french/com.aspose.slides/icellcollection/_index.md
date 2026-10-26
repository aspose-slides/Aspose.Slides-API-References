---
title: ICellCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de cellules.
type: docs
url: /fr/com.aspose.slides/icellcollection/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Représente une collection de cellules.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie une cellule par sa position. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```

Renvoie une cellule par sa position. Lecture seule [ICell](../../com.aspose.slides/icell).

--------------------

Un objet CellEx peut être renvoyé pour plusieurs index si la cellule est fusionnée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[ICell](../../com.aspose.slides/icell)