---
title: ValueAs()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore dell'elemento come il tipo specificato.
type: docs
weight: 131
url: /it/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metodo

Restituisce il valore dell'elemento come il tipo specificato.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo con cui restituire il valore dell'elemento. |

### Valore di ritorno

Il valore dell'elemento come il tipo richiesto.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metodo

Quando sovrascritto in una classe derivata, restituisce il valore dell'elemento come il tipo specificato utilizzando l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) specificato per risolvere i prefissi degli spazi dei nomi.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo con cui restituire il valore dell'elemento. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi degli spazi dei nomi. |

### Valore di ritorno

Il valore dell'elemento come il tipo richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XPathItem](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)