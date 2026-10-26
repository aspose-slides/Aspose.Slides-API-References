---
title: Load()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URL'den XML belgesini yükler.
type: docs
weight: 508
url: /tr/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) yöntemi

Belirtilen URL'den XML belgesini yükler.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Yüklemek için XML belgesini içeren dosyanın URL'si. URL hem yerel bir dosya hem de bir HTTP URL'si (bir [Web](../../../system.web/) adresi) olabilir. |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) yöntemi

Belirtilen akıştan XML belgesini yükler.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Yüklemek için XML belgesini içeren akış. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) yöntemi

Belirtilen TextReader'dan XML belgesini yükler.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Belgeye XML verisini aktarmak için kullanılan TextReader. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) yöntemi

Belirtilen [XmlReader](../../xmlreader/)'den XML belgesini yükler.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Belgeye XML verisini aktarmak için kullanılan [XmlReader](../../xmlreader/). |

## Ayrıca bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [XmlReader](../../xmlreader/)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)