---
title: ReadStartElement()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła.
type: docs
weight: 846
url: /pl/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metoda

Sprawdza, czy bieżący węzeł jest elementem i przesuwa czytnik do następnego węzła.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) metoda

Sprawdza, czy bieżący węzeł zawartości jest elementem o podanej wartości [XmlReader::get_Name](../get_name/) i przesuwa czytnik do następnego węzła.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | W pełni kwalifikowana nazwa elementu. |

## XmlReader::ReadStartElement(String, String) metoda

Sprawdza, czy bieżący węzeł zawartości jest elementem o podanych wartościach [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/) i przesuwa czytnik do następnego węzła.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Lokalna nazwa elementu. |
| ns | [String](../../../system/string/) | URI przestrzeni nazw elementu. |

## Zobacz także

* Klasa [XmlReader](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)