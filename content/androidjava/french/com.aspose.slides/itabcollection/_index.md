---
title: ITabCollection
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente une collection d'onglets.
type: docs
url: /fr/com.aspose.slides/itabcollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Représente une collection d'onglets.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index indiqué. |
| [add(double position, int align)](#add-double-int-) | Ajoute un onglet à la collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Ajoute un onglet à la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index indiqué de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Obtient l'élément à l'index indiqué. Lecture seule [ITab](../../com.aspose.slides/itab).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Ajoute un onglet à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | double | Position de l'onglet. |
| align | int | Alignement de l'onglet. |

**Renvoie :**
[ITab](../../com.aspose.slides/itab) - Onglet ajouté.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Ajoute un onglet à la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | L'objet Tab à ajouter à la fin de la collection. |

**Renvoie :**
int - L'indice auquel l'onglet a été ajouté.
### clear() {#clear--}
```
public abstract void clear()
```


Supprime tous les éléments de la collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Supprime l'élément à l'index indiqué de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément à supprimer. |