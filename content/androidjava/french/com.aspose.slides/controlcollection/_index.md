---
title: ControlCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Une collection de contrôles ActiveX.
type: docs
url: /fr/com.aspose.slides/controlcollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Une collection de contrôles ActiveX.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'objets dans la collection. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crée et ajoute un nouveau contrôle à la collection. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Supprime un contrôle ActiveX de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un contrôle ActiveX stocké à la position spécifiée de la collection. |
| [clear()](#clear--) | Supprime tous les contrôles de la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie un contrôle à la position spécifiée. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie l'ensemble de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'objets dans la collection. Lecture seule int.

**Renvoie :**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Crée et ajoute un nouveau contrôle à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlType | int | Type du contrôle à ajouter. |
| x | float | La coordonnée X du côté gauche du cadre de la forme. |
| y | float | La coordonnée Y du côté supérieur du cadre de la forme. |
| width | float | La largeur du cadre de la forme. |
| height | float | La hauteur du cadre de la forme. |

**Renvoie :**
[IControl](../../com.aspose.slides/icontrol) - Contrôle créé.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Supprime un contrôle ActiveX de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un contrôle à supprimer. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime un contrôle ActiveX stocké à la position spécifiée de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du contrôle à supprimer. |
### clear() {#clear--}
```
public final void clear()
```

Supprime tous les contrôles de la collection.
### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Renvoie un contrôle à la position spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice du contrôle. |

**Renvoie :**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un java.util.Iterator pour l'ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie l'ensemble de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible |
| index | int | Indice dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

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

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject