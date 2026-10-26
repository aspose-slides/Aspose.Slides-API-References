---
title: KeyIterator
second_title: Referensi API Aspose.Slides untuk C++
description: Iterator kamus yang menyediakan akses kunci.
type: docs
weight: 365
url: /id/system.collections.generic/keyiterator/
---
## KeyIterator kelas


[Dictionary](../dictionary/) iterator yang menyediakan akses kunci.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Dict | [Dictionary](../dictionary/) kelas. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Menggandakan iterator saat ini. |
| void [DecrementIterator](./decrementiterator/)() override | Memindahkan iterator satu langkah mundur. |
| void [IncrementIterator](./incrementiterator/)() override | Memindahkan iterator satu langkah maju. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Konstruktor pemindahan. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Memindahkan iterator sebanyak langkah yang ditentukan. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Lihat Juga

* Ruang nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)