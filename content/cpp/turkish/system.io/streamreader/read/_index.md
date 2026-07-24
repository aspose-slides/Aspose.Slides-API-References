---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan tek bir karakter okur.
type: docs
weight: 40
url: /tr/system.io/streamreader/read/
---
## StreamReader::Read() yöntemi


Akıştan tek bir karakter okur.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Dönüş Değeri

UTF-16 kodlamasıyla kodlanmış karakteri okur; eğer okunan karakter UTF-16 kodlamasında iki kod noktasına karşılık geliyorsa yalnızca yüksek surrogat döndürülür.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) yöntemi


Akıştan belirtilen sayıdaki karakteri okur, UTF-16 kodlamasına dönüştürür ve oluşan UTF-16 karakterlerini belirtilen konumdan başlayarak belirtilen karakter dizisine yazar.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Akıştan okunan karakterlerin yazılacağı UTF-16 karakter dizisi |
| index | int | **buffer** içinde yazmaya başlanacak 0 tabanlı indeks |
| count | int | Akıştan okunacak karakter sayısı |

### Dönüş Değeri

Akıştan okunan karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [StreamReader](../)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)