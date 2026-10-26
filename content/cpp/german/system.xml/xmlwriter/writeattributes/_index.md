---
title: WriteAttributes()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn es in einer abgeleiteten Klasse überschrieben wird, schreibt es alle Attribute, die an der aktuellen Position im XmlReader gefunden wurden.
type: docs
weight: 417
url: /de/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) Methode

Wenn es in einer abgeleiteten Klasse überschrieben wird, schreibt es alle Attribute, die an der aktuellen Position im [XmlReader](../../xmlreader/) gefunden wurden.

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Der [XmlReader](../../xmlreader/), von dem die Attribute kopiert werden. |
| defattr | **bool** | **true** zum Kopieren der Standardattribute aus dem [XmlReader](../../xmlreader/); andernfalls **false**. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlWriter](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)