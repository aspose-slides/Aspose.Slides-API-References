---
title: Load()
second_title: Aspose.Slides C++ API hivatkozás
description: Betölti az XML dokumentumot a megadott URL-ről.
type: docs
weight: 508
url: /hu/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metódus


Betölti az XML dokumentumot a megadott URL-ről.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| filename | [String](../../../system/string/) | A betöltendő XML dokumentumot tartalmazó fájl URL-je. Az URL lehet helyi fájl vagy HTTP URL (egy [Web](../../../system.web/) cím). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metódus


Betölti az XML dokumentumot a megadott adatfolyamból.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az XML dokumentumot tartalmazó adatfolyam, amely betöltésre kerül. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metódus


Betölti az XML dokumentumot a megadott TextReader-ből.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | A TextReader, amely az XML adatokat a dokumentumba továbbítja. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metódus


Betölti az XML dokumentumot a megadott [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | A [XmlReader](../../xmlreader/) amely az XML adatokat a dokumentumba továbbítja. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [TextReader](../../../system.io/textreader/)
* Osztály [XmlReader](../../xmlreader/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)