---
title: ReadContentAs()
second_title: Referência da API Aspose.Slides for C++
description: Lê o conteúdo como um objeto do tipo especificado.
type: docs
weight: 456
url: /pt/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Lê o conteúdo como um objeto do tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | O tipo do valor a ser retornado. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Um objeto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) que é usado para resolver quaisquer prefixos de namespace relacionados à conversão de tipo. Por exemplo, isso pode ser usado ao converter um objeto [XmlQualifiedName](../../xmlqualifiedname/) para um **xs:string**. Este valor pode ser **nullptr**. |

### Valor de Retorno

O conteúdo de texto concatenado ou o valor do atributo convertido para o tipo solicitado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)