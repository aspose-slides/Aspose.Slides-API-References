---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: "Lê um XML Schema a partir do IO::TextReader fornecido."
type: docs
weight: 365
url: /pt/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) método

Lê um XML [Schema](../../) do [IO::TextReader](../../../system.io/textreader/) fornecido.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O [IO::TextReader](../../../system.io/textreader/) que contém o XML [Schema](../../) para ler. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | O manipulador de evento de validação que recebe informações sobre erros de sintaxe XML [Schema](../../). |

### Valor de Retorno

O objeto [XmlSchema](../) que representa o XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) método

Lê um XML [Schema](../../) do stream fornecido.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O stream de dados fornecido. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | O manipulador de evento de validação que recebe informações sobre erros de sintaxe XML [Schema](../../). |

### Valor de Retorno

O objeto [XmlSchema](../) que representa o XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) método

Lê um XML [Schema](../../) do [XmlReader](../../../system.xml/xmlreader/) fornecido.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O [XmlReader](../../../system.xml/xmlreader/) que contém o XML [Schema](../../) para ler. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | O manipulador de evento de validação que recebe informações sobre erros de sintaxe XML [Schema](../../). |

### Valor de Retorno

O objeto [XmlSchema](../) que representa o XML [Schema](../../).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Classe [XmlSchema](../)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [Stream](../../../system.io/stream/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Espaço de nomes [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)