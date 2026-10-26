---
title: ReadElementContentAsObject()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Odczytuje bieżący element i zwraca jego zawartość jako obiekt.
type: docs
weight: 469
url: /pl/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metoda

Odczytuje bieżący element i zwraca zawartość jako [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Wartość zwracana

Obiekt opakowany najbardziej odpowiedniego typu. Wartość [XmlReader::get_ValueType](../get_valuetype/) określa odpowiedni typ. Jeśli zawartość jest typowana jako typ listy, metoda zwraca tablicę opakowanych obiektów odpowiedniego typu.

## XmlReader::ReadElementContentAsObject(String, String) metoda

Sprawdza, czy określona nazwa lokalna i identyfikator URI przestrzeni nazw pasują do bieżącego elementu, a następnie odczytuje bieżący element i zwraca zawartość jako [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokalna nazwa elementu. |
| namespaceURI | [String](../../../system/string/) | Identyfikator URI przestrzeni nazw elementu. |

### Wartość zwracana

Obiekt opakowany najbardziej odpowiedniego typu. Wartość [XmlReader::get_ValueType](../get_valuetype/) określa odpowiedni typ. Jeśli zawartość jest typowana jako typ listy, metoda zwraca tablicę opakowanych obiektów odpowiedniego typu.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [XmlReader](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)