---
title: ReadStartElement()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, že aktuální uzel je element a posouvá čtečku na další uzel.
type: docs
weight: 846
url: /cs/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() metoda

Kontroluje, že aktuální uzel je element a posouvá čtečku na další uzel.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) metoda

Kontroluje, že aktuální obsahový uzel je element s danou hodnotou [XmlReader::get_Name](../get_name/) a posouvá čtečku na další uzel.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název elementu. |

## XmlReader::ReadStartElement(String, String) metoda

Kontroluje, že aktuální obsahový uzel je element s danými hodnotami [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/) a posouvá čtečku na další uzel.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Lokální název elementu. |
| ns | [String](../../../system/string/) | URI jmenného prostoru elementu. |

## Viz také

* Třída [XmlReader](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)