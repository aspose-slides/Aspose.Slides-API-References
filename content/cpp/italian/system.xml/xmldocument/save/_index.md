---
title: Save()
second_title: Riferimento API di Aspose.Slides per C++
description: Salva il documento XML nel file specificato. Se il file specificato esiste, questo metodo lo sovrascrive.
type: docs
weight: 534
url: /it/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metodo

Salva il documento XML nel file specificato. Se il file specificato esiste, questo metodo lo sovrascrive.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Il percorso del file dove si desidera salvare il documento. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metodo

Salva il documento XML nello stream specificato.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Lo stream su cui si desidera salvare. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metodo

Salva il documento XML nel TextWriter specificato.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Il TextWriter su cui si desidera salvare. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metodo

Salva il documento XML nel [XmlWriter](../../xmlwriter/) specificato.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Il [XmlWriter](../../xmlwriter/) su cui si desidera salvare. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)