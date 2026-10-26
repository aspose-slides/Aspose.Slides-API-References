---
title: EnumeratorWrapperIterator
second_title: Referensi API Aspose.Slides untuk C++
description: Pengiter yang membungkus enumerator yang sudah dibuat sebelumnya dan mengarahkan semua pemanggilan ke dalamnya.
type: docs
weight: 196
url: /id/system.collections.generic/enumeratorwrapperiterator/
---
## EnumeratorWrapperIterator kelas

Pengiter yang membungkus enumerator yang sudah dibuat sebelumnya dan mengarahkan semua pemanggilan ke dalamnya.

```cpp
template<typename Element>class EnumeratorWrapperIterator : public System::Details::VirtualizedIteratorBase<Element>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Element | Tipe elemen. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<Element\> * [CloneIterator](./cloneiterator/)() const override | Menggandakan iterator saat ini. |
|  [EnumeratorWrapperIterator](./enumeratorwrapperiterator/)(const [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<Element\>\>\&) |  |
| void [IncrementIterator](./incrementiterator/)() override | Memindahkan iterator satu langkah ke depan. Harus memperbarui m_is_end dan m_pointer. |
| **bool** [IteratorEquals](./iteratorequals/)(System::Details::VirtualizedIteratorBase\<Element\> *) const override | Memeriksa apakah dua iterator menunjuk ke item yang sama. |
| virtual  [~EnumeratorWrapperIterator](./~enumeratorwrapperiterator/)() | Penghancur. |

## Lihat Juga

* Ruang nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)