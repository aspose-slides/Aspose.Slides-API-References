---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Giriş akışından tek bir karakter okur.
type: docs
weight: 66
url: /tr/system.io/binaryreader/read/
---
## BinaryReader::Read() yöntemi

Giriş akışından tek bir karakter okur.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Dönüş Değeri

UTF-16 kodlamasıyla kodlanmış karakteri okur; eğer okunan karakter UTF-16 kodlamasında iki kod noktasından oluşuyorsa yalnızca yüksek surrogat döndürülür.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) yöntemi

Giriş akışından belirtilen sayıda baytı okur ve bunları belirtilen bayt dizisine yazar.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunan baytların yazılacağı bayt dizisi |
| index | int | **buffer** içinde yazmaya başlanacak 0 tabanlı konum |
| count | int | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan baytların sayısı

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) yöntemi

Giriş akışından belirtilen sayıda karakter okur, bunları UTF-16 kodlamasına dönüştürür ve elde edilen UTF-16 karakterlerini belirtilen konumda başlayan belirtilen karakter dizisine yazar.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Giriş akışından okunan karakterlerin yazılacağı UTF-16 karakter dizisi |
| index | int | **buffer** içinde yazmaya başlanacak 0 tabanlı indeks |
| count | int | Akıştan okunacak karakter sayısı |

### Dönüş Değeri

Giriş akışından okunan karakter sayısı

## Ayrıca

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BinaryReader](../)
* Ad Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)