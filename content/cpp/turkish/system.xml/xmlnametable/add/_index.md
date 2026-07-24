---
title: Add()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyi atomize eder ve XmlNameTable'a ekler.
type: docs
weight: 14
url: /tr/system.xml/xmlnametable/add/
---
## XmlNameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyi atomize eder ve [XmlNameTable](../)'ye ekler.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const ArrayPtr<char16_t> &array, int32_t offset, int32_t length)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Eklenecek adı içeren karakter dizisi. |
| offset | **int32_t** | Adın ilk karakterini belirten dizi içindeki sıfır tabanlı indeks. |
| length | **int32_t** | Adın karakter sayısı. |

### Dönüş Değeri

Yeni atomize edilmiş dize ya da zaten varsa mevcut dize. Uzunluk sıfır ise [String::Empty](../../../system/string/empty/) döndürülür.

## XmlNameTable::Add(const String\&) metodu

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen dizeyi atomize eder ve [XmlNameTable](../)'ye ekler.

```cpp
virtual const String & System::Xml::XmlNameTable::Add(const String &array)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [String](../../../system/string/)\& | Eklenecek ad. |

### Dönüş Değeri

Yeni atomize edilmiş dize ya da zaten varsa mevcut dize.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)