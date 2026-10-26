---
title: GetNamespacesInScope()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna uma coleção que contém todos os namespaces atualmente em escopo.
type: docs
weight: 716
url: /pt/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) método


Retorna uma coleção que contém todos os namespaces atualmente em escopo.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Um valor XmlNamespaceScope que especifica o tipo de nós de namespace a serem retornados. |

### Valor de retorno

Um objeto IDictionary que contém todos os namespaces atualmente em escopo. Se o leitor não estiver posicionado em um elemento, um dicionário vazio (sem namespaces) é retornado.

## Veja Também

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)