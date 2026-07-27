---
title: Validate()
second_title: Referência da API Aspose.Slides para C++
description: "Valida o XmlDocument contra os esquemas XML Schema Definition Language (XSD) contidos na lista XmlDocument::get_Schemas."
type: docs
weight: 573
url: /pt/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) método


Valida o [XmlDocument](../) contra os esquemas XML [Schema](../../../system.xml.schema/) Definition Language (XSD) contidos na lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | O objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recebe informações sobre avisos e erros de validação de esquema. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) método


Valida o objeto [XmlNode](../../xmlnode/) especificado contra os esquemas XML [Schema](../../../system.xml.schema/) Definition Language (XSD) na lista [XmlDocument::get_Schemas](../get_schemas/).

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | O objeto [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) que recebe informações sobre avisos e erros de validação de esquema. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | O objeto [XmlNode](../../xmlnode/) criado a partir de um [XmlDocument](../) para validação. |

## Veja Também

* Typedef [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlDocument](../)
* Classe [XmlNode](../../xmlnode/)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)