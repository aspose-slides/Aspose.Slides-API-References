---
title: Read()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.
type: docs
weight: 27
url: /tr/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodu

Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı, yazmaya başlanacak konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodu

Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt dizisi görünümü |
| offset | **int32_t** | **buffer** içinde 0 tabanlı, yazmaya başlanacak konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metodu

Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| N | Yığın dizisinin boyutu |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Okunan baytların yazılacağı bayt yığın dizisi |
| offset | **int32_t** | **buffer** içinde 0 tabanlı, yazmaya başlanacak konum |
| count | **int32_t** | Okunacak bayt sayısı |

### Dönüş Değeri

Okunan bayt sayısı

## Stream::Read(const System::Span\<uint8_t\>\&) metodu

Belirtilen sayıda baytı akıştan okur ve belirtilen bayt aralığına yazar.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Okunan baytların yazılacağı bayt aralığı |

### Dönüş Değeri

Okunan bayt sayısı

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Stream](../)
* Sınıf [Span](../../../system/span/)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)