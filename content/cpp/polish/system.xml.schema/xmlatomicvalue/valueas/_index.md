---
title: ValueAs()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zwraca zweryfikowaną wartość elementu XML lub atrybutu jako określony typ przy użyciu obiektu IXmlNamespaceResolver służącego do rozwiązywania prefiksów przestrzeni nazw.
type: docs
weight: 144
url: /pl/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda


Zwraca zweryfikowaną wartość elementu XML lub atrybutu jako typ określony przy użyciu obiektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) przeznaczonego do rozwiązywania prefiksów przestrzeni nazw.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Typ, w którym zwrócić zweryfikowaną wartość elementu XML lub atrybutu. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw. |

### Wartość zwracana

Wartość zweryfikowanego elementu XML lub atrybutu jako żądany typ.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XmlAtomicValue](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)