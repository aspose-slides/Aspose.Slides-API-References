---
title: Reprocess()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Znovu zpracuje schéma XML Schema definition language (XSD), které již existuje v XmlSchemaSet.
type: docs
weight: 222
url: /cs/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) metoda

Znovu zpracuje XML [Schema](../../) definition language (XSD) schéma, které již existuje v [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | Schéma k opětovnému zpracování. |

### Návratová hodnota

Objekt [XmlSchema](../../xmlschema/), pokud je schéma platné. Pokud schéma není platné a je zadán ValidationEventHandler, vrátí se **nullptr** a vyvolá se příslušná validační událost. V opačném případě je vyhozena výjimka XmlSchemaException.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlSchema](../../xmlschema/)
* Třída [XmlSchemaSet](../)
* Jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)