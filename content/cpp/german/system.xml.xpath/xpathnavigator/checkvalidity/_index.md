---
title: CheckValidity()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die XML-Daten im XPathNavigator dem bereitgestellten XML-Schema-Definitionssprache (XSD)-Schema entsprechen.
type: docs
weight: 755
url: /de/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) Methode

Überprüft, ob die XML-Daten in [XPathNavigator](../) dem XML [Schema](../../../system.xml.schema/)-Definitionssprache (XSD)-Schema entsprechen, das bereitgestellt wurde.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | Das XmlSchemaSet, das die Schemata enthält, die zum Validieren der XML-Daten in [XPathNavigator](../) verwendet werden. |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Der ValidationEventHandler, der Informationen über Warnungen und Fehler bei der Schema-Validierung erhält. |

### Rückgabewert

**true** if no schema validation errors occurred; otherwise, **false**.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Klasse [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)