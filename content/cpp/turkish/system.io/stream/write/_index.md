---
title: Write()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.
type: docs
weight: 53
url: /tr/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki öğelerin sayısı |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki öğelerin sayısı |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metod


Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | Yığın dizisinin boyutu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Yazılacak baytları içeren yığın dizisi |
| offset | **int32_t** | **buffer** içinde yazılacak alt aralığın başladığı 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki öğelerin sayısı |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) metod


Belirtilen bayt aralığından belirtilen bayt alt aralığını akışa yazar.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Yazılmış baytları okumak için bayt aralığı |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Stream](../)
* Sınıf [ReadOnlySpan](../../../system/readonlyspan/)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)