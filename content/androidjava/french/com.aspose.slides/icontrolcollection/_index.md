---
title: IControlCollection
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Une collection de contrôles ActiveX.
type: docs
url: /fr/com.aspose.slides/icontrolcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

Une collection de contrôles ActiveX.
## Méthodes

| Méthode | Description |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Supprime un contrôle ActiveX de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un contrôle ActiveX stocké à la position spécifiée de la collection. |
| [clear()](#clear--) | Supprime tous les contrôles de la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie un contrôle à la position spécifiée. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crée et ajoute un nouveau contrôle à la collection. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Supprime un contrôle ActiveX de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un contrôle à supprimer. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime un contrôle ActiveX stocké à la position spécifiée de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du contrôle à supprimer. |

### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les contrôles de la collection.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Renvoie un contrôle à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du contrôle. |

**Retour :**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Crée et ajoute un nouveau contrôle à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlType | int | Type d'un contrôle à ajouter. |
| x | float | La coordonnée X du côté gauche du cadre de la forme. |
| y | float | La coordonnée Y du côté supérieur du cadre de la forme. |
| width | float | La largeur du cadre de la forme. |
| height | float | La hauteur du cadre de la forme. |

**Retour :**
[IControl](../../com.aspose.slides/icontrol) - Contrôle créé [IControl](../../com.aspose.slides/icontrol).