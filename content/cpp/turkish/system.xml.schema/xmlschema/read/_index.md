---
title: Read()
second_title: Aspose.Slides için C++ API Referansı
description: "Sağlanan IO::TextReader'dan bir XML Şeması okur."
type: docs
weight: 365
url: /tr/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) method

Sağlanan [IO::TextReader](../../../system.io/textreader/)'den bir XML [Schema](../../) okur.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Okunacak XML [Schema](../../)'yi içeren [IO::TextReader](../../../system.io/textreader/). |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) sözdizimi hataları hakkında bilgi alan doğrulama olay işleyicisi. |

### Dönüş Değeri

XML [Schema](../../)'yi temsil eden [XmlSchema](../) nesnesi.

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) method

Sağlanan akıştan bir XML [Schema](../../) okur.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Sağlanan veri akışı. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) sözdizimi hataları hakkında bilgi alan doğrulama olay işleyicisi. |

### Dönüş Değeri

XML [Schema](../../)'yi temsil eden [XmlSchema](../) nesnesi.

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) method

Sağlanan [XmlReader](../../../system.xml/xmlreader/)'den bir XML [Schema](../../) okur.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Okunacak XML [Schema](../../)'yi içeren [XmlReader](../../../system.xml/xmlreader/). |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | XML [Schema](../../) sözdizimi hataları hakkında bilgi alan doğrulama olay işleyicisi. |

### Dönüş Değeri

XML [Schema](../../)'yi temsil eden [XmlSchema](../) nesnesi.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Class [XmlSchema](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)