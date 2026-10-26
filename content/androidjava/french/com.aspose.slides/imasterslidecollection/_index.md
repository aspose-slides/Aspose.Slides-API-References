---
title: IMasterSlideCollection
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente une collection de diapositives maîtres.
type: docs
url: /fr/com.aspose.slides/imasterslidecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Représente une collection de diapositives maîtres.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Supprime la première occurrence d'un objet spécifique de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Supprime les diapositives maîtres inutilisées. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Ajoute une copie d'une diapositive maîtresse spécifiée à la fin de la collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Insère une copie d'une diapositive maîtresse spécifiée à la position spécifiée de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [IMasterSlide](../../com.aspose.slides/imasterslide).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositive maîtresse à supprimer de la collection. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime l'élément à l'index spécifié de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


Supprime les diapositives maîtres inutilisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| ignorePreserveField | boolean | Détermine si cette méthode doit supprimer les maîtres inutilisés même si sa propriété [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) est définie sur vrai. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


Ajoute une copie d'une diapositive maîtresse spécifiée à la fin de la collection. Les diapositives de mise en page liées seront également copiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive à cloner. |

**Retour :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositive ajoutée.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Insère une copie d'une diapositive maîtresse spécifiée à la position spécifiée de la collection. Les diapositives de mise en page liées seront également copiées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle diapositive. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositive à cloner. |

**Retour :**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositive maîtresse insérée.