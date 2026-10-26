---
title: Load()
second_title: Aspose.Slides pro C++ – reference API
description: Načte XML dokument ze zadané adresy URL.
type: docs
weight: 508
url: /cs/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metoda


Načte XML dokument ze zadané adresy URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Adresa URL souboru obsahujícího XML dokument k načtení. Adresa URL může být buď místní soubor, nebo HTTP adresa ([Web](../../../system.web/) adresa). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metoda


Načte XML dokument ze zadaného proudu.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud obsahující XML dokument k načtení. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metoda


Načte XML dokument ze zadaného TextReaderu.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | TextReader použitý k vložení XML dat do dokumentu. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metoda


Načte XML dokument ze zadaného [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/) použité k vložení XML dat do dokumentu. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Třída [Stream](../../../system.io/stream/)
* Třída [TextReader](../../../system.io/textreader/)
* Třída [XmlReader](../../xmlreader/)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)