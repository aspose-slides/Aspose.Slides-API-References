---
title: ValueAs()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do nó atual como o Type especificado, usando o objeto IXmlNamespaceResolver especificado para resolver os prefixos de namespace.
type: docs
weight: 378
url: /pt/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método


Retorna o valor do nó atual como o Type especificado, usando o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver os prefixos de namespace.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O Type para o qual retornar o valor do nó atual. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver os prefixos de namespace. |

### Valor de Retorno

O valor do nó atual como o Type solicitado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathNavigator](../)
* Espaço de nomes [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)