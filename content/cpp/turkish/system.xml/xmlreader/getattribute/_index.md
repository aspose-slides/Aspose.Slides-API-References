---
title: GetAttribute()
second_title: Aspose.Slides için C++ API Referansı
description: "Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen XmlReader::get_Name değerine sahip öznitelğin değerini alır."
type: docs
weight: 599
url: /tr/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metot

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../get_name/) değerine sahip öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin nitelikli adı. |

### Dönüş Değeri

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa veya değer [String::Empty](../../../system/string/empty/) ise, **nullptr** döndürülür.

## XmlReader::GetAttribute(String, String) metot

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerine sahip öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Özniteliğin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Özniteliğin ad alanı URI'si. |

### Dönüş Değeri

Belirtilen özniteliğin değeri. Öznitelik bulunamazsa veya değer [String::Empty](../../../system/string/empty/) ise, **nullptr** döndürülür. Bu metot okuyucuyu ilerletmez.

## XmlReader::GetAttribute(int32_t) metot

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeks değerine sahip öznitelğin değerini alır.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Özniteliğin indeksi. İndeks sıfır tabanlıdır. (İlk öznitelik indeks 0'dadır.) |

### Dönüş Değeri

Belirtilen özniteliğin değeri. Bu metot okuyucuyu ilerletmez.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)