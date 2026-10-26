---
title: SmartArtNodeCollection
second_title: Référence de l'API Aspose.Slides for Java
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

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le nœud à l’indice |
| [size()](#size--) | Renvoie le nombre de nœuds dans la collection Lecture seule int Lecture seule int . |
| [addNode()](#addNode--) | Ajoute un nouveau nœud SmartArt ou sous-nœud. |
| [removeNode(int index)](#removeNode-int-) | Supprime le nœud ou le sous-nœud par indice |
| [removeNode(ISmartArtNode node)](#removeNode-com.aspose.slides.ISmartArtNode-) | Supprime le nœud ou le sous-nœud |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Ajoute un nouveau nœud à la position sélectionnée de la collection de nœuds |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |

### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtNode get_Item(int index)
```

Renvoie le nœud à l’indice

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de l’élément |

**Renvoie:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Le nœud SmartArt

### size() {#size--}
```
public final int size()
```

Renvoie le nombre de nœuds dans la collection Lecture seule int Lecture seule int .

**Renvoie:**  
int

### addNode() {#addNode--}
```
public final ISmartArtNode addNode()
```

Ajoute un nouveau nœud SmartArt ou sous-nœud.

**Renvoie:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté

### removeNode(int index) {#removeNode-int-}
```
public final void removeNode(int index)
```

Supprime le nœud ou le sous-nœud par indice

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indice basé sur zéro du nœud |

### removeNode(ISmartArtNode node) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public final void removeNode(ISmartArtNode node)
```

Supprime le nœud ou le sous-nœud

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| node | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nœud à supprimer |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public final ISmartArtNode addNodeByPosition(int position)
```

Ajoute un nouveau nœud à la position sélectionnée de la collection de nœuds

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | Position du nœud basée sur zéro |

**Renvoie:**  
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtNode> iteratorJava()
```

Renvoie un itérateur java pour l’ensemble de la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtNode> - Un java.util.Iterator pour l’ensemble de la collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Lecture seule boolean .

**Renvoie:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie:**  
java.lang.Object