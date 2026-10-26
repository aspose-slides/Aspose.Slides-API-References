---
title: ReadStartElement()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir.
type: docs
weight: 846
url: /tr/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metodu

Geçerli düğümün bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) metodu

Geçerli içerik düğümünün verilen [XmlReader::get_Name](../get_name/) değerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | [String](../../../system/string/) | Öğenin nitelikli adı. |

## XmlReader::ReadStartElement(String, String) metodu

Geçerli içerik düğümünün verilen [XmlReader::get_LocalName](../get_localname/) ve [XmlReader::get_NamespaceURI](../get_namespaceuri/) değerlerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Öğenin yerel adı. |
| ns | [String](../../../system/string/) | Öğenin ad alanı URI'si. |

## Ayrıca Bakınız

* Sınıf [XmlReader](../)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)