---
title: Validate()
second_title: Riferimento API di Aspose.Slides per C++
description: "Convalida l'XmlDocument contro gli schemi XML Schema Definition Language (XSD) contenuti nell'elenco XmlDocument::get_Schemas."
type: docs
weight: 573
url: /it/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metodo


Convalida il [XmlDocument](../) rispetto agli schemi XML [Schema](../../../system.xml.schema/) Definition Language (XSD) contenuti nell'elenco [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | L'oggetto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) che riceve informazioni sugli avvisi e sugli errori di convalida dello schema. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metodo


Convalida l'oggetto [XmlNode](../../xmlnode/) specificato rispetto agli schemi XML [Schema](../../../system.xml.schema/) Definition Language (XSD) nell'elenco [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | L'oggetto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) che riceve informazioni sugli avvisi e sugli errori di convalida dello schema. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | L'oggetto [XmlNode](../../xmlnode/) creato da un [XmlDocument](../) da convalidare. |

## Vedi anche

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDocument](../)
* Classe [XmlNode](../../xmlnode/)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)