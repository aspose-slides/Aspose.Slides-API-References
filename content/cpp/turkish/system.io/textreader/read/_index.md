---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan tek bir karakter okur.
type: docs
weight: 40
url: /tr/system.io/textreader/read/
---
## TextReader::Read() metod

Akıştan tek bir karakter okur.

```cpp
virtual int System::IO::TextReader::Read()
```

### Dönüş Değeri

UTF-16 kodlamasıyla kodlanmış okunan karakter; eğer okunan karakter UTF-16 kodlamasında iki kod noktasına karşılık geliyorsa yalnızca yüksek surrogate döndürülür.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) metod

Akıştan belirtilen sayıda karakter okur ve belirtilen konumdan başlayarak belirtilen karakter dizisine yazar.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Akıştan okunan karakterlerin yazılacağı UTF-16 karakter dizisi |
| index | int | **buffer** içinde yazmaya başlanacak 0 tabanlı indeks |
| count | int | Akıştan okunacak karakter sayısı |

### Dönüş Değeri

Akıştan okunan karakter sayısı

## İlgili

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [TextReader](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)