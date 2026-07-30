---
title: CreateXmlDeclaration()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytvoří uzel XmlDeclaration s uvedenými hodnotami.
type: docs
weight: 378
url: /cs/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) metoda

Vytvoří uzel [XmlDeclaration](../../xmldeclaration/) s určenými hodnotami.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Verze musí být "1.0". |
| encoding | const [String](../../../system/string/)\& | Hodnota atributu encoding. Jedná se o kódování, které se používá při ukládání [XmlDocument](../) do souboru nebo proudu; proto musí být nastaveno na řetězec podporovaný třídou [Text::Encoding](../../../system.text/encoding/), jinak selže "XmlDocument::Save(String)". Pokud je toto **nullptr** nebo [String::Empty](../../../system/string/empty/), metoda [XmlDocument::Save](../save/) nezapíše atribut encoding do XML deklarace a proto se použije výchozí kódování UTF-8. |
| standalone | const [String](../../../system/string/)\& | Hodnota musí být buď "yes" nebo "no". Pokud je toto **nullptr** nebo [String::Empty](../../../system/string/empty/), metoda [XmlDocument::Save](../save/) nezapíše atribut standalone do XML deklarace. |

### Návratová hodnota

Nový uzel [XmlDeclaration](../../xmldeclaration/).

## Poznámky

Poznámka: Pokud je [XmlDocument](../) uložen buď do TextWriteru, nebo do [XmlTextWriter](../../xmltextwriter/), tato hodnota kódování je zahozena. Místo toho se použije kódování TextWriteru nebo [XmlTextWriter](../../xmltextwriter/). To zajišťuje, že vypsané XML lze načíst zpět pomocí správného kódování.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlDeclaration](../../xmldeclaration/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)