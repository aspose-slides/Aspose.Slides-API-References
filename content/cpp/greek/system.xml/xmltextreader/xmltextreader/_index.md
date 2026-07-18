---
title: XmlTextReader()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αρχικοποιεί μια νέα παρουσία της κλάσης XmlTextReader με τη καθορισμένη ροή.
type: docs
weight: 482
url: /el/system.xml/xmltextreader/xmltextreader/
---
## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με τη καθορισμένη ροή.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML για ανάγνωση. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο URL και τη ροή.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που θα χρησιμοποιηθεί για την επίλυση εξωτερικών πόρων. Το [XmlTextReader::get_BaseURI](../get_baseuri/) ορίζεται σε αυτήν την τιμή. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML για ανάγνωση. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με τη καθορισμένη ροή και το [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML για ανάγνωση. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο URL, τη ροή και το [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::Stream> &input, const SharedPtr<XmlNameTable> &nt)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που θα χρησιμοποιηθεί για την επίλυση εξωτερικών πόρων. Το [XmlTextReader::get_BaseURI](../get_baseuri/) ορίζεται σε αυτήν την τιμή. Αν **url** είναι **nullptr**, το **BaseURI** ορίζεται σε [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει τα δεδομένα XML για ανάγνωση. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο TextReader που περιέχει τα δεδομένα XML για ανάγνωση. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο URL και TextReader.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που θα χρησιμοποιηθεί για την επίλυση εξωτερικών πόρων. Το [XmlTextReader::get_BaseURI](../get_baseuri/) ορίζεται σε αυτήν την τιμή. |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο TextReader που περιέχει τα δεδομένα XML για ανάγνωση. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο TextReader και το [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο TextReader που περιέχει τα δεδομένα XML για ανάγνωση. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlNameTable\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο URL, TextReader και το [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlNameTable> &nt)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που θα χρησιμοποιηθεί για την επίλυση εξωτερικών πόρων. Το [XmlTextReader::get_BaseURI](../get_baseuri/) ορίζεται σε αυτήν την τιμή. Αν **url** είναι **nullptr**, το **BaseURI** ορίζεται σε [String::Empty](../../../system/string/empty/). |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | Ο TextReader που περιέχει τα δεδομένα XML για ανάγνωση. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί. |

## XmlTextReader::XmlTextReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με τη καθορισμένη ροή, XmlNodeType και [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή που περιέχει το τμήμα XML για ανάλυση. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Το XmlNodeType του τμήματος XML. Καθορίζει επίσης τι μπορεί να περιέχει το τμήμα. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Το [XmlParserContext](../../xmlparsercontext/) στο οποίο θα αναλυθεί το **xmlFragment**. Περιλαμβάνει το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί, κωδικοποίηση, πεδίο ονοματοχώρου, την τρέχουσα **xml:lang** και το πεδίο **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο συμβολοσειρά, XmlNodeType και [XmlParserContext](../../xmlparsercontext/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | Η συμβολοσειρά που περιέχει το τμήμα XML για ανάλυση. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Το XmlNodeType του τμήματος XML. Καθορίζει επίσης τι μπορεί να περιέχει η συμβολοσειρά τμήματος. |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Το [XmlParserContext](../../xmlparsercontext/) στο οποίο θα αναλυθεί το **xmlFragment**. Περιλαμβάνει το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί, κωδικοποίηση, πεδίο ονοματοχώρου, την τρέχουσα **xml:lang** και το πεδίο **xml:space**. |

## XmlTextReader::XmlTextReader(const String\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο αρχείο.

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL του αρχείου που περιέχει τα δεδομένα XML. Το [XmlTextReader::get_BaseURI](../get_baseuri/) ορίζεται σε αυτήν την τιμή. |

## XmlTextReader::XmlTextReader(const String\&, const SharedPtr\<XmlNameTable\>\&) constructor

Αρχικοποιεί μια νέα παρουσία της [XmlTextReader](../) κλάσης με το καθορισμένο αρχείο και το [XmlNameTable](../../xmlnametable/).

```cpp
System::Xml::XmlTextReader::XmlTextReader(const String &url, const SharedPtr<XmlNameTable> &nt)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL του αρχείου που περιέχει τα δεδομένα XML για ανάγνωση. |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Το [XmlNameTable](../../xmlnametable/) που θα χρησιμοποιηθεί. |

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [XmlTextReader](../)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [TextReader](../../../system.io/textreader/)
* Class [XmlParserContext](../../xmlparsercontext/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)