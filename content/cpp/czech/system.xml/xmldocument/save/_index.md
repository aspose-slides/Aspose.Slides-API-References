---
title: Save()
second_title: Aspose.Slides pro C++ API Reference
description: Ukládá XML dokument do zadaného souboru. Pokud zadaný soubor existuje, tato metoda jej přepíše.
type: docs
weight: 534
url: /cs/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metoda

Ukládá XML dokument do zadaného souboru. Pokud zadaný soubor existuje, tato metoda jej přepíše.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Umístění souboru, kde chcete dokument uložit. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metoda

Ukládá XML dokument do zadaného proudu.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Průtok, do kterého chcete uložit. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metoda

Ukládá XML dokument do zadaného TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | TextWriter, do kterého chcete uložit. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metoda

Ukládá XML dokument do zadaného [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | [XmlWriter](../../xmlwriter/), do kterého chcete uložit. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [XmlDocument](../)
* Třída [Stream](../../../system.io/stream/)
* Třída [TextWriter](../../../system.io/textwriter/)
* Třída [XmlWriter](../../xmlwriter/)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)