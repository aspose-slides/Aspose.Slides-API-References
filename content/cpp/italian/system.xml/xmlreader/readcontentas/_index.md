---
title: ReadContentAs()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto come un oggetto del tipo specificato.
type: docs
weight: 456
url: /it/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Legge il contenuto come un oggetto del tipo specificato.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo del valore da restituire. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un oggetto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) che viene usato per risolvere eventuali prefissi di spazio dei nomi relativi alla conversione di tipo. Per esempio, questo può essere usato quando si converte un oggetto [XmlQualifiedName](../../xmlqualifiedname/) in un **xs:string**. Questo valore può essere **nullptr**. |

### Valore restituito

Il contenuto testuale concatenato o il valore dell'attributo convertito nel tipo richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)