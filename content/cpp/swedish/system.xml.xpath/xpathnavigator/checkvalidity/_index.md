---
title: CheckValidity()
second_title: Aspose.Slides för C++ API-referens
description: Verifierar att XML-data i XPathNavigator överensstämmer med den angivna XML Schema definitionsspråket (XSD)-schemat.
type: docs
weight: 755
url: /sv/system.xml.xpath/xpathnavigator/checkvalidity/
---
## XPathNavigator::CheckValidity(SharedPtr\<System::Xml::Schema::XmlSchemaSet\>, System::Xml::Schema::ValidationEventHandler) method


Verifierar att XML-data i [XPathNavigator](../) överensstämmer med XML [Schema](../../../system.xml.schema/)-definitionsspråket (XSD) schema som tillhandahålls.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::CheckValidity(SharedPtr<System::Xml::Schema::XmlSchemaSet> schemas, System::Xml::Schema::ValidationEventHandler validationEventHandler)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schemas | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)\> | XmlSchemaSet-objektet som innehåller scheman som används för att validera XML-data som finns i [XPathNavigator](../). |
| validationEventHandler | [System::Xml::Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | ValidationEventHandler som tar emot information om varningar och fel vid schema-validering. |

### Returvärde

**true** om inga schema valideringsfel inträffade; annars **false**.

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Typdefinition [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Klass [XmlSchemaSet](../../../system.xml.schema/xmlschemaset/)
* Klass [XPathNavigator](../)
* Namnrymd [System::Xml::XPath](../../)
* Bibliotek [Aspose.Slides](../../../)