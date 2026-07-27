---
title: ValueAs()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor do item como o tipo especificado.
type: docs
weight: 131
url: /pt/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) método

Retorna o valor do item como o tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo para o qual retornar o valor do item. |

### Valor de Retorno

O valor do item como o tipo solicitado.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Quando sobrescrito em uma classe derivada, retorna o valor do item como o tipo especificado usando o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo para o qual retornar o valor do item. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace. |

### Valor de Retorno

O valor do item como o tipo solicitado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XPathItem](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)