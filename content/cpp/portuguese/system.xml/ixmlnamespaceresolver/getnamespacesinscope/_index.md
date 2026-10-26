---
title: GetNamespacesInScope()
second_title: Referência da API Aspose.Slides para C++
description: Retorna uma coleção de mapeamentos de prefixo-namespace definidos que estão atualmente no escopo.
type: docs
weight: 1
url: /pt/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) método


Retorna uma coleção de mapeamentos de prefixo-namespace definidos que estão atualmente no escopo.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | Um valor XmlNamespaceScope que especifica o tipo de nós de namespace a ser retornado. |

### Valor de Retorno

Uma coleção IDictionary que contém os namespaces atualmente no escopo.

## Veja Também

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)