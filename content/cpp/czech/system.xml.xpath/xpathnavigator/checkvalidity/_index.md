---
title: CheckValidity()
second_title: Aspose.Slides pro C++ API Reference
description: Ověřuje, že XML data v XPathNavigator odpovídají definicím jazyka XML Schema (XSD) poskytnutého schématu.
type: docs
weight: 755
url: /cs/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) metoda


Ověřuje, že XML data v [XPathNavigator](../) odpovídají definicím jazyka XML [Schema](../../../system.xml.schema/) (XSD) schématu poskytnutému.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | Instance XmlSchemaSet obsahující schémata používaná k ověření XML dat obsažených v [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | Objekt ValidationEventHandler, který přijímá informace o varováních a chybách při ověřování schématu. |

### Návratová hodnota

**true**, pokud nedošlo k žádným chybám ověření schématu; jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Třída [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Třída [XPathNavigator](../)
* Jmenný prostor [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)