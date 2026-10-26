---
title: Read()
second_title: Αναφορά API Aspose.Slides για C++
description: "Διαβάζει ένα XML Schema από τον παρεχόμενο IO::TextReader."
type: docs
weight: 365
url: /el/system.xml.schema/xmlschema/read/
---
## XmlSchema::Read(const SharedPtr\<IO::TextReader\>\&, ValidationEventHandler) μέθοδος

Διαβάζει ένα XML [Schema](../../) από το παρεχόμενο [IO::TextReader](../../../system.io/textreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::TextReader> &reader, ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Το [IO::TextReader](../../../system.io/textreader/) που περιέχει το XML [Schema](../../) προς ανάγνωση. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Ο διαχειριστής γεγονότων επικύρωσης που λαμβάνει πληροφορίες για τα συντακτικά σφάλματα XML [Schema](../../). |

### Τιμή επιστροφής

Το αντικείμενο [XmlSchema](../) που αντιπροσωπεύει το XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<IO::Stream\>\&, ValidationEventHandler) μέθοδος

Διαβάζει ένα XML [Schema](../../) από το παρεχόμενο ρεύμα.

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<IO::Stream> &stream, ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η παρεχόμενη ροή δεδομένων. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Ο διαχειριστής γεγονότων επικύρωσης που λαμβάνει πληροφορίες για τα συντακτικά σφάλματα XML [Schema](../../). |

### Τιμή επιστροφής

Το αντικείμενο [XmlSchema](../) που αντιπροσωπεύει το XML [Schema](../../).

## XmlSchema::Read(const SharedPtr\<XmlReader\>\&, ValidationEventHandler) μέθοδος

Διαβάζει ένα XML [Schema](../../) από το παρεχόμενο [XmlReader](../../../system.xml/xmlreader/).

```cpp
static SharedPtr<XmlSchema> System::Xml::Schema::XmlSchema::Read(const SharedPtr<XmlReader> &reader, ValidationEventHandler validationEventHandler)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Το [XmlReader](../../../system.xml/xmlreader/) που περιέχει το XML [Schema](../../) προς ανάγνωση. |
| validationEventHandler | [ValidationEventHandler](../../validationeventhandler/) | Ο διαχειριστής γεγονότων επικύρωσης που λαμβάνει πληροφορίες για τα συντακτικά σφάλματα XML [Schema](../../). |

### Τιμή επιστροφής

Το αντικείμενο [XmlSchema](../) που αντιπροσωπεύει το XML [Schema](../../).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ValidationEventHandler](../../validationeventhandler/)
* Κλάση [XmlSchema](../)
* Κλάση [TextReader](../../../system.io/textreader/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Χώρος ονομάτων [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)