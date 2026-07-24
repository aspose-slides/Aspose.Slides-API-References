---
title: Write()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bayt dizisinden belirtilen alt aralıktaki baytları temel akışa yazar.
type: docs
weight: 66
url: /tr/system.io/bufferedstream/write/
---
## BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) yöntem

Belirtilen bayt dizisinden belirtilen alt aralıktaki baytları temel akışa yazar.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | Yazma alt aralığının başladığı, **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) yöntem

Belirtilen bayt dizisinden belirtilen alt aralıktaki baytları temel akışa yazar.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| offset | **int32_t** | Yazma alt aralığının başladığı, **buffer** içindeki 0 tabanlı indeks |
| count | **int32_t** | Yazılacak alt aralıktaki eleman sayısı |

## Başvurular

* Tip tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BufferedStream](../)
* Ad alanı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)