---
title: idx_get()
second_title: Aspose.Slides C++ için API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeks ile öznitelğin değerini alır.
type: docs
weight: 612
url: /tr/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metod


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeks ile öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Öznitelğin indeksi. |

### Dönüş Değeri

Belirtilen öznitelğin değeri.

## XmlReader::idx_get(String) metod


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../get_name/) değerine sahip öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Öznitelğin nitelikli adı. |

### Dönüş Değeri

Belirtilen öznitelğin değeri. Öznitelik bulunamazsa, **nullptr** döndürülür.

## XmlReader::idx_get(String, String) metod


Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerine sahip öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Öznitelğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öznitelğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen öznitelğin değeri. Öznitelik bulunamazsa, **nullptr** döndürülür.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)