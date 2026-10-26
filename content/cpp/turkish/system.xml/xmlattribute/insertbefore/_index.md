---
title: InsertBefore()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen düğümü, belirtilen referans düğümünün hemen önüne ekler.
type: docs
weight: 209
url: /tr/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) yöntemi

Belirtilen düğümü, belirtilen referans düğümünden hemen önce ekler.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Eklenecek [XmlNode](../../xmlnode/). |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Referans düğüm olan [XmlNode](../../xmlnode/). **newChild** bu düğümün önüne yerleştirilir. |

### Dönüş Değeri

Eklenecek [XmlNode](../../xmlnode/).

## Başvurular

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)