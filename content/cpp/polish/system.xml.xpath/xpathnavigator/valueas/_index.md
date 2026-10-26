---
title: ValueAs()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca wartość bieżącego węzła jako określony Type, przy użyciu obiektu IXmlNamespaceResolver służącego do rozwiązywania prefiksów przestrzeni nazw.
type: docs
weight: 378
url: /pl/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Zwraca wartość bieżącego węzła jako określony Type, przy użyciu obiektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) służącego do rozwiązywania prefiksów przestrzeni nazw.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Type, którego wartość ma zostać zwrócona jako wartość bieżącego węzła. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw. |

### Wartość zwracana

Wartość bieżącego węzła jako żądany Type.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)