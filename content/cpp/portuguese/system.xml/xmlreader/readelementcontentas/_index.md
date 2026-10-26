---
title: ReadElementContentAs()
second_title: Referência da API Aspose.Slides para C++
description: Lê o conteúdo do elemento como o tipo solicitado.
type: docs
weight: 586
url: /pt/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método


Lê o conteúdo do elemento como o tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo do valor a ser retornado. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Um objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que é usado para resolver quaisquer prefixos de namespace relacionados à conversão de tipo. |

### Valor de Retorno

O conteúdo do elemento convertido para o objeto tipado solicitado.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) método


Verifica se o nome local especificado e o URI do namespace correspondem ao do elemento atual, então lê o conteúdo do elemento como o tipo solicitado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo do valor a ser retornado. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Um objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que é usado para resolver quaisquer prefixos de namespace relacionados à conversão de tipo. |
| localName | [String](../../../system/string/) | O nome local do elemento. |
| namespaceURI | [String](../../../system/string/) | O URI do namespace do elemento. |

### Valor de Retorno

O conteúdo do elemento convertido para o objeto tipado solicitado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)