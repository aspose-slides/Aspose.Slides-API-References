---
title: ILayoutSlideCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente une classe de base pour la collection de diapositives de mise en page.
type: docs
url: /fr/com.aspose.slides/ilayoutslidecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Représente une classe de base pour la collection de diapositives de mise en page.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie la diapositive de mise en page par indice. |
| [getByType(byte type)](#getByType-byte-) | Renvoie la première diapositive de mise en page du type spécifié. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Supprime une mise en page de la collection. |
| [removeUnused()](#removeUnused--) | Supprime les diapositives de mise en page inutilisées (diapositives de mise en page dont la propriété HasDependingSlides est false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Renvoie la diapositive de mise en page par indice. Lecture seule [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Renvoie la première diapositive de mise en page du type spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | byte | Un type de diapositive de mise en page à rechercher. |

**Retour :**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) avec le type spécifié ou null si aucune mise en page n'est trouvée.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Supprime une mise en page de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositive de mise en page à supprimer de la collection.

--------------------

1) Pour éviter le lancement de PptxEditException, vérifiez la propriété HasDependingSlides de la mise en page au préalable. 2) Vous pouvez également utiliser la méthode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pour simplifier le code. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Supprime les diapositives de mise en page inutilisées (diapositives de mise en page dont la propriété HasDependingSlides est false).