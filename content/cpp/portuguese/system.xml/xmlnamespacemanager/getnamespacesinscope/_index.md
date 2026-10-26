---
title: GetNamespacesInScope()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção de nomes de espaços de nomes indexados por prefixo que pode ser usada para enumerar os espaços de nomes atualmente em escopo.
type: docs
weight: 105
url: /pt/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) método


Retorna uma coleção de nomes de espaço de nomes indexados por prefixo que pode ser usada para enumerar os espaços de nomes atualmente em escopo.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Um valor de enumeração que especifica o tipo de nós de espaço de nomes a serem retornados. |

### Valor de retorno

Uma coleção de pares de espaço de nomes e prefixo atualmente em escopo.

## Veja também

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)