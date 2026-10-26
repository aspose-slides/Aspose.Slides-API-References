---
title: Schemas()
second_title: Aspose.Slides voor C++ API Referentie
description: Retourneert een collectie van alle XML Schema definitietaal (XSD) schema's in de XmlSchemaSet.
type: docs
weight: 248
url: /nl/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() methode

Retourneert een verzameling van alle XML [Schema](../../) definitietaal (XSD) schema's in de [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Retourwaarde

Een IList-object dat alle schema's bevat die zijn toegevoegd aan de [XmlSchemaSet](../). Als er geen schema's zijn toegevoegd aan de [XmlSchemaSet](../), wordt een lege verzameling geretourneerd.

## XmlSchemaSet::Schemas(String) methode

Retourneert een verzameling van alle XML [Schema](../../) definitietaal (XSD) schema's in de [XmlSchemaSet](../) die tot de opgegeven namespace behoren.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | De **targetNamespace**-eigenschap van het schema. |

### Retourwaarde

Een IList-object dat alle schema's bevat die zijn toegevoegd aan de [XmlSchemaSet](../) die tot de opgegeven namespace behoren. Als er geen schema's zijn toegevoegd aan de [XmlSchemaSet](../), wordt een lege verzameling geretourneerd.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IList](../../../system.collections.generic/ilist/)
* Klasse [XmlSchema](../../xmlschema/)
* Klasse [XmlSchemaSet](../)
* Klasse [List](../../../system.collections.generic/list/)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)