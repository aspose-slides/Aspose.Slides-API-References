---
title: AddAfter()
second_title: Aspose.Slides for C++ API Referansı
description: Liste düğümünün ardından öğe ekler.
type: docs
weight: 53
url: /tr/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method

Listeye **element** öğesini **node** öğesinin sonrasına ekler.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek düğüm |
| element | const T\& | Eklenecek öğe |

### Dönüş Değeri

Yeni düğüm.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method

Listeye **newNode** öğesini **node** öğesinin sonrasına ekler.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek düğüm |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Eklenecek yeni düğüm |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [LinkedListNode](../../linkedlistnode/)
* Sınıf [LinkedList](../)
* Ad Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)