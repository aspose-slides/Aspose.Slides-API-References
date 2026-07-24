---
title: ReadToFollowing()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen nitelikli adı taşıyan bir öğe bulunana kadar okur.
type: docs
weight: 898
url: /tr/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) yöntemi

Belirtilen nitelikli adı taşıyan bir öğe bulunana kadar okur.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Öğenin nitelikli adı. |

### Dönüş Değeri

**true** eşleşen bir öğe bulunursa; aksi takdirde **false** ve [XmlReader](../) dosyanın sonu durumundadır.

## XmlReader::ReadToFollowing(String, String) yöntemi

Belirtilen yerel ad ve ad alanı URI'sine sahip bir öğe bulunana kadar okur.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Öğenin yerel adı. |
| namespaceURI | [String](../../../system/string/) | Öğenin ad alanı URI'si. |

### Dönüş Değeri

**true** eşleşen bir öğe bulunursa; aksi takdirde **false** ve [XmlReader](../) dosyanın sonu durumundadır.

## Ayrıca Bakınız

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)