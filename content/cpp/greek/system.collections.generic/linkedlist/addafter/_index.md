---
title: AddAfter()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει το στοιχείο μετά τον κόμβο της λίστας.
type: docs
weight: 53
url: /el/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) μέθοδος


Προσθέτει το **element** μετά το **node** της λίστας.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Κόμβος μετά τον οποίο θα εισαχθεί |
| element | const T\& | Στοιχείο προς προσθήκη |

### Τιμή Επιστροφής

Νέος κόμβος.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) μέθοδος


Προσθέτει το **newNode** μετά το **node** της λίστας.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Κόμβος μετά τον οποίο θα εισαχθεί |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Νέος κόμβος προς προσθήκη |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [LinkedListNode](../../linkedlistnode/)
* Κλάση [LinkedList](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)