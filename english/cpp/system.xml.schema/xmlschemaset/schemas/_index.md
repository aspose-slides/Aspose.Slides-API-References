---
title: Schemas()
second_title: Aspose.Slides for C++ API Reference
description: Returns a collection of all the XML Schema definition language (XSD) schemas in the XmlSchemaSet.
type: docs
weight: 248
url: /cpp/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() method


Returns a collection of all the XML [Schema](../../) definition language (XSD) schemas in the [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Return Value

An IList object containing all the schemas that have been added to the [XmlSchemaSet](../). If no schemas have been added to the [XmlSchemaSet](../), an empty collection is returned.

## XmlSchemaSet::Schemas(String) method


Returns a collection of all the XML [Schema](../../) definition language (XSD) schemas in the [XmlSchemaSet](../) that belong to the given namespace.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | The schema **targetNamespace** property. |

### Return Value

An IList object containing all the schemas that have been added to the [XmlSchemaSet](../) that belong to the given namespace. If no schemas have been added to the [XmlSchemaSet](../), an empty collection is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)