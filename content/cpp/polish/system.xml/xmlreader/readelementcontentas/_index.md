---
title: ReadElementContentAs()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Odczytuje zawartość elementu jako żądany typ.
type: docs
weight: 586
url: /pl/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) metoda


Odczytuje zawartość elementu jako żądany typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ wartości, która ma zostać zwrócona. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), który służy do rozwiązywania dowolnych prefiksów przestrzeni nazw związanych z konwersją typów. |

### Wartość zwracana

Zawartość elementu przekonwertowana na żądany typowany obiekt.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) metoda


Sprawdza, czy podana lokalna nazwa i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje zawartość elementu jako żądany typ.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Typ wartości, która ma zostać zwrócona. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../ixmlnamespaceresolver/), który służy do rozwiązywania dowolnych prefiksów przestrzeni nazw związanych z konwersją typów. |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu. |
| namespaceURI | [String](../../../system/string/) | Identifikator URI przestrzeni nazw elementu. |

### Wartość zwracana

Zawartość elementu przekonwertowana na żądany typowany obiekt.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasa [XmlReader](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)