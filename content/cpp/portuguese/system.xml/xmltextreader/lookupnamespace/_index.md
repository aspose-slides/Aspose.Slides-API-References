---
title: LookupNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Resolve um prefixo de namespace no escopo do elemento atual.
type: docs
weight: 612
url: /pt/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) method

Resolve um prefixo de namespace no escopo do elemento atual.

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo cujo URI de namespace você deseja resolver. Para corresponder ao namespace padrão, passe uma string vazia. Esta string não precisa ser atomizada. |

### Valor de retorno

O URI do namespace ao qual o prefixo mapeia ou **nullptr** se nenhum prefixo correspondente for encontrado.

## Veja também

* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)