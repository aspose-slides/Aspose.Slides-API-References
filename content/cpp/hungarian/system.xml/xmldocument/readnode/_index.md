---
title: ReadNode()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy XmlNode objektumot az XmlReader információi alapján. Az olvasónak egy csomóponton vagy attribútumon kell állnia.
type: docs
weight: 495
url: /hu/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) metódus


Létrehoz egy [XmlNode](../../xmlnode/) objektumot a [XmlReader](../../xmlreader/) információi alapján. Az olvasónak egy csomóponton vagy attribútumon kell állnia.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Az XML forrás. |

### Visszatérési érték

Az új [XmlNode](../../xmlnode/) vagy **nullptr**, ha már nincs több csomópont.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlReader](../../xmlreader/)
* Osztály [XmlDocument](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)