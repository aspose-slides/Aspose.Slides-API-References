---
title: CreateXmlDeclaration()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen XmlDeclaration-Knoten mit den angegebenen Werten.
type: docs
weight: 378
url: /de/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) Methode

Erstellt einen [XmlDeclaration](../../xmldeclaration/)-Knoten mit den angegebenen Werten.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Die Version muss \"1.0\" sein. |
| encoding | const [String](../../../system/string/)\& | Der Wert des encoding-Attributs. Dies ist das Encoding, das verwendet wird, wenn Sie das [XmlDocument](../) in einer Datei oder einem Stream speichern; daher muss es auf eine von der [Text::Encoding](../../../system.text/encoding/)-Klasse unterstützte Zeichenkette gesetzt werden, andernfalls schlägt \"XmlDocument::Save(String)\" fehl. Wenn dies **nullptr** oder [String::Empty](../../../system/string/empty/) ist, schreibt die [XmlDocument::Save](../save/)-Methode kein encoding-Attribut in die XML-Deklaration und daher wird das Standard-Encoding UTF-8 verwendet. |
| standalone | const [String](../../../system/string/)\& | Der Wert muss entweder \"yes\" oder \"no\" sein. Wenn dies **nullptr** oder [String::Empty](../../../system/string/empty/) ist, schreibt die [XmlDocument::Save](../save/)-Methode kein standalone-Attribut in die XML-Deklaration. |

### Rückgabewert

Der neue [XmlDeclaration](../../xmldeclaration/)-Knoten.

## Bemerkungen

Hinweis: Wenn das [XmlDocument](../) entweder in einen TextWriter oder ein [XmlTextWriter](../../xmltextwriter/) gespeichert wird, wird dieser Encoding-Wert verworfen. Stattdessen wird das Encoding des TextWriter oder des [XmlTextWriter](../../xmltextwriter/) verwendet. Dies stellt sicher, dass das ausgegebene XML mit dem korrekten Encoding wieder eingelesen werden kann.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlDeclaration](../../xmldeclaration/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)