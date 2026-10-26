---
title: DrawingGuidesCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de guides de dessin ajustables.
type: docs
url: /fr/com.aspose.slides/drawingguidescollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Représente une collection de guides de dessin ajustables.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le guide de dessin par indice. |
| [add(byte orientation, float position)](#add-byte-float-) | Ajoute le guide de dessin à la fin de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime le guide de dessin à l’indice spécifié. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour la collection entière. |
| [getCount()](#getCount--) | Renvoie le nombre d’éléments de la collection. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Renvoie le guide de dessin par indice. Lecture seule [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Ajoute le guide de dessin à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| orientation | byte | Orientation du guide de dessin. |
| position | float | Position du guide de dessin en points. |

**Renvoie :**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime le guide de dessin à l’indice spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du guide de dessin à supprimer. |

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Renvoie un itérateur Java pour la collection entière.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Un java.util.Iterator pour la collection entière.
### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre d’éléments de la collection. Lecture seule int.

**Renvoie :**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |