---
title: SmartArtNodeCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection de nœuds SmartArt.
type: docs
url: /fr/com.aspose.slides/smartartnodecollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
```
public final class SmartArtNodeCollection implements ISmartArtNodeCollection
```

Représente une collection de nœuds SmartArt.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le nœud à l'indice |
| [size()](#size--) | Renvoie le nombre de nœuds dans la collection Lecture seule  int  Lecture seule  int . |
| [addNode()](#addNode--) | Ajoute un nouveau nœud SmartArt ou sous-nœud. |
| [removeNode(int index)](#removeNode-int-) | Supprime le nœud ou le sous-nœud par indice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Supprime le nœud ou le sous-nœud |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Ajoute un nouveau nœud à la position sélectionnée dans la collection de nœuds |
| [iterator()](#iterator--) | Renvoie un énumérateur qui itère à travers la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Renvoie le nœud à l'indice

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'indice basé sur zéro de l'élément |

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Le nœud SmartArt
### size() {#size--}
```
public final int size()
```

Renvoie le nombre de nœuds dans la collection Lecture seule  int  Lecture seule  int .

**Retour :**
int
### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Ajoute un nouveau nœud SmartArt ou sous-nœud.

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté
### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Supprime le nœud ou le sous-nœud par indice

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice basé sur zéro du nœud |
### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Supprime le nœud ou le sous-nœud

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nœud à supprimer |
### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Ajoute un nouveau nœud à la position sélectionnée dans la collection de nœuds

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | Position du nœud, basée sur zéro |

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Renvoie un énumérateur qui itère à travers la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un java.util.Iterator pour l'ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule  boolean .

**Retour :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie la racine de synchronisation. Lecture seule Object.

**Retour :**
java.lang.Object