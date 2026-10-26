---
title: Load()
second_title: Aspose.Slides για C++ API Αναφορά
description: Φορτώνει το XML έγγραφο από το καθορισμένο URL.
type: docs
weight: 508
url: /el/system.xml/xmldocument/load/
---
## XmlDocument::Load(String) μέθοδος

Φορτώνει το XML έγγραφο από το καθορισμένο URL.

```cpp
virtual void System::Xml::XmlDocument::Load(String filename)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | [String](../../../system/string/) | URL του αρχείου που περιέχει το XML έγγραφο προς φόρτωση. Το URL μπορεί να είναι είτε τοπικό αρχείο είτε HTTP URL (μια [Web](../../../system.web/) διεύθυνση). |

## XmlDocument::Load(SharedPtr\<IO::Stream\>) μέθοδος

Φορτώνει το XML έγγραφο από τη συγκεκριμένη ροή.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::Stream> inStream)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Η ροή που περιέχει το XML έγγραφο προς φόρτωση. |

## XmlDocument::Load(SharedPtr\<IO::TextReader\>) μέθοδος

Φορτώνει το XML έγγραφο από το καθορισμένο TextReader.

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<IO::TextReader> txtReader)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| txtReader | [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\> | Ο TextReader που χρησιμοποιείται για την τροφοδοσία των XML δεδομένων στο έγγραφο. |

## XmlDocument::Load(SharedPtr\<XmlReader\>) μέθοδος

Φορτώνει το XML έγγραφο από το καθορισμένο [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlDocument::Load(SharedPtr<XmlReader> reader)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Το [XmlReader](../../xmlreader/) που χρησιμοποιείται για την τροφοδοσία των XML δεδομένων στο έγγραφο. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [TextReader](../../../system.io/textreader/)
* Κλάση [XmlReader](../../xmlreader/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)