---
title: IsStartElement()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Wywołuje XmlReader::MoveToContent i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu."
type: docs
weight: 885
url: /pl/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() metoda

Wywołuje [XmlReader::MoveToContent](../movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Wartość zwracana

**true** jeśli [XmlReader::MoveToContent](../movetocontent/) znajdzie tag początkowy lub pusty tag elementu; **false** jeśli znaleziono typ węzła inny niż [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) metoda

Wywołuje [XmlReader::MoveToContent](../movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu oraz czy wartość [XmlReader::get_Name](../get_name/) znalezionego elementu pasuje do podanego argumentu.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Ciąg znaków dopasowany do wartości **Name** znalezionego elementu. |

### Wartość zwracana

**true** jeśli wynikowy węzeł jest elementem i wartość **Name** pasuje do określonego ciągu. **false** jeśli znaleziono typ węzła inny niż [XmlNodeType::Element](../../xmlnodetype/) lub jeśli wartość **Name** elementu nie pasuje do określonego ciągu.

## XmlReader::IsStartElement(String, String) metoda

Wywołuje [XmlReader::MoveToContent](../movetocontent/) i sprawdza, czy bieżący węzeł zawartości jest tagiem początkowym lub pustym tagiem elementu oraz czy wartości [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/) znalezionego elementu pasują do podanych ciągów.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Ciąg znaków do dopasowania z wartością **LocalName** znalezionego elementu. |
| ns | [String](../../../system/string/) | Ciąg znaków do dopasowania z wartością **NamespaceURI** znalezionego elementu. |

### Wartość zwracana

**true** jeśli wynikowy węzeł jest elementem. **false** jeśli znaleziono typ węzła inny niż [XmlNodeType::Element](../../xmlnodetype/) lub jeśli wartości **LocalName** i **NamespaceURI** elementu nie pasują do określonych ciągów.

## Zobacz także

* Klasa [XmlReader](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)