---
title: GetAttribute()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca wartość atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.
type: docs
weight: 482
url: /pl/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) metoda


Zwraca wartość atrybutu o określonej nazwie lokalnej i identyfikatorze URI przestrzeni nazw.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa atrybutu. **localName** jest wrażliwa na wielkość liter. |
| namespaceURI | [String](../../../system/string/) | URI przestrzeni nazw atrybutu. |

### Wartość zwracana

Obiekt [String](../../../system/string/) zawierający wartość określonego atrybutu; [String::Empty](../../../system/string/empty/) jeśli nie znaleziono pasującego atrybutu lub jeśli [XPathNavigator](../) nie jest ustawiony na węzeł elementu.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XPathNavigator](../)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)