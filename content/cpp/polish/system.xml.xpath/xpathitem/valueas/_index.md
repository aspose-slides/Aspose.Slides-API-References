---
title: ValueAs()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca wartość elementu jako określony typ.
type: docs
weight: 131
url: /pl/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) metoda


Zwraca wartość elementu jako określony typ.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, w którym zwrócić wartość elementu. |

### Wartość zwracana

Wartość elementu w żądanym typie.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda


Gdy zostanie przesłonięta w klasie pochodnej, zwraca wartość elementu jako typ określony przy użyciu obiektu [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) służącego do rozwiązywania prefiksów przestrzeni nazw.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ, w którym zwrócić wartość elementu. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania prefiksów przestrzeni nazw. |

### Wartość zwracana

Wartość elementu w żądanym typie.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [XPathItem](../)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)