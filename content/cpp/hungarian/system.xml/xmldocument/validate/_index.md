---
title: Validate()
second_title: Aspose.Slides for C++ API Referenciája
description: "Érvényesíti az XmlDocument-et az XML Schema Definition Language (XSD) sémák ellen, amelyek az XmlDocument::get_Schemas listában találhatók."
type: docs
weight: 573
url: /hu/system.xml/xmldocument/validate/
---
## XmlDocument::Validate(Schema::ValidationEventHandler) metódus

Érvényesíti a [XmlDocument](../)-t az XML [Schema](../../../system.xml.schema/) Definíciós Nyelv (XSD) sémák ellen, amelyek a [XmlDocument::get_Schemas](../get_schemas/) listában találhatók.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | A [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) objektum, amely információkat kap a séma érvényesítési figyelmeztetésekről és hibákról. |

## XmlDocument::Validate(Schema::ValidationEventHandler, const SharedPtr\<XmlNode\>\&) metódus

Érvényesíti a megadott [XmlNode](../../xmlnode/) objektumot az XML [Schema](../../../system.xml.schema/) Definíciós Nyelv (XSD) sémák ellen, amelyek a [XmlDocument::get_Schemas](../get_schemas/) listában vannak.

```cpp
void System::Xml::XmlDocument::Validate(Schema::ValidationEventHandler validationEventHandler, const SharedPtr<XmlNode> &nodeToValidate)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| validationEventHandler | [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) | A [Schema::ValidationEventHandler](../../../system.xml.schema/validationeventhandler/) objektum, amely információkat kap a séma érvényesítési figyelmeztetésekről és hibákról. |
| nodeToValidate | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | A [XmlNode](../../xmlnode/) objektum, amely egy [XmlDocument](../)-ból készült az érvényesítéshez. |

## Lásd még

* Típusdefiníció [ValidationEventHandler](../../../system.xml.schema/validationeventhandler/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlDocument](../)
* Osztály [XmlNode](../../xmlnode/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)