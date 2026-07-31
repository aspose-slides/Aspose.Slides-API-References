---
title: ValueIterator
second_title: Referensi API Aspose.Slides untuk C++
description: Iterator kamus yang menyediakan akses nilai.
type: docs
weight: 625
url: /id/system.collections.generic/valueiterator/
---
## ValueIterator kelas

[Dictionary](../dictionary/) iterator yang menyediakan akses nilai.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Dict | [Dictionary](../dictionary/) kelas. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::mapped_type\> * [CloneIterator](./cloneiterator/)() const override | Menggandakan iterator saat ini. |
| void [DecrementIterator](./decrementiterator/)() override | Memindahkan iterator satu langkah ke belakang. |
| void [IncrementIterator](./incrementiterator/)() override | Memindahkan iterator satu langkah ke depan. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Memindahkan iterator sebanyak jumlah langkah yang ditentukan. |
|  [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [ValueIterator](./valueiterator/)([ValueIterator](./)\&&) | Konstruktor pemindahan. |
| virtual  [~ValueIterator](./~valueiterator/)() | Penghancur. |

## Lihat Juga

* Namespace [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)