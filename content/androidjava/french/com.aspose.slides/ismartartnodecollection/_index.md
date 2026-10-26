---
title: ISmartArtNodeCollection
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une collection de nœuds SmartArt.
type: docs
url: /fr/com.aspose.slides/ismartartnodecollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface ISmartArtNodeCollection extends IGenericCollection<ISmartArtNode>
```

Représente une collection de nœuds SmartArt.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie le nœud par index. |
| [addNode()](#addNode--) | Ajoute un nouveau nœud ou sous-nœud. |
| [removeNode(int index)](#removeNode-int-) | Supprime le nœud ou sous-nœud par indice. |
| [removeNode(ISmartArtNode nodeObj)](#removeNode-com.aspose.slides.ISmartArtNode-) | Supprime le nœud ou sous-nœud. |
| [addNodeByPosition(int position)](#addNodeByPosition-int-) | Ajoute un nouveau nœud à la position sélectionnée de la collection de nœuds. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISmartArtNode get_Item(int index)
```


Renvoie le nœud par index. Lecture seule [ISmartArtNode](../../com.aspose.slides/ismartartnode)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de l’élément. |

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode)
### addNode() {#addNode--}
```
public abstract ISmartArtNode addNode()
```


Ajoute un nouveau nœud ou sous-nœud.

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté
### removeNode(int index) {#removeNode-int-}
```
public abstract void removeNode(int index)
```


Supprime le nœud ou sous-nœud par indice.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice basé sur zéro du nœud |

### removeNode(ISmartArtNode nodeObj) {#removeNode-com.aspose.slides.ISmartArtNode-}
```
public abstract void removeNode(ISmartArtNode nodeObj)
```


Supprime le nœud ou sous-nœud.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodeObj | [ISmartArtNode](../../com.aspose.slides/ismartartnode) | Nœud à supprimer. |

### addNodeByPosition(int position) {#addNodeByPosition-int-}
```
public abstract ISmartArtNode addNodeByPosition(int position)
```


Ajoute un nouveau nœud à la position sélectionnée de la collection de nœuds.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | Position du nœud basée sur zéro. |

**Retour :**
[ISmartArtNode](../../com.aspose.slides/ismartartnode) - Nœud ajouté