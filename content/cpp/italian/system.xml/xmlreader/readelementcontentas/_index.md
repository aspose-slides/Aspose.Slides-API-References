---
title: ReadElementContentAs()
second_title: Aspose.Slides for C++ Riferimento API
description: Legge il contenuto dell'elemento come il tipo richiesto.
type: docs
weight: 586
url: /it/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodo

Legge il contenuto dell'elemento come il tipo richiesto.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo del valore da restituire. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un oggetto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) usato per risolvere eventuali prefissi di namespace relativi alla conversione di tipo. |

### Valore di ritorno

Il contenuto dell'elemento convertito nell'oggetto tipizzato richiesto.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metodo

Verifica che il nome locale e l'URI del namespace specificati corrispondano a quelli dell'elemento corrente, quindi legge il contenuto dell'elemento come il tipo richiesto.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo del valore da restituire. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un oggetto [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) usato per risolvere eventuali prefissi di namespace relativi alla conversione di tipo. |
| localName | [String](../../../system/string/) | Il nome locale dell'elemento. |
| namespaceURI | [String](../../../system/string/) | L'URI del namespace dell'elemento. |

### Valore di ritorno

Il contenuto dell'elemento convertito nell'oggetto tipizzato richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Class [XmlReader](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)