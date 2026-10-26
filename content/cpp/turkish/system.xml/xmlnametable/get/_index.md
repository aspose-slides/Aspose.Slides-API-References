---
title: Get()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomikleştirilmiş dizeyi alır.
type: docs
weight: 1
url: /tr/system.xml/xmlnametable/get/
---
## XmlNameTable::Get(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method

Türetilmiş bir sınıfta geçersiz kılındığında, verilen dizideki belirtilen karakter aralığıyla aynı karakterleri içeren atomikleştirilmiş dizeyi alır.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Aranacak ismi içeren karakter dizisi. |
| offset | **int32_t** | İsmin ilk karakterini belirten, dizi içinde sıfır tabanlı indeks. |
| length | **int32_t** | İsmin karakter sayısı. |

### Dönüş Değeri

Atomikleştirilmiş dize ya da dize daha önce atomikleştirilmemişse **nullptr**. **length** sıfır ise, [String::Empty](../../../system/string/empty/) döndürülür.

## XmlNameTable::Get(const String\&) method

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyle aynı değeri içeren atomikleştirilmiş dizeyi alır.

```cpp
virtual const String & System::Xml::XmlNameTable::Get(const String &array)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Aranacak isim. |

### Dönüş Değeri

Atomikleştirilmiş dize ya da dize daha önce atomikleştirilmemişse **nullptr**.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlNameTable](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)