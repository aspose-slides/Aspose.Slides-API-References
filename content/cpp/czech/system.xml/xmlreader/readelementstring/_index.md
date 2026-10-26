---
title: ReadElementString()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Čte textový prvek. Nicméně se doporučuje použít metodu XmlReader::ReadElementContentAsString místo toho, protože poskytuje přímější způsob, jak tuto operaci provést."
type: docs
weight: 859
url: /cs/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() method

Čte textový prvek. Nicméně se doporučuje použít metodu [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) místo toho, protože poskytuje přímější způsob, jak tuto operaci provést.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Návratová hodnota

Text obsažený v přečteném elementu. Prázdný řetězec, pokud je element prázdný.

## XmlReader::ReadElementString(String) method

Ověřuje, že hodnota [XmlReader::get_Name](../get_name/) nalezeného elementu odpovídá zadanému řetězci před čtením textového prvku. Nicméně se doporučuje použít metodu [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) místo toho, protože poskytuje přímější způsob, jak tuto operaci provést.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Název, který se má zkontrolovat. |

### Návratová hodnota

Text obsažený v přečteném elementu. Prázdný řetězec, pokud je element prázdný.

## XmlReader::ReadElementString(String, String) method

Ověřuje, že hodnoty [XmlReader::get_LocalName](../get_localname/) a [XmlReader::get_NamespaceURI](../get_namespaceuri/) nalezeného elementu odpovídají zadaným řetězcům před čtením textového prvku. Nicméně se doporučuje použít metodu [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) místo toho, protože poskytuje přímější způsob, jak tuto operaci provést.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Místní název, který se má zkontrolovat. |
| ns | [String](../../../system/string/) | URI prostoru názvů, který se má zkontrolovat. |

### Návratová hodnota

Text obsažený v přečteném elementu. Prázdný řetězec, pokud je element prázdný.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)