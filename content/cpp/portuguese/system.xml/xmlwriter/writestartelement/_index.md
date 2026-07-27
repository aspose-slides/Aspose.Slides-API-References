---
title: WriteStartElement()
second_title: Aspose.Slides para C++ Referência da API
description: Quando sobrescrito em uma classe derivada, grava a tag de início especificada e a associa ao namespace fornecido.
type: docs
weight: 92
url: /pt/system.xml/xmlwriter/writestartelement/
---
## XmlWriter::WriteStartElement(const String\&, const String\&) método

Quando sobrescrito em uma classe derivada, grava a tag de início especificada e a associa ao namespace fornecido.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName, const String &ns)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do elemento. |
| ns | const [String](../../../system/string/)\& | O URI do namespace a ser associado ao elemento. Se esse namespace já estiver no escopo e possuir um prefixo associado, o escritor grava esse prefixo automaticamente. |

## XmlWriter::WriteStartElement(const String\&, const String\&, const String\&) método

Quando sobrescrito em uma classe derivada, grava a tag de início especificada e a associa ao namespace e ao prefixo fornecidos.

```cpp
virtual void System::Xml::XmlWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do namespace do elemento. |
| localName | const [String](../../../system/string/)\& | O nome local do elemento. |
| ns | const [String](../../../system/string/)\& | O URI do namespace a ser associado ao elemento. |

## XmlWriter::WriteStartElement(const String\&) método

Quando sobrescrito em uma classe derivada, grava uma tag de início com o nome local especificado.

```cpp
void System::Xml::XmlWriter::WriteStartElement(const String &localName)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do elemento. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)