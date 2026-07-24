---
title: XPathDocument()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen XmlReader nesnesinde bulunan XML verilerinden XPathDocument sınıfının yeni bir örneğini başlatır.
type: docs
weight: 1
url: /tr/system.xml.xpath/xpathdocument/xpathdocument/
---
## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&) constructor

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML verilerinden [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XML verilerini içeren [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XPathDocument::XPathDocument(const SharedPtr\<XmlReader\>\&, XmlSpace) constructor

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinde bulunan XML verileri ve belirtilen boşluk işleme ayarıyla [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<XmlReader> &reader, XmlSpace space)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | XML verilerini içeren [XmlReader](../../../system.xml/xmlreader/) nesnesi. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Bir XmlSpace nesnesi. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::TextReader\>\&) constructor

Belirtilen TextReader nesnesinde bulunan XML verilerinden [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::TextReader> &textReader)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textReader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | XML verilerini içeren TextReader nesnesi. |

## XPathDocument::XPathDocument(const SharedPtr\<IO::Stream\>\&) constructor

Belirtilen Stream nesnesinde bulunan XML verilerinden [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const SharedPtr<IO::Stream> &stream)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | XML verilerini içeren Stream nesnesi. |

## XPathDocument::XPathDocument(const String\&) constructor

Belirtilen dosyada bulunan XML verilerinden [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | XML verilerini içeren dosyanın yolu. |

## XPathDocument::XPathDocument(const String\&, XmlSpace) constructor

Belirtilen dosyada bulunan XML verileri ve belirtilen boşluk işleme ayarıyla [XPathDocument](../) sınıfının yeni bir örneğini başlatır.

```cpp
System::Xml::XPath::XPathDocument::XPathDocument(const String &uri, XmlSpace space)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | XML verilerini içeren dosyanın yolu. |
| space | [XmlSpace](../../../system.xml/xmlspace/) | Bir XmlSpace nesnesi. |

## İlgili

* Enum [XmlSpace](../../../system.xml/xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Sınıf [XPathDocument](../)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)