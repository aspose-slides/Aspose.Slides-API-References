---
title: AddBefore()
second_title: Aspose.Slides C++ API Referansı
description: Listenin düğümünden önce öğe ekler.
type: docs
weight: 66
url: /tr/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metot


Listeye **element** öğesini **node** öğesinden önce ekler.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek düğüm |
| element | const T\& | Eklenecek öğe |

### Dönüş Değeri

Yeni düğüm.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metot


Listeye **newNode** öğesini **node** öğesinden önce ekler.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek düğüm |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek yeni düğüm |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [LinkedListNode](../../linkedlistnode/)
* Sınıf [LinkedList](../)
* Ad alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)