---
title: idx_get()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací XmlSchema spojený s daným URI jmenného prostoru.
type: docs
weight: 53
url: /cs/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) metoda


Vrací [XmlSchema](../../xmlschema/) spojený s daným URI jmenného prostoru.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI jmenného prostoru spojený se schématem, které chcete vrátit. Obvykle se jedná o **targetNamespace** schématu. |

### Návratová hodnota

[XmlSchema](../../xmlschema/) spojený s URI jmenného prostoru; **nullptr**, pokud neexistuje načtené schéma spojené s daným jmenným prostorem nebo pokud je jmenný prostor spojen s XDR schématem.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchema](../../xmlschema/)
* Třída [String](../../../system/string/)
* Třída [XmlSchemaCollection](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Knihovna [Aspose.Slides](../../../)