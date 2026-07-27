---
title: WriteStartElement()
second_title: Referência da API Aspose.Slides para C++
description: Escreve a tag de início especificada e a associa ao namespace e prefixo fornecidos.
type: docs
weight: 235
url: /pt/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) método

Escreve a tag de início especificada e a associa ao namespace e prefixo fornecidos.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo do namespace do elemento. |
| localName | const [String](../../../system/string/)\& | O nome local do elemento. |
| ns | const [String](../../../system/string/)\& | O URI do namespace a ser associado ao elemento. Se esse namespace já estiver no escopo e possuir um prefixo associado, o gravador escreverá automaticamente esse prefixo também. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlTextWriter](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)