---
title: ValueAs()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce il valore del nodo corrente come il Tipo specificato, utilizzando l'oggetto IXmlNamespaceResolver specificato per risolvere i prefissi degli spazi dei nomi.
type: docs
weight: 378
url: /it/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodo

Restituisce il valore del nodo corrente come il Tipo specificato, utilizzando l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi degli spazi dei nomi.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il Type per restituire il valore del nodo corrente. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi dei namespace. |

### Valore di ritorno

Il valore del nodo corrente come il Tipo richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)