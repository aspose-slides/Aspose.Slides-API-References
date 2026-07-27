---
title: WriteAttributeString()
second_title: Referência da API Aspose.Slides para C++
description: Quando substituído em uma classe derivada, grava um atributo com o nome local, URI do namespace e valor especificados.
type: docs
weight: 131
url: /pt/system.xml/xmlwriter/writeattributestring/
---
## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&) método


Quando substituído em uma classe derivada, grava um atributo com o nome local, URI do namespace e valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &ns, const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| ns | const [String](../../../system/string/)\& | O URI do namespace a ser associado ao atributo. |
| value | const [String](../../../system/string/)\& | O valor do atributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&) método


Quando substituído em uma classe derivada, grava o atributo com o nome local e valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &localName, const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| value | const [String](../../../system/string/)\& | O valor do atributo. |

## XmlWriter::WriteAttributeString(const String\&, const String\&, const String\&, const String\&) método


Quando substituído em uma classe derivada, grava o atributo com o prefixo, nome local, URI do namespace e valor especificados.

```cpp
void System::Xml::XmlWriter::WriteAttributeString(const String &prefix, const String &localName, const String &ns, const String &value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do namespace do atributo. |
| localName | const [String](../../../system/string/)\& | O nome local do atributo. |
| ns | const [String](../../../system/string/)\& | O URI do namespace do atributo. |
| value | const [String](../../../system/string/)\& | O valor do atributo. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)