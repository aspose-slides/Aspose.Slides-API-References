---
title: Save()
second_title: Référence de l'API Aspose.Slides pour C++
description: Enregistre le document XML dans le fichier spécifié. Si le fichier spécifié existe, cette méthode le remplace.
type: docs
weight: 534
url: /fr/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) méthode

Enregistre le document XML dans le fichier spécifié. Si le fichier spécifié existe, cette méthode le remplace.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | L'emplacement du fichier où vous souhaitez enregistrer le document. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) méthode

Enregistre le document XML dans le flux spécifié.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux dans lequel vous souhaitez enregistrer. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) méthode

Enregistre le document XML dans le TextWriter spécifié.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Le TextWriter dans lequel vous souhaitez enregistrer. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) méthode

Enregistre le document XML dans le [XmlWriter](../../xmlwriter/) spécifié.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Le [XmlWriter](../../xmlwriter/) dans lequel vous souhaitez enregistrer. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [XmlWriter](../../xmlwriter/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)