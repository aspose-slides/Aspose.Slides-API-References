---
title: XmlTextWriter()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen akış ve kodlamayı kullanarak XmlTextWriter sınıfının bir örneğini oluşturur.
type: docs
weight: 183
url: /tr/system.xml/xmltextwriter/xmltextwriter/
---
## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Text::Encoding\>\&) yapıcı


Belirtilen akış ve kodlamayı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::Stream> &w, const SharedPtr<Text::Encoding> &encoding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Yazmak istediğiniz akış. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Oluşturulacak kodlama. Kodlama **nullptr** ise akışı UTF-8 olarak yazar ve **ProcessingInstruction** öğesinden kodlama özniteliğini atlar. |

## XmlTextWriter::XmlTextWriter(const String\&, const SharedPtr\<Text::Encoding\>\&) yapıcı


Belirtilen dosyayı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const String &filename, const SharedPtr<Text::Encoding> &encoding)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Yazılacak dosya adı. Dosya varsa, içeriği kesilir ve yeni içerikle üzerine yazılır. |
| encoding | const [SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Oluşturulacak kodlama. Kodlama **nullptr** ise dosyayı UTF-8 olarak yazar ve **ProcessingInstruction** öğesinden kodlama özniteliğini atlar. |

## XmlTextWriter::XmlTextWriter(const SharedPtr\<IO::TextWriter\>\&) yapıcı


Belirtilen TextWriter'ı kullanarak [XmlTextWriter](../) sınıfının bir örneğini oluşturur.

```cpp
System::Xml::XmlTextWriter::XmlTextWriter(const SharedPtr<IO::TextWriter> &w)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Yazılacak TextWriter. TextWriter'ın zaten doğru kodlamaya ayarlandığı varsayılır. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [Encoding](../../../system.text/encoding/)
* Sınıf [XmlTextWriter](../)
* Sınıf [String](../../../system/string/)
* Sınıf [TextWriter](../../../system.io/textwriter/)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)