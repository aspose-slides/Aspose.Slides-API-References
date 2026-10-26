---
title: XmlTextWriter()
second_title: Aspose.Slides pro C++ – API Reference
description: Vytvoří instanci třídy XmlTextWriter pomocí zadaného proudu a kódování.
type: docs
weight: 183
url: /cs/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) constructor

Vytvoří instanci třídy [XmlTextWriter](../) pomocí zadaného proudu a kódování.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, do kterého chcete zapisovat. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování, které se má generovat. Pokud je kódování **nullptr**, zapíše se proud jako UTF-8 a atribut kódování se vynechá v **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) constructor

Vytvoří instanci třídy [XmlTextWriter](../) pomocí zadaného souboru.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Název souboru, do kterého se zapisuje. Pokud soubor existuje, zkrátí jej a přepíše novým obsahem. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kódování, které se má generovat. Pokud je kódování **nullptr**, zapíše se soubor jako UTF-8 a atribut kódování se vynechá v **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) constructor

Vytvoří instanci třídy [XmlTextWriter](../) pomocí zadaného TextWriteru.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do kterého se zapisuje. Předpokládá se, že TextWriter již má nastaveno správné kódování. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../../system.io/stream/)
* Třída [Encoding](../../../system.text/encoding/)
* Třída [XmlTextWriter](../)
* Třída [String](../../../system/string/)
* Třída [TextWriter](../../../system.io/textwriter/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)