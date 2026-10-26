---
title: MoveToAttribute()
second_title: Aspose.Slides for C++ API Referansı
description: "Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen XmlReader::get_Name değerine sahip niteliğe geçer."
type: docs
weight: 625
url: /tr/system.xml/xmlreader/movetoattribute/
---
## XmlReader::MoveToAttribute(String) method

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../get_name/) değerine sahip niteliğe geçer.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Niteliğin nitelikli adı. |

### Dönüş Değeri

**true** niteliğin bulunması durumunda; aksi takdirde **false**. **false** ise okuyucunun konumu değişmez.

## XmlReader::MoveToAttribute(String, String) method

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerine sahip niteliğe geçer.

```cpp
virtual bool System::Xml::XmlReader::MoveToAttribute(String name, String ns)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Niteliğin yerel adı. |
| ns | [String](../../../system/string/) | Niteliğin ad alanı URI'si. |

### Dönüş Değeri

**true** niteliğin bulunması durumunda; aksi takdirde **false**. **false** ise okuyucunun konumu değişmez.

## XmlReader::MoveToAttribute(int32_t) method

Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeksdeki niteliğe geçer.

```cpp
virtual void System::Xml::XmlReader::MoveToAttribute(int32_t i)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| i | **int32_t** | Niteliğin indeksi. |

## Diğer

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)