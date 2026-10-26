---
title: Read()
second_title: Riferimento API di Aspose.Slides per C++
description: "Legge uno schema XML dal IO::TextReader fornito."
type: docs
weight: 365
url: /it/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) metodo

Legge un XML [Schema](../../) dal [IO::TextReader](../../../system.io/textreader/) fornito.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Il [IO::TextReader](../../../system.io/textreader/) contenente l'XML [Schema](../../) da leggere. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Il gestore di eventi di validazione che riceve informazioni sugli errori di sintassi XML [Schema](../../). |

### Valore restituito

L'oggetto [XmlSchema](../) che rappresenta l'XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) metodo

Legge un XML [Schema](../../) dal flusso fornito.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Il flusso di dati fornito. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Il gestore di eventi di validazione che riceve informazioni sugli errori di sintassi XML [Schema](../../). |

### Valore restituito

L'oggetto [XmlSchema](../) che rappresenta l'XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) metodo

Legge un XML [Schema](../../) dal [XmlReader](../../../system.xml/xmlreader/) fornito.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Il [XmlReader](../../../system.xml/xmlreader/) contenente l'XML [Schema](../../) da leggere. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Il gestore di eventi di validazione che riceve informazioni sugli errori di sintassi XML [Schema](../../). |

### Valore restituito

L'oggetto [XmlSchema](../) che rappresenta l'XML [Schema](../../).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)