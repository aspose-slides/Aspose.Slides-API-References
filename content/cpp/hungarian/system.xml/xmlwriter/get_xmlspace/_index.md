---
title: get_XmlSpace()
second_title: Aspose.Slides C++ API referenciája
description: "Ha felülírják egy leszármazott osztályban, egy XmlSpace-ot ad vissza, amely az aktuális xml:space hatókört képviseli."
type: docs
weight: 27
url: /hu/system.xml/xmlwriter/get_xmlspace/
---
## XmlWriter::get_XmlSpace() metódus


When overridden in a derived class, gets an XmlSpace representing the current **xml:space** scope.

```cpp
virtual System::Xml::XmlSpace System::Xml::XmlWriter::get_XmlSpace()
```


### Visszatérési érték

An XmlSpace representing the current **xml:space** scope.



| Érték | Jelentés |
| --- | --- |
| `None`| Ez az alapértelmezett, ha nincs `xml:space` hatókör. |
| `Default`| Az aktuális hatókör `xml:space="default"`. |
| `Preserve`| Az aktuális hatókör `xml:space="preserve"`. |


## Lásd még

* Enum [XmlSpace](../../xmlspace/)
* Osztály [XmlWriter](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)