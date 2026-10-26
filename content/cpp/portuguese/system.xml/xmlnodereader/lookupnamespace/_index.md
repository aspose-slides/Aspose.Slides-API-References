---
title: LookupNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Resolve um prefixo de namespace no escopo do elemento atual.
type: docs
weight: 404
url: /pt/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) método

Resolve um prefixo de namespace no escopo do elemento atual.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo cujo URI de namespace você deseja resolver. Para corresponder ao namespace padrão, passe uma string vazia. Essa string não precisa ser atomizada. |

### Valor de Retorno

O URI do namespace ao qual o prefixo mapeia ou **nullptr** se nenhum prefixo correspondente for encontrado.

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)