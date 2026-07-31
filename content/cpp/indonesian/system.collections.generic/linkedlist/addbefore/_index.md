---
title: AddBefore()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan elemen sebelum node dalam daftar.
type: docs
weight: 66
url: /id/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) metode

Menambahkan **element** sebelum **node** dalam daftar.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node sebelum mana akan disisipkan |
| element | const T\& | Element untuk ditambahkan |

### Nilai Kembali

Node baru.

## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) metode

Menambahkan **newNode** sebelum **node** dalam daftar.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node sebelum mana akan disisipkan |
| newNode | const [SharedPtr](../../../system/sharedptr/)\<[LinkedListNode](../../linkedlistnode/)\<T\>\>\& | Node baru untuk ditambahkan |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [LinkedListNode](../../linkedlistnode/)
* Kelas [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)