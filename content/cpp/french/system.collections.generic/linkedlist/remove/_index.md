---
title: Remove()
second_title: Référence de l'API Aspose.Slides pour C++
description: Supprime la première occurrence de l'élément spécifié de la liste.
type: docs
weight: 196
url: /fr/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) méthode


Supprime la première occurrence de l'**element** spécifié de la liste.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| element | const T\& | Élément à supprimer. |

### Valeur de retour

True si **element** a été trouvé et supprimé, false sinon.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) méthode


Supprime le nœud de la liste.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Nœud à supprimer. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [LinkedList](../)
* Classe [LinkedListNode](../../linkedlistnode/)
* Espace de noms [System::Collections::Generic](../../)
* Bibliothèque [Aspose.Slides](../../../)