---
title: Compile()
second_title: Aspose.Slides för C++ API-referens
description: Kompilerar XML SchemaObject Model (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering.
type: docs
weight: 352
url: /sv/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) metod


Kompilerar XML [Schema](../../)[Object](../../../system/object/) modell (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Den valideringshändelsehanteraren som tar emot information om XML [Schema](../../) valideringsfel. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) metod


Kompilerar XML [Schema](../../)[Object](../../../system/object/) modell (SOM) till schemainformation för validering. Används för att kontrollera den syntaktiska och semantiska strukturen i det programatiskt byggda SOM. Semantisk valideringskontroll utförs under kompilering.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Den valideringshändelsehanteraren som tar emot information om XML [Schema](../../) valideringsfel. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include** och **import**-element. |

## Se även

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchema](../)
* Klass [XmlResolver](../../../system.xml/xmlresolver/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)