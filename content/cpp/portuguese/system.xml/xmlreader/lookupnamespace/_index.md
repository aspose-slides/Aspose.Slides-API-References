---
title: LookupNamespace()
second_title: Aspose.Slides para C++ Referência da API
description: Quando sobrescrito em uma classe derivada, resolve um prefixo de namespace no escopo do elemento atual.
type: docs
weight: 729
url: /pt/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) método


Quando sobrescrito em uma classe derivada, resolve um prefixo de namespace no escopo do elemento atual.

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | O prefixo cujo URI de namespace você deseja resolver. Para corresponder ao namespace padrão, passe uma string vazia. |

### Valor de retorno

O URI de namespace ao qual o prefixo mapeia ou **nullptr** se nenhum prefixo correspondente for encontrado.

## Veja também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)