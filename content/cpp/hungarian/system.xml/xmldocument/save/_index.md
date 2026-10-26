---
title: Save()
second_title: Aspose.Slides C++ API-referencia
description: Elmenti az XML dokumentumot a megadott fájlba. Ha a megadott fájl létezik, ez a metódus felülírja.
type: docs
weight: 534
url: /hu/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metódus

Elmenti az XML dokumentumot a megadott fájlba. Ha a megadott fájl létezik, ez a metódus felülírja.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | [String](../../../system/string/) | A fájl helye, ahová el szeretné menteni a dokumentumot. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metódus

Elmenti az XML dokumentumot a megadott adatfolyamra.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amelybe el szeretné menteni. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metódus

Elmenti az XML dokumentumot a megadott TextWriter-be.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | A TextWriter, amelybe el szeretné menteni. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metódus

Elmenti az XML dokumentumot a megadott [XmlWriter](../../xmlwriter/)-ba.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | A [XmlWriter](../../xmlwriter/), amelybe el szeretné menteni. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [TextWriter](../../../system.io/textwriter/)
* Osztály [XmlWriter](../../xmlwriter/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)