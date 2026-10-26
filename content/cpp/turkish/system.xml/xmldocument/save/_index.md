---
title: Save()
second_title: Aspose.Slides for C++ API Referansı
description: XML belgesini belirtilen dosyaya kaydeder. Belirtilen dosya mevcutsa, bu metot üzerine yazar.
type: docs
weight: 534
url: /tr/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) metodu

XML belgesini belirtilen dosyaya kaydeder. Belirtilen dosya varsa, bu metot onu üzerine yazar.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Belgeyi kaydetmek istediğiniz dosyanın konumu. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) metodu

XML belgesini belirtilen akışa kaydeder.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Kaydetmek istediğiniz akış. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) metodu

XML belgesini belirtilen TextWriter'a kaydeder.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Kaydetmek istediğiniz TextWriter. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) metodu

XML belgesini belirtilen [XmlWriter](../../xmlwriter/)'a kaydeder.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Kaydetmek istediğiniz [XmlWriter](../../xmlwriter/). |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlDocument](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [TextWriter](../../../system.io/textwriter/)
* Sınıf [XmlWriter](../../xmlwriter/)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)