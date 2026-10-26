---
title: Remove()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen öğenin listedeki ilk görünümünü kaldırır.
type: docs
weight: 196
url: /tr/system.collections.generic/linkedlist/remove/
---
## LinkedList::Remove(const T\&) metodu


Belirtilen **element**'in listedeki ilk görünümünü kaldırır.

```cpp
bool System::Collections::Generic::LinkedList<T>::Remove(const T &element) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | const T\& | Kaldırılacak element. |

### Dönüş Değeri

True if **element** was found and removed, false otherwise.

## LinkedList::Remove(const SharedPtr\<LinkedListNode\<T\>\>\&) metodu


Düğümü listeden kaldırır.

```cpp
void System::Collections::Generic::LinkedList<T>::Remove(const SharedPtr<LinkedListNode<T>> &node)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Kaldırılacak düğüm. |

## İlgili

* Tip Tanımlaması [SharedPtr](../../../system/sharedptr/)
* Sınıf [LinkedList](../)
* Sınıf [LinkedListNode](../../linkedlistnode/)
* İsim Alanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)