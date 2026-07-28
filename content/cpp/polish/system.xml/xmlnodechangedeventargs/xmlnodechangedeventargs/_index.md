---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Inicjalizuje nową instancję klasy XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /pl/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) konstruktor

Inicjalizuje nową instancję klasy [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/), który wygenerował zdarzenie. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Stary rodzic [XmlNode](../../xmlnode/) elementu [XmlNode](../../xmlnode/), który wygenerował zdarzenie. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Nowy rodzic [XmlNode](../../xmlnode/) elementu [XmlNode](../../xmlnode/), który wygenerował zdarzenie. |
| oldValue | const [String](../../../system/string/)\& | Stara wartość [XmlNode](../../xmlnode/), który wygenerował zdarzenie. |
| newValue | const [String](../../../system/string/)\& | Nowa wartość [XmlNode](../../xmlnode/), który wygenerował zdarzenie. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Akcja XmlNodeChangedAction. |

## Zobacz także

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [String](../../../system/string/)
* Klasa [XmlNodeChangedEventArgs](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)