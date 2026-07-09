---
title: IDrawingGuidesCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de guides de dessin réglables.
type: docs
url: /fr/com.aspose.slides/idrawingguidescollection/
---
**Toutes les interfaces implémentées:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Représente une collection de guides de dessin réglables.

## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le guide de dessin par index. |
| [add(byte orientation, float position)](#add-byte-float-) | Ajoute le guide de dessin à la fin de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime le guide de dessin à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [getCount()](#getCount--) | Obtient le nombre de tous les éléments de la collection. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

Renvoie le guide de dessin par index. Lecture seule [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourne :**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

Ajoute le guide de dessin à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientation | byte | Orientation du guide de dessin. |
| position | float | Position du guide de dessin en points. |

**Retourne :**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime le guide de dessin à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index du guide de dessin qui doit être supprimé. |

### clear() {#clear--}
```
public abstract void clear()
```

Supprime tous les éléments de la collection.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtient le nombre de tous les éléments de la collection. Lecture seule int.

**Retourne :**
int