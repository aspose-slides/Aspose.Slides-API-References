---
title: Remove()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καταργεί την πρώτη εμφάνιση του καθορισμένου στοιχείου από τη λίστα.
type: docs
weight: 196
url: /el/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) μέθοδος

Καταργεί την πρώτη εμφάνιση του καθορισμένου **element** από τη λίστα.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | const T\& | Το στοιχείο προς κατάργηση. |

### Τιμή Επιστροφής

Αληθές αν **element** βρέθηκε και αφαιρέθηκε, ψευδές διαφορετικά.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) μέθοδος

Καταργεί κόμβο από τη λίστα.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Κόμβος προς κατάργηση. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [LinkedList](../)
* Κλάση [LinkedListNode](../../linkedlistnode/)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)