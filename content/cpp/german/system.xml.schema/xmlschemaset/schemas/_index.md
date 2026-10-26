---
title: Schemas()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt eine Sammlung aller XML Schema-Definitionssprache (XSD)-Schemata im XmlSchemaSet zurück.
type: docs
weight: 248
url: /de/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() Methode

Gibt eine Sammlung aller XML [Schema](../../) Definitionssprache (XSD) Schemata im [XmlSchemaSet](../) zurück.

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```

### Rückgabewert

Ein IList-Objekt, das alle Schemata enthält, die zum [XmlSchemaSet](../) hinzugefügt wurden. Wenn keinen Schemata zum [XmlSchemaSet](../) hinzugefügt wurden, wird eine leere Sammlung zurückgegeben.

## XmlSchemaSet::Schemas(String) Methode

Gibt eine Sammlung aller XML [Schema](../../) Definitionssprache (XSD) Schemata im [XmlSchemaSet](../) zurück, die zum angegebenen Namespace gehören.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Die **targetNamespace**-Eigenschaft. |

### Rückgabewert

Ein IList-Objekt, das alle Schemata enthält, die zum [XmlSchemaSet](../) hinzugefügt wurden und zum angegebenen Namespace gehören. Wenn keinen Schemata zum [XmlSchemaSet](../) hinzugefügt wurden, wird eine leere Sammlung zurückgegeben.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Class [List](../../../system.collections.generic/list/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)