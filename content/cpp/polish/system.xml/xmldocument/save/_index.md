---
title: Save()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Zapisuje dokument XML do określonego pliku. Jeśli podany plik istnieje, metoda nadpisuje go.
type: docs
weight: 534
url: /pl/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metoda

Zapisuje dokument XML do określonego pliku. Jeśli określony plik istnieje, ta metoda nadpisuje go.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Lokalizacja pliku, w którym chcesz zapisać dokument. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metoda

Zapisuje dokument XML do określonego strumienia.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień, do którego chcesz zapisać. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metoda

Zapisuje dokument XML do określonego TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter, do którego chcesz zapisać. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metoda

Zapisuje dokument XML do określonego [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/) do którego chcesz zapisać. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [TextWriter](../../../system.io/textwriter/)
* Klasa [XmlWriter](../../xmlwriter/)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)