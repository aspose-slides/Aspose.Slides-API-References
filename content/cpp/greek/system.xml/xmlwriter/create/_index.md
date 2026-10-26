---
title: Create()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια νέα παρουσία XmlWriter χρησιμοποιώντας το καθορισμένο όνομα αρχείου.
type: docs
weight: 469
url: /el/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το καθορισμένο όνομα αρχείου.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Το αρχείο στο οποίο θέλετε να γράψετε. Το [XmlWriter](../) δημιουργεί ένα αρχείο στην καθορισμένη διαδρομή και γράφει σε αυτό με σύνταξη κειμένου XML 1.0. Η **outputFileName** πρέπει να είναι διαδρομή του συστήματος αρχείων. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το όνομα αρχείου και το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | Το αρχείο στο οποίο θέλετε να γράψετε. Το [XmlWriter](../) δημιουργεί ένα αρχείο στην καθορισμένη διαδρομή και γράφει σε αυτό με σύνταξη κειμένου XML 1.0. Η **outputFileName** πρέπει να είναι διαδρομή του συστήματος αρχείων. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) που χρησιμοποιείται για τη διαμόρφωση του νέου αντικειμένου [XmlWriter](../). Εάν είναι **nullptr**, χρησιμοποιείται ένα [XmlWriterSettings](../../xmlwritersettings/) με προεπιλεγμένες ρυθμίσεις. Εάν το [XmlWriter](../) χρησιμοποιείται με τη μέθοδο XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) θα πρέπει να χρησιμοποιήσετε την τιμή XslCompiledTransform::get_OutputSettings για να αποκτήσετε ένα αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) με τις σωστές ρυθμίσεις. Αυτό διασφαλίζει ότι το δημιουργημένο αντικείμενο [XmlWriter](../) έχει τις σωστές ρυθμίσεις εξόδου. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το καθορισμένο ρεύμα.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Το ρεύμα στο οποίο θέλετε να γράψετε. Το [XmlWriter](../) γράφει σε σύνταξη κειμένου XML 1.0 και το προσθέτει στο καθορισμένο ρεύμα. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το ρεύμα και το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Το ρεύμα στο οποίο θέλετε να γράψετε. Το [XmlWriter](../) γράφει σε σύνταξη κειμένου XML 1.0 και το προσθέτει στο καθορισμένο ρεύμα. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) που χρησιμοποιείται για τη διαμόρφωση του νέου αντικειμένου [XmlWriter](../). Εάν είναι **nullptr**, χρησιμοποιείται ένα [XmlWriterSettings](../../xmlwritersettings/) με προεπιλεγμένες ρυθμίσεις. Εάν το [XmlWriter](../) χρησιμοποιείται με τη μέθοδο XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) θα πρέπει να χρησιμοποιήσετε την τιμή XslCompiledTransform::get_OutputSettings για να αποκτήσετε ένα αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) με τις σωστές ρυθμίσεις. Αυτό διασφαλίζει ότι το δημιουργημένο αντικείμενο [XmlWriter](../) έχει τις σωστές ρυθμίσεις εξόδου. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας τον καθορισμένο TextWriter.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να γράψετε. Το [XmlWriter](../) γράφει σε σύνταξη κειμένου XML 1.0 και το προσθέτει στον καθορισμένο TextWriter. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας τον TextWriter και τα αντικείμενα [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να γράψετε. Το [XmlWriter](../) γράφει σε σύνταξη κειμένου XML 1.0 και το προσθέτει στον καθορισμένο TextWriter. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) που χρησιμοποιείται για τη διαμόρφωση του νέου αντικειμένου [XmlWriter](../). Εάν είναι **nullptr**, χρησιμοποιείται ένα [XmlWriterSettings](../../xmlwritersettings/) με προεπιλεγμένες ρυθμίσεις. Εάν το [XmlWriter](../) χρησιμοποιείται με τη μέθοδο XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) θα πρέπει να χρησιμοποιήσετε την τιμή XslCompiledTransform::get_OutputSettings για να αποκτήσετε ένα αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) με τις σωστές ρυθμίσεις. Αυτό διασφαλίζει ότι το δημιουργημένο αντικείμενο [XmlWriter](../) έχει τις σωστές ρυθμίσεις εξόδου. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το καθορισμένο [Text::StringBuilder](../../../system.text/stringbuilder/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Το [Text::StringBuilder](../../../system.text/stringbuilder/) στο οποίο θα γραφτεί. Το περιεχόμενο που γράφεται από το [XmlWriter](../) προστίθεται στο [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας τα αντικείμενα [Text::StringBuilder](../../../system.text/stringbuilder/) και [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | Το [Text::StringBuilder](../../../system.text/stringbuilder/) στο οποίο θα γραφτεί. Το περιεχόμενο που γράφεται από το [XmlWriter](../) προστίθεται στο [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) που χρησιμοποιείται για τη διαμόρφωση του νέου αντικειμένου [XmlWriter](../). Εάν είναι **nullptr**, χρησιμοποιείται ένα [XmlWriterSettings](../../xmlwritersettings/) με προεπιλεγμένες ρυθμίσεις. Εάν το [XmlWriter](../) χρησιμοποιείται με τη μέθοδο XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) θα πρέπει να χρησιμοποιήσετε την τιμή XslCompiledTransform::get_OutputSettings για να αποκτήσετε ένα αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) με τις σωστές ρυθμίσεις. Αυτό διασφαλίζει ότι το δημιουργημένο αντικείμενο [XmlWriter](../) έχει τις σωστές ρυθμίσεις εξόδου. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας το καθορισμένο αντικείμενο [XmlWriter](../).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Το αντικείμενο [XmlWriter](../) που θέλετε να χρησιμοποιήσετε ως υποκείμενο γράφοντα. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../) που περιβάλλεται γύρω από το καθορισμένο αντικείμενο [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) μέθοδος


Δημιουργεί ένα νέο αντικείμενο [XmlWriter](../) χρησιμοποιώντας τα καθορισμένα αντικείμενα [XmlWriter](../) και [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | Το αντικείμενο [XmlWriter](../) που θέλετε να χρησιμοποιήσετε ως υποκείμενο γράφοντα. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | Το αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) που χρησιμοποιείται για τη διαμόρφωση του νέου αντικειμένου [XmlWriter](../). Εάν είναι **nullptr**, χρησιμοποιείται ένα [XmlWriterSettings](../../xmlwritersettings/) με προεπιλεγμένες ρυθμίσεις. Εάν το [XmlWriter](../) χρησιμοποιείται με τη μέθοδο XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>) θα πρέπει να χρησιμοποιήσετε την τιμή XslCompiledTransform::get_OutputSettings για να αποκτήσετε ένα αντικείμενο [XmlWriterSettings](../../xmlwritersettings/) με τις σωστές ρυθμίσεις. Αυτό διασφαλίζει ότι το δημιουργημένο αντικείμενο [XmlWriter](../) έχει τις σωστές ρυθμίσεις εξόδου. |

### Τιμή Επιστροφής

Ένα αντικείμενο [XmlWriter](../) που περιβάλλεται γύρω από το καθορισμένο αντικείμενο [XmlWriter](../).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../)
* Class [String](../../../system/string/)
* Class [XmlWriterSettings](../../xmlwritersettings/)
* Class [Stream](../../../system.io/stream/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)