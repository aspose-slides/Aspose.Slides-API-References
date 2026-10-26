---
title: Compile()
second_title: Aspose.Slides voor C++ API-referentie
description: Compileert het XML SchemaObject Model (SOM) naar schemainformatie voor validatie. Wordt gebruikt om de syntactische en semantische structuur van de programmatisch gebouwde SOM te controleren. Semantische validatiecontrole wordt uitgevoerd tijdens de compilatie.
type: docs
weight: 352
url: /nl/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) methode


Compileert de XML [Schema](../../)[Object](../../../system/object/) Model (SOM) naar schemainformatie voor validatie. Wordt gebruikt om de syntactische en semantische structuur van de programmatisch gebouwde SOM te controleren. Semantische validatiecontrole wordt uitgevoerd tijdens de compilatie.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | De validation event handler die informatie ontvangt over XML [Schema](../../) validatiefouten. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) methode


Compileert de XML [Schema](../../)[Object](../../../system/object/) Model (SOM) naar schemainformatie voor validatie. Wordt gebruikt om de syntactische en semantische structuur van de programmatisch gebouwde SOM te controleren. Semantische validatiecontrole wordt uitgevoerd tijdens de compilatie.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | De validation event handler die informatie ontvangt over de XML [Schema](../../) validatiefouten. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om namespaces die in **include**- en **import**-elementen worden verwezen, op te lossen. |

## Zie ook

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Naamruimte [System::Xml::Schema](../../)
* Bibliotheek [Aspose.Slides](../../../)