---
title: ReadElementContentAsObject()
second_title: Aspose.Slides pro C++ API Reference
description: Načte aktuální prvek a vrátí jeho obsah jako objekt.
type: docs
weight: 469
url: /cs/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metoda

Načte aktuální prvek a vrátí obsah jako [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```

### Návratová hodnota

Objekt zabalený do schránky nejvhodnějšího typu. Hodnota [XmlReader::get_ValueType](../get_valuetype/) určuje vhodný typ. Pokud je obsah typu seznamu, tato metoda vrátí pole zabalených objektů vhodného typu.

## XmlReader::ReadElementContentAsObject(String, String) metoda

Zkontroluje, že zadaný místní název a URI jmenného prostoru odpovídá aktuálnímu prvku, poté načte aktuální prvek a vrátí jeho obsah jako [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Místní název prvku. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru prvku. |

### Návratová hodnota

Objekt zabalený do schránky nejvhodnějšího typu. Hodnota [XmlReader::get_ValueType](../get_valuetype/) určuje vhodný typ. Pokud je obsah typu seznamu, tato metoda vrátí pole zabalených objektů vhodného typu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [XmlReader](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)