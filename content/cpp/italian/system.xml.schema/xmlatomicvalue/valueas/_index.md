---
title: ValueAs()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore dell'elemento o attributo XML convalidato come il tipo specificato utilizzando l'oggetto IXmlNamespaceResolver indicato per risolvere i prefissi dello spazio dei nomi.
type: docs
weight: 144
url: /it/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Restituisce il valore dell'elemento o attributo XML convalidato come il tipo specificato utilizzando l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) indicato per risolvere i prefissi dello spazio dei nomi.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Il tipo come cui restituire il valore dell'elemento o attributo XML convalidato. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usato per risolvere i prefissi dello spazio dei nomi. |

### Valore restituito

Il valore dell'elemento o attributo XML convalidato come il tipo richiesto.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlAtomicValue](../)
* Spazio dei nomi [System::Xml::Schema](../../)
* Libreria [Aspose.Slides](../../../)