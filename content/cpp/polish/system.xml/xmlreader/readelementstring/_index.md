---
title: ReadElementString()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: "Odczytuje element zawierający wyłącznie tekst. Jednak zaleca się użycie metody XmlReader::ReadElementContentAsString, ponieważ zapewnia ona prostszy sposób obsługi tej operacji."
type: docs
weight: 859
url: /pl/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() metoda

Odczytuje element zawierający tylko tekst. Jednak zaleca się użycie metody [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Wartość zwracana

Tekst zawarty w odczytanym elemencie. Pusty ciąg znaków, jeśli element jest pusty.

## XmlReader::ReadElementString(String) metoda

Sprawdza, czy wartość [XmlReader::get_Name](../get_name/) znalezionego elementu pasuje do podanego ciągu znaków przed odczytaniem elementu zawierającego tylko tekst. Jednak zaleca się użycie metody [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nazwa do sprawdzenia. |

### Wartość zwracana

Tekst zawarty w odczytanym elemencie. Pusty ciąg znaków, jeśli element jest pusty.

## XmlReader::ReadElementString(String, String) metoda

Sprawdza, czy wartości [XmlReader::get_LocalName](../get_localname/) i [XmlReader::get_NamespaceURI](../get_namespaceuri/) znalezionego elementu pasują do podanych ciągów znaków przed odczytaniem elementu zawierającego tylko tekst. Jednak zaleca się użycie metody [XmlReader::ReadElementContentAsString](../readelementcontentasstring/), ponieważ zapewnia ona prostszy sposób obsługi tej operacji.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Lokalna nazwa do sprawdzenia. |
| ns | [String](../../../system/string/) | Adres URI przestrzeni nazw do sprawdzenia. |

### Wartość zwracana

Tekst zawarty w odczytanym elemencie. Pusty ciąg znaków, jeśli element jest pusty.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlReader](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)