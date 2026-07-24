---
title: Get()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değere sahip atomikleştirilmiş dizeyi döndürür.
type: docs
weight: 27
url: /tr/system.xml/nametable/get/
---
## NameTable::Get(const String\&) yöntemi


Belirtilen değere sahip atomikleştirilmiş dizeyi döndürür.

```cpp
const String & System::Xml::NameTable::Get(const String &value) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Bulunacak isim. |

### Dönüş Değeri

Atomikleştirilmiş dize nesnesi ya da dize daha önce atomikleştirilmemişse **nullptr**.

## NameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) yöntemi


Verilen dizideki belirtilen karakter aralığındaki aynı karakterleri içeren atomikleştirilmiş dizeyi döndürür.

```cpp
const String & System::Xml::NameTable::Get(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Bulunacak ismi içeren karakter dizisi. |
| start | **int32_t** | İsmin ilk karakterini belirten dizideki sıfır tabanlı indeks. |
| len | **int32_t** | İsmin karakter sayısı. |

### Dönüş Değeri

Atomikleştirilmiş dize ya da dize daha önce atomikleştirilmemişse **nullptr**. **len** sıfır ise [String::Empty](../../../system/string/empty/) döndürülür.

## Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [NameTable](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)