---
title: Write()
second_title: C++ API Referansı için Aspose.Slides
description: Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.
type: docs
weight: 92
url: /tr/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | Yazma alt aralığının başladığı **buffer** içindeki 0 tabanlı eleman indeksi |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi görünümü |
| offset | **int32_t** | Yazma alt aralığının başladığı **buffer** içindeki 0 tabanlı eleman indeksi |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [MemoryStream](../)
* Ad alanı [System::IO](../../)
* Library [Aspose.Slides](../../../)