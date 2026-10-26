---
title: Load()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Ładuje dokument XML z określonego adresu URL.
type: docs
weight: 508
url: /pl/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metoda

Ładuje dokument XML z określonego adresu URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Adres URL pliku zawierającego dokument XML do załadowania. Adres URL może być zarówno plikiem lokalnym, jak i adresem HTTP (adres [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metoda

Ładuje dokument XML z określonego strumienia.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień zawierający dokument XML do załadowania. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metoda

Ładuje dokument XML z określonego TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader używany do wprowadzania danych XML do dokumentu. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metoda

Ładuje dokument XML z określonego [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) używany do wprowadzania danych XML do dokumentu. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)