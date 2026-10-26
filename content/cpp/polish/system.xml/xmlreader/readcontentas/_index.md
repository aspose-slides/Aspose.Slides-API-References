---
title: ReadContentAs()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Odczytuje zawartość jako obiekt określonego typu.
type: docs
weight: 456
url: /pl/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda

Odczytuje zawartość jako obiekt określonego typu.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ zwracanej wartości. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) używany do rozwiązywania dowolnych prefiksów przestrzeni nazw związanych z konwersją typów. Na przykład może być użyty przy konwertowaniu obiektu [XmlQualifiedName](../../xmlqualifiedname/) na **xs:string**. Ta wartość może być **nullptr**. |

### Wartość zwracana

Połączona zawartość tekstowa lub wartość atrybutu przekształcona na żądany typ.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)