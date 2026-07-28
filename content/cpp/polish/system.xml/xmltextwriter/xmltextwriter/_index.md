---
title: XmlTextWriter()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy instancję klasy XmlTextWriter przy użyciu określonego strumienia i kodowania.
type: docs
weight: 183
url: /pl/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Tworzy instancję klasy [XmlTextWriter](../) przy użyciu określonego strumienia i kodowania.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Strumień, do którego chcesz zapisywać. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do wygenerowania. Jeśli kodowanie jest **nullptr**, zapisuje strumień jako UTF-8 i pomija atrybut kodowania w **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) konstruktor


Tworzy instancję klasy [XmlTextWriter](../) używając określonego pliku.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nazwa pliku, do którego ma być zapisane. Jeśli plik istnieje, zostaje przycięty i nadpisany nową zawartością. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Kodowanie do wygenerowania. Jeśli kodowanie jest **nullptr**, zapisuje plik jako UTF-8 i pomija atrybut kodowania w **ProcessingInstruction**. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) konstruktor


Tworzy instancję klasy [XmlTextWriter](../) przy użyciu określonego TextWriter.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | TextWriter, do którego ma być zapisane. Zakłada się, że TextWriter jest już ustawiony na właściwe kodowanie. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [Encoding](../../../system.text/encoding/)
* Klasa [XmlTextWriter](../)
* Klasa [String](../../../system/string/)
* Klasa [TextWriter](../../../system.io/textwriter/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)