---
title: Load()
second_title: Riferimento API di Aspose.Slides per C++
description: Carica il documento XML dall'URL specificato.
type: docs
weight: 508
url: /it/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) metodo

Carica il documento XML dall'URL specificato.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL del file contenente il documento XML da caricare. L'URL può essere sia un file locale sia un URL HTTP (un indirizzo [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) metodo

Carica il documento XML dallo stream specificato.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Lo stream contenente il documento XML da caricare. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) metodo

Carica il documento XML dal TextReader specificato.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Il TextReader usato per alimentare i dati XML nel documento. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) metodo

Carica il documento XML dal [XmlReader](../../xmlreader/) specificato.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Il [XmlReader](../../xmlreader/) usato per alimentare i dati XML nel documento. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextReader](../../../system.io/textreader/)
* Classe [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)