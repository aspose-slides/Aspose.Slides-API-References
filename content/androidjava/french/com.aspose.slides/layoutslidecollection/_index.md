---
title: LayoutSlideCollection
second_title: Référence API Java d'Aspose.Slides pour Android
description: Représente une classe de base pour la collection de diapositives de mise en page.
type: docs
url: /fr/com.aspose.slides/layoutslidecollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Représente une classe de base pour la collection de diapositives de mise en page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre de diapositives de mise en page dans une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie la diapositive de mise en page à l’index indiqué. |
| [getByType(byte type)](#getByType-byte-) | Renvoie la première diapositive de mise en page du type spécifié. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Supprime une mise en page de la collection. |
| [removeUnused()](#removeUnused--) | Supprime les diapositives de mise en page inutilisées (diapositives dont HasDependingSlides est false). |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre de diapositives de mise en page dans une collection. Lecture seule int.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Renvoie la diapositive de mise en page à l’index indiqué. Lecture seule [LayoutSlide](../../com.aspose.slides/layoutslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Renvoie la première diapositive de mise en page du type spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | byte | Un type de diapositive de mise en page à trouver. |

**Renvoie :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) avec le type indiqué ou null si aucune mise en page n’est trouvée.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Supprime une mise en page de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositive de mise en page à supprimer de la collection.

--------------------

1) Pour éviter le déclenchement de PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable. 2) Vous pouvez également utiliser la méthode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pour simplifier le code. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Supprime les diapositives de mise en page inutilisées (diapositives dont HasDependingSlides est false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Renvoie un itérateur Java pour l’ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un java.util.Iterator pour l’ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l’objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject