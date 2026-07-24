---
title: Compile()
second_title: Aspose.Slides für C++ API-Referenz
description: Kompiliert das XML SchemaObject Model (SOM) in Schemainformationen für die Validierung. Wird verwendet, um die syntaktische und semantische Struktur des programmgesteuert erstellten SOM zu überprüfen. Die semantische Validierungsprüfung wird während der Kompilierung durchgeführt.
type: docs
weight: 352
url: /de/system.xml.schema/xmlschema/compile/
---
## XmlSchema::Compile(ValidationEventHandler) Methode

Kompiliert das XML [Schema](../../)[Object](../../../system/object/) Modell (SOM) zu Schemainformationen für die Validierung. Wird verwendet, um die syntaktische und semantische Struktur des programmgesteuert erstellten SOM zu überprüfen. Die semantische Validierungsprüfung wird während der Kompilierung durchgeführt.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Der Validierungsereignis-Handler, der Informationen über XML [Schema](../../) Validierungsfehler empfängt. |

## XmlSchema::Compile(ValidationEventHandler, const SharedPtr\<XmlResolver\>\&) Methode

Kompiliert das XML [Schema](../../)[Object](../../../system/object/) Modell (SOM) zu Schemainformationen für die Validierung. Wird verwendet, um die syntaktische und semantische Struktur des programmgesteuert erstellten SOM zu überprüfen. Die semantische Validierungsprüfung wird während der Kompilierung durchgeführt.

```cpp
void System::Xml::Schema::XmlSchema::Compile(ValidationEventHandler validationEventHandler, const SharedPtr<XmlResolver> &resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Der Validierungsereignis-Handler, der Informationen über XML [Schema](../../) Validierungsfehler empfängt. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Der [XmlResolver](../../../system.xml/xmlresolver/) wird verwendet, um Namespaces, die in **include**- und **import**-Elementen referenziert werden, aufzulösen. |

## Siehe auch

* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlSchema](../)
* Klasse [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Bibliothek [Aspose.Slides](../../../)