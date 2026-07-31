---
title: DictionaryIterator
second_title: Referensi API Aspose.Slides untuk C++
description: Iterator kamus yang menyediakan notasi KeyValuePair.
type: docs
weight: 157
url: /id/system.collections.generic/dictionaryiterator/
---
## Kelas DictionaryIterator

[Dictionary](../dictionary/) iterator yang menyediakan [KeyValuePair](../keyvaluepair/) notasi.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Dict | [Dictionary](../dictionary/) kelas. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::KeyValuePairType\> * [CloneIterator](./cloneiterator/)() const override | Mengkloning iterator saat ini. |
| void [DecrementIterator](./decrementiterator/)() override | Menggerakkan iterator satu langkah mundur. |
|  [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [DictionaryIterator](./dictionaryiterator/)([DictionaryIterator](./)\&&) | Konstruktor pemindahan. |
| void [IncrementIterator](./incrementiterator/)() override | Menggerakkan iterator satu langkah maju. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Menggerakkan iterator sebanyak jumlah langkah yang ditentukan. |
| virtual  [~DictionaryIterator](./~dictionaryiterator/)() | Destruktor. |

## Lihat Juga

* Ruang Nama [System::Collections::Generic](../)
* Perpustakaan [Aspose.Slides](../../)