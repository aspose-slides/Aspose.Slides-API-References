---
title: ToByteArray()
second_title: Aspose.Slides için C++ API Referansı
description: String veya alt dizeyi bayt dizisine dönüştürür.
type: docs
weight: 508
url: /tr/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const metodu

string veya alt dizeyi bayt dizisine dönüştürür.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | **int32_t** | Alt dize başlangıç indeksi. |
| length | **int32_t** | Alt dize uzunluğu. |
| LE | **bool** | true ise, karakterleri little endian kullanarak kodlar; aksi takdirde big endian kullanır. |

### Dönüş Değeri

[Array](../../array/) içeren, string karakterlerini temsil eden baytlar.

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Sınıf [String](../)
* Ad Alanı [System](../../)
* Library [Aspose.Slides](../../../)