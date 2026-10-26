---
title: WriteStartElement()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Zapisuje określony znacznik początkowy i wiąże go z podaną przestrzenią nazw oraz prefiksem.
type: docs
weight: 235
url: /pl/system.xml/xmltextwriter/writestartelement/
---
## XmlTextWriter::WriteStartElement(const String\&, const String\&, const String\&) metoda

Zapisuje określony znacznik początkowy i wiąże go z podaną przestrzenią nazw oraz prefiksem.

```cpp
void System::Xml::XmlTextWriter::WriteStartElement(const String &prefix, const String &localName, const String &ns) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Prefiks przestrzeni nazw elementu. |
| localName | const [String](../../../system/string/)\& | Lokalna nazwa elementu. |
| ns | const [String](../../../system/string/)\& | Adres URI przestrzeni nazw do powiązania z elementem. Jeśli ta przestrzeń nazw jest już w zasięgu i ma powiązany prefiks, to pisarz automatycznie zapisuje również ten prefiks. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlTextWriter](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)