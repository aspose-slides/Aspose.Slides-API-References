---
title: Read()
second_title: Référence API Aspose.Slides pour C++
description: "Lit un schéma XML depuis le IO::TextReader fourni."
type: docs
weight: 365
url: /fr/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) méthode

Lit un XML [Schema](../../) depuis le [IO::TextReader](../../../system.io/textreader/) fourni.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Le [IO::TextReader](../../../system.io/textreader/) contenant le XML [Schema](../../) à lire. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Le gestionnaire d'événements de validation qui reçoit des informations sur les erreurs de syntaxe du XML [Schema](../../). |

### Valeur de retour

L'objet [XmlSchema](../) représentant le XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) méthode

Lit un XML [Schema](../../) depuis le flux fourni.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Le flux de données fourni. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Le gestionnaire d'événements de validation qui reçoit des informations sur les erreurs de syntaxe du XML [Schema](../../). |

### Valeur de retour

L'objet [XmlSchema](../) représentant le XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) méthode

Lit un XML [Schema](../../) depuis le [XmlReader](../../../system.xml/xmlreader/) fourni.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Le [XmlReader](../../../system.xml/xmlreader/) contenant le XML [Schema](../../) à lire. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Le gestionnaire d'événements de validation qui reçoit des informations sur les erreurs de syntaxe du XML [Schema](../../). |

### Valeur de retour

L'objet [XmlSchema](../) représentant le XML [Schema](../../).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)