---
title: Deserialize()
second_title: Aspose.Slides for C++ API Referansı
description: XML belgesini nesneye dönüştürür.
type: docs
weight: 14
url: /tr/system.xml.serialization/xmlserializer/deserialize/
---
## XmlSerializer::Deserialize(System::SharedPtr\<IO::Stream\>) metodu

XML belgesini nesneye dönüştürür.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::Stream> stream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Belgeyi okumak için kullanılan akış. |

### Dönüş Değeri

[Object](../../../system/object/) daha önce verilen belgeye serileştirilmiş olan.

## XmlSerializer::Deserialize(System::SharedPtr\<IO::TextReader\>) metodu

XML belgesini nesneye dönüştürür.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<IO::TextReader> textReader)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textReader | [System::SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Belgeyi okumak için kullanılan okuyucu. |

### Dönüş Değeri

[Object](../../../system/object/) daha önce verilen belgeye serileştirilmiş olan.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>) metodu

XML belgesini nesneye dönüştürür.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Belgeyi okumak için kullanılan okuyucu. |

### Dönüş Değeri

[Object](../../../system/object/) daha önce verilen belgeye serileştirilmiş olan.

## XmlSerializer::Deserialize(System::SharedPtr\<XmlReader\>, String) metodu

XML belgesini nesneye dönüştürür.

```cpp
System::SharedPtr<Object> System::Xml::Serialization::XmlSerializer::Deserialize(System::SharedPtr<XmlReader> xmlReader, String encodingStyle)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Belgeyi okumak için kullanılan okuyucu. |
| encodingStyle | [String](../../../system/string/) | Nesneyi serileştirmek için kullanılan stil. |

### Dönüş Değeri

[Object](../../../system/object/) daha önce verilen belgeye serileştirilmiş olan.

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [Object](../../../system/object/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [XmlSerializer](../)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Sınıf [String](../../../system/string/)
* Ad Alanı [System::Xml::Serialization](../../)
* Kütüphane [Aspose.Slides](../../../)