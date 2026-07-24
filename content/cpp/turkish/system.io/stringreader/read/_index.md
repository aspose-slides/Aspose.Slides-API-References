---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Akıştan tek bir karakter okur.
type: docs
weight: 40
url: /tr/system.io/stringreader/read/
---
## StringReader::Read() yöntemi


Akıştan tek bir karakter okur.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Dönüş Değeri

Okunan bir karakter ya da hiçbir karakter okunmadıysa -1

## StringReader::Read(ArrayPtr\<char_t\>, int, int) yöntemi


Belirtilen konumdan başlayarak belirli sayıda karakteri akıştan belirtilen karakter dizisine okur.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Akıştan okunan karakterlerin yazılacağı karakter dizisi |
| index | int | **buffer** içinde yazmaya başlanacak 0 tabanlı indis |
| count | int | Akıştan okunacak karakter sayısı |

### Dönüş Değeri

Akıştan okunan karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [StringReader](../)
* İsim Alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)