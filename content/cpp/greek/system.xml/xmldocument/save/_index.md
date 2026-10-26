---
title: Save()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποθηκεύει το έγγραφο XML στο καθορισμένο αρχείο. Εάν το καθορισμένο αρχείο υπάρχει, αυτή η μέθοδος το αντικαθιστά.
type: docs
weight: 534
url: /el/system.xml/xmldocument/save/
---
## XmlDocument::Save(String) μέθοδος

Αποθηκεύει το έγγραφο XML στο καθορισμένο αρχείο. Εάν το καθορισμένο αρχείο υπάρχει, αυτή η μέθοδος το αντικαθιστά.

```cpp
virtual void System::Xml::XmlDocument::Save(String filename)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | [String](../../../system/string/) | Η θέση του αρχείου όπου θέλετε να αποθηκεύσετε το έγγραφο. |

## XmlDocument::Save(SharedPtr\<IO::Stream\>) μέθοδος

Αποθηκεύει το έγγραφο XML στο καθορισμένο ρεύμα.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::Stream> outStream)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Το ρεύμα στο οποίο θέλετε να αποθηκεύσετε. |

## XmlDocument::Save(SharedPtr\<IO::TextWriter\>) μέθοδος

Αποθηκεύει το έγγραφο XML στον καθορισμένο TextWriter.

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<IO::TextWriter> writer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| writer | [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\> | Ο TextWriter στον οποίο θέλετε να αποθηκεύσετε. |

## XmlDocument::Save(SharedPtr\<XmlWriter\>) μέθοδος

Αποθηκεύει το έγγραφο XML στον καθορισμένο [XmlWriter](../../xmlwriter/).

```cpp
virtual void System::Xml::XmlDocument::Save(SharedPtr<XmlWriter> w)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| w | [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../xmlwriter/)\> | Το [XmlWriter](../../xmlwriter/) στο οποίο θέλετε να αποθηκεύσετε. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlDocument](../)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [TextWriter](../../../system.io/textwriter/)
* Κλάση [XmlWriter](../../xmlwriter/)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)