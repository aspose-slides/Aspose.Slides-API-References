---
title: Schemas()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en samling av alla XML Schema definitionsspråk (XSD) scheman i XmlSchemaSet.
type: docs
weight: 248
url: /sv/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


Returnerar en samling av alla XML [Schema](../../) definitionsspråk (XSD) scheman i [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Return Value

Ett IList-objekt som innehåller alla scheman som har lagts till i [XmlSchemaSet](../). Om inga scheman har lagts till i [XmlSchemaSet](../) returneras en tom samling.

## XmlSchemaSet::Schemas(String) method


Returnerar en samling av alla XML [Schema](../../) definitionsspråk (XSD) scheman i [XmlSchemaSet](../) som tillhör den angivna namnrymden.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Schemaegenskapen **targetNamespace**. |

### Return Value

Ett IList-objekt som innehåller alla scheman som har lagts till i [XmlSchemaSet](../) som tillhör den angivna namnrymden. Om inga scheman har lagts till i [XmlSchemaSet](../) returneras en tom samling.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IList](../../../system.collections.generic/ilist/)
* Klass [XmlSchema](../../xmlschema/)
* Klass [XmlSchemaSet](../)
* Klass [List](../../../system.collections.generic/list/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)