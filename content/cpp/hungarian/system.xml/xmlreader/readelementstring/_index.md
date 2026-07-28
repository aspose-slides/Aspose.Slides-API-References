---
title: ReadElementString()
second_title: Aspose.Slides for C++ API Hivatkozás
description: "Csak szöveget tartalmazó elemet olvas. Azonban ajánlott a XmlReader::ReadElementContentAsString metódust használni helyette, mivel ez egy egyszerűbb módot biztosít az ilyen művelet kezelésére."
type: docs
weight: 859
url: /hu/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() metódus

Csak szöveget tartalmazó elemet olvas. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metódust használni helyette, mivel ez egy egyszerűbb módot biztosít az ilyen művelet kezelésére.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Visszatérési érték

Az olvasott elemben található szöveg. Üres karakterlánc, ha az elem üres.

## XmlReader::ReadElementString(String) metódus

Ellenőrzi, hogy a megtalált elem [XmlReader::get_Name](../get_name/) értéke megegyezik-e a megadott karakterlánccal, mielőtt csak szöveget tartalmazó elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metódust használni helyette, mivel ez egy egyszerűbb módot biztosít az ilyen művelet kezelésére.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A vizsgálandó név. |

### Visszatérési érték

Az olvasott elemben található szöveg. Üres karakterlánc, ha az elem üres.

## XmlReader::ReadElementString(String, String) metódus

Ellenőrzi, hogy a megtalált elem [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal, mielőtt csak szöveget tartalmazó elemet olvasna. Azonban ajánlott a [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) metódust használni helyette, mivel ez egy egyszerűbb módot biztosít az ilyen művelet kezelésére.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localname | [String](../../../system/string/) | A vizsgálandó helyi név. |
| ns | [String](../../../system/string/) | A vizsgálandó névtér URI. |

### Visszatérési érték

Az olvasott elemben található szöveg. Üres karakterlánc, ha az elem üres.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)