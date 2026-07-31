---
title: AddAfter()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan elemen setelah node dalam daftar.
type: docs
weight: 53
url: /id/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metode

Menambahkan **elemen** setelah **node** dalam daftar.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node setelah mana akan disisipkan |
| element | const T\& | Elemen yang akan ditambahkan |

### Nilai Kembali

Node baru.

## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metode

Menambahkan **newNode** setelah **node** dalam daftar.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node setelah mana akan disisipkan |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node baru yang akan ditambahkan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [LinkedListNode](../../linkedlistnode/)
* Kelas [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)