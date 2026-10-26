---
title: get_Encoding()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Kodierungsebene des XML-Dokuments zurück.
type: docs
weight: 14
url: /de/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() Methode

Gibt die Kodierungsebene des XML-Dokuments zurück.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Rückgabewert

Der gültige Name der Zeichenkodierung.

## Bemerkungen

Die am häufigsten unterstützten Zeichenkodierungsnamen für XML sind die folgenden:

| Kategorie | Kodierungsnamen |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Dieser Wert ist optional. Wenn kein Wert gesetzt ist, gibt diese Methode [String::Empty](../../../system/string/empty/) zurück. Wenn kein Kodierungsattribut enthalten ist, wird beim Schreiben oder Speichern des Dokuments die UTF-8-Kodierung angenommen.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlDeclaration](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)