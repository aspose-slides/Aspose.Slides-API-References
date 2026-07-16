---
title: Load()
second_title: Référence de l'API Aspose.Slides pour C++
description: Charge le document XML à partir de l'URL spécifiée.
type: docs
weight: 508
url: /fr/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) méthode

Charge le document XML à partir de l’URL spécifiée.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL du fichier contenant le document XML à charger. L'URL peut être soit un fichier local, soit une URL HTTP (une adresse [Web](../../../system.web/)). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) méthode

Charge le document XML à partir du flux spécifié.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux contenant le document XML à charger. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) méthode

Charge le document XML à partir du TextReader spécifié.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Le TextReader utilisé pour alimenter le document avec les données XML. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) méthode

Charge le document XML à partir du [XmlReader](../../xmlreader/) spécifié.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Le [XmlReader](../../xmlreader/) utilisé pour alimenter le document avec les données XML. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Class [Stream](../../../system.io/stream/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlReader](../../xmlreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)