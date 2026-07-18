---
title: Transform()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε ένα XmlWriter.
type: docs
weight: 40
url: /el/system.xml.xsl/xslcompiledtransform/transform/
---
## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα προς μετασχηματισμό. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/). Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα προς μετασχηματισμό. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε ένα TextWriter. Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα προς μετασχηματισμό. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Το TextWriter στο οποίο θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε μια ροή. Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα προς μετασχηματισμό. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το [XmlReader](../../../system.xml/xmlreader/) αντικείμενο και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Το [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο εισόδου. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το [XmlReader](../../../system.xml/xmlreader/) αντικείμενο και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/). Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το [XmlReader](../../../system.xml/xmlreader/) αντικείμενο και εξάγει τα αποτελέσματα σε ένα TextWriter. Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Το TextWriter στο οποίο θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το [XmlReader](../../../system.xml/xmlreader/) αντικείμενο και εξάγει τα αποτελέσματα σε μια ροή. Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το URI και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI του εγγράφου εισόδου. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το URI και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/). Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI του εγγράφου εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το URI και εξάγει τα αποτελέσματα σε ένα TextWriter.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::TextWriter> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI του εγγράφου εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Το TextWriter στο οποίο θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const String\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το URI και εξάγει τα αποτελέσματα σε ροή. Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<IO::Stream> &results)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI του εγγράφου εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |

## XslCompiledTransform::Transform(const String\&, const String\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το URI και εξάγει τα αποτελέσματα σε αρχείο.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const String &inputUri, const String &resultsFile)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | Το URI του εγγράφου εισόδου. |
| resultsFile | const [String](../../../system/string/)\& | Το URI του αρχείου εξόδου. |

## XslCompiledTransform::Transform(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το [XmlReader](../../../system.xml/xmlreader/) αντικείμενο και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/). Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης και το [XmlResolver](../../../system.xml/xmlresolver/) επιλύει τη λειτουργία XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<XmlReader> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει το έγγραφο εισόδου. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ορίσματα με καθορισμό ονοματοχώρου που χρησιμοποιούνται ως είσοδος για τη μετατροπή. Αυτή η τιμή μπορεί να είναι **nullptr**. |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Ο [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της λειτουργίας XSLT **document()**. Εάν είναι **nullptr**, η λειτουργία **document()** δεν επιλύεται. |

## XslCompiledTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<XmlResolver\>\&) μέθοδος

Εκτελεί τη μετατροπή χρησιμοποιώντας το έγγραφο εισόδου που καθορίζεται από το αντικείμενο IXPathNavigable και εξάγει τα αποτελέσματα σε ένα [XmlWriter](../../../system.xml/xmlwriter/). Το [XsltArgumentList](../../xsltargumentlist/) παρέχει πρόσθετα επιχειρήματα χρόνου εκτέλεσης και το [XmlResolver](../../../system.xml/xmlresolver/) επιλύει τη λειτουργία XSLT **document()**.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &arguments, const SharedPtr<XmlWriter> &results, const SharedPtr<XmlResolver> &documentResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Το έγγραφο προς μετατροπή που καθορίζεται από το αντικείμενο IXPathNavigable. |
| arguments | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Λίστα ορισμάτων ως [XsltArgumentList](../../xsltargumentlist/). |
| results | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. Εάν το φύλλο στυλ περιέχει ένα στοιχείο **xsl:output**, θα πρέπει να δημιουργήσετε το [XmlWriter](../../../system.xml/xmlwriter/) χρησιμοποιώντας το αντικείμενο [XmlWriterSettings](../../../system.xml/xmlwritersettings/) που επιστρέφεται από την τιμή [XslCompiledTransform::get_OutputSettings](../get_outputsettings/). Αυτό διασφαλίζει ότι το [XmlWriter](../../../system.xml/xmlwriter/) έχει τις σωστές ρυθμίσεις εξαγωγής. |
| documentResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Ο [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της λειτουργίας XSLT **document()**. Εάν είναι **nullptr**, η λειτουργία **document()** δεν επιλύεται. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XslCompiledTransform](../)
* Class [XsltArgumentList](../../xsltargumentlist/)
* Class [TextWriter](../../../system.io/textwriter/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [String](../../../system/string/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)