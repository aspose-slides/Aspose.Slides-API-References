---
title: CreateXmlDeclaration()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy węzeł XmlDeclaration z określonymi wartościami.
type: docs
weight: 378
url: /pl/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) metoda


Tworzy węzeł [XmlDeclaration](../../xmldeclaration/) z określonymi wartościami.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Wersja musi być "1.0". |
| encoding | const [String](../../../system/string/)\& | Wartość atrybutu encoding. Jest to kodowanie używane, gdy zapisujesz [XmlDocument](../) do pliku lub strumienia; dlatego musi być ustawione na ciąg znaków obsługiwany przez klasę [Text::Encoding](../../../system.text/encoding/), w przeciwnym razie "XmlDocument::Save(String)" nie powiedzie się. Jeśli jest to **nullptr** lub [String::Empty](../../../system/string/empty/), metoda [XmlDocument::Save](../save/) nie zapisuje atrybutu encoding w deklaracji XML i w związku z tym używane jest domyślne kodowanie, UTF-8. |
| standalone | const [String](../../../system/string/)\& | Wartość musi być "yes" lub "no". Jeśli jest to **nullptr** lub [String::Empty](../../../system/string/empty/), metoda [XmlDocument::Save](../save/) nie zapisuje atrybutu standalone w deklaracji XML. |

### Wartość zwracana

Nowy węzeł [XmlDeclaration](../../xmldeclaration/).

## Uwagi



Uwaga: Jeśli [XmlDocument](../) jest zapisywany do TextWriter lub [XmlTextWriter](../../xmltextwriter/), wartość tego kodowania jest pomijana. Zamiast tego używane jest kodowanie TextWritera lub [XmlTextWriter](../../xmltextwriter/). Zapewnia to, że zapisane XML może być odczytane przy użyciu właściwego kodowania.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlDeclaration](../../xmldeclaration/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)