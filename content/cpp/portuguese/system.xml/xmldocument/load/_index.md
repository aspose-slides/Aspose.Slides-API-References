---
title: Load()
second_title: Referência da API Aspose.Slides para C++
description: Carrega o documento XML a partir do URL especificado.
type: docs
weight: 508
url: /pt/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) método

Carrega o documento XML a partir da URL especificada.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL do arquivo que contém o documento XML a ser carregado. A URL pode ser um arquivo local ou uma URL HTTP (um endereço [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) método

Carrega o documento XML a partir do fluxo especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | O fluxo contendo o documento XML a ser carregado. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) método

Carrega o documento XML a partir do TextReader especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | O TextReader usado para fornecer os dados XML ao documento. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) método

Carrega o documento XML a partir do [XmlReader](../../xmlreader/) especificado.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | O [XmlReader](../../xmlreader/) usado para fornecer os dados XML ao documento. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)