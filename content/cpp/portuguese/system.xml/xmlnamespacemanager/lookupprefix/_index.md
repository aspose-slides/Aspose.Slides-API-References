---
title: LookupPrefix()
second_title: Referência da API Aspose.Slides para C++
description: Encontra o prefixo declarado para o URI do namespace fornecido.
type: docs
weight: 131
url: /pt/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) método

Encontra o prefixo declarado para o URI do namespace fornecido.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | O namespace a ser resolvido para o prefixo. |

### Valor de Retorno

O prefixo correspondente. Se não houver prefixo mapeado, o método retorna [String::Empty](../../../system/string/empty/). Se um valor nulo for fornecido, então **nullptr** é retornado.

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)