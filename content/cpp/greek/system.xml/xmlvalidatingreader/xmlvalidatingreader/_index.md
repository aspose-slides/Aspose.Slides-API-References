---
title: XmlValidatingReader()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης XmlValidatingReader που επαληθεύει το περιεχόμενο που επιστρέφεται από το δεδομένο XmlReader.
type: docs
weight: 430
url: /el/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlValidatingReader](../) που επαληθεύει το περιεχόμενο που επιστρέφεται από το δοθέν [XmlReader](../../xmlreader/).

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | Το [XmlReader](../../xmlreader/) για ανάγνωση κατά την επαλήθευση. Η τρέχουσα υλοποίηση υποστηρίζει μόνο [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlValidatingReader](../) με τις καθορισμένες τιμές.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Η συμβολοσειρά που περιέχει το τμήμα XML προς ανάλυση. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Ο XmlNodeType του τμήματος XML. Αυτό επίσης καθορίζει τι μπορεί να περιέχει η συμβολοσειρά του τμήματος (βλ. πίνακα παρακάτω). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Το [XmlParserContext](../../xmlparsercontext/) στο οποίο θα αναλυθεί το τμήμα XML. Αυτό περιλαμβάνει το [NameTable](../../nametable/) προς χρήση, κωδικοποίηση, πεδίο ονομάτων, τρέχουσα **xml:lang** και **xml:space**. |

## Παρατηρήσεις

Ο παρακάτω πίνακας παραθέτει έγκυρες τιμές για το **fragType** και πώς ο αναγνώστης επεξεργάζεται κάθε διαφορετικό τύπο κόμβου.

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| Η τιμή ενός γνωρίσματος (το τμήμα μέσα στα εισαγωγικά). |
| Document| Τα περιεχόμενα ενός ολόκληρου εγγράφου XML· αυτό επιβάλλει κανόνες επιπέδου εγγράφου. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlValidatingReader](../) με τις καθορισμένες τιμές.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει το τμήμα XML προς ανάλυση. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Ο XmlNodeType του τμήματος XML. Αυτό καθορίζει τι μπορεί να περιέχει το τμήμα (βλ. πίνακα παρακάτω). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Το [XmlParserContext](../../xmlparsercontext/) στο οποίο θα αναλυθεί το τμήμα XML. Αυτό περιλαμβάνει το [XmlNameTable](../../xmlnametable/) προς χρήση, κωδικοποίηση, πεδίο ονομάτων, τρέχουσα **xml:lang** και **xml:space**. |

## Παρατηρήσεις

Ο παρακάτω πίνακας παραθέτει έγκυρες τιμές για το **fragType** και πώς ο αναγνώστης επεξεργάζεται κάθε διαφορετικό τύπο κόμβου.

| XmlNodeType | Fragment May Contain |
| --- | --- |
| Element| Any valid element content (for example, any combination of elements, comments, processing instructions, cdata, text, and entity references). |
| [Attribute](../../../system/attribute/)| Η τιμή ενός γνωρίσματος (το τμήμα μέσα στα εισαγωγικά). |
| Document| Τα περιεχόμενα ενός ολόκληρου εγγράφου XML· αυτό επιβάλλει κανόνες επιπέδου εγγράφου. |

## Δείτε επίσης

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlReader](../../xmlreader/)
* Κλάση [XmlValidatingReader](../)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlParserContext](../../xmlparsercontext/)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [System::Xml](../../)
* Library [Aspose.Slides](../../../)