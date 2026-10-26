---
title: Transform()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε έναν XmlReader.
type: docs
weight: 40
url: /el/system.xml.xsl/xsltransform/transform/
---
## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροφή. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

### Τιμή Επιστροφής

Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει τα αποτελέσματα της μετατροπής.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |

### Τιμή Επιστροφής

Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει τα αποτελέσματα της μετατροπής.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα args και εξάγει το αποτέλεσμα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα args και εξάγει το αποτέλεσμα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε μια ροή.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε μια ροή.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε έναν TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο XPathNavigator χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε έναν TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::XPathNavigator> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα XPathNavigator που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να εξάγετε. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

### Τιμή Επιστροφής

Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει τα αποτελέσματα της μετατροπής.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlReader](../../../system.xml/xmlreader/).

```cpp
SharedPtr<XmlReader> System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |

### Τιμή Επιστροφής

Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει τα αποτελέσματα της μετατροπής.

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε έναν TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::TextWriter\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε έναν TextWriter.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::TextWriter> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | Ο TextWriter στον οποίο θέλετε να εξάγετε. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε μια ροή.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την [XslTransform::Transform](./) μέθοδο. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<IO::Stream\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε μια ροή.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<IO::Stream> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Η ροή στην οποία θέλετε να εξάγετε. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Transform(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<XsltArgumentList\>\&, const SharedPtr\<XmlWriter\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο IXPathNavigable χρησιμοποιώντας τα καθορισμένα **args** και εξάγει το αποτέλεσμα σε ένα [XmlWriter](../../../system.xml/xmlwriter/).

```cpp
void System::Xml::Xsl::XslTransform::Transform(const SharedPtr<System::Xml::XPath::IXPathNavigable> &input, const SharedPtr<XsltArgumentList> &args, const SharedPtr<XmlWriter> &output)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί το interface IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει τα δεδομένα που θα μετατραπούν. |
| args | const [SharedPtr](../../../system/sharedptr/)\<[XsltArgumentList](../../xsltargumentlist/)\>\& | Ένα [XsltArgumentList](../../xsltargumentlist/) που περιέχει τα ονομαστικά-κατηγοριοποιημένα επιχειρήματα που χρησιμοποιούνται ως είσοδος στη μετατροπή. |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../../../system.xml/xmlwriter/)\>\& | Το [XmlWriter](../../../system.xml/xmlwriter/) στο οποίο θέλετε να εξάγετε. |

## XslTransform::Transform(const String\&, const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο αρχείο εισόδου και εξάγει το αποτέλεσμα σε αρχείο εξόδου.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Το URL του πηγής εγγράφου που θα μετατραπεί. |
| outputfile | const [String](../../../system/string/)\& | Το URL του αρχείου εξόδου. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση της συνάρτησης XSLT **document()**. Εάν είναι **nullptr**, η συνάρτηση **document()** δεν επιλύεται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην προσωρινή μνήμη μετά την [XslTransform::Transform](./) μέθοδο. |

## XslTransform::Transform(const String\&, const String\&) μέθοδος

Μετατρέπει τα δεδομένα XML στο αρχείο εισόδου και εξάγει το αποτέλεσμα σε αρχείο εξόδου.

```cpp
void System::Xml::Xsl::XslTransform::Transform(const String &inputfile, const String &outputfile)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| inputfile | const [String](../../../system/string/)\& | Το URL του πηγής εγγράφου που θα μετατραπεί. |
| outputfile | const [String](../../../system/string/)\& | Το URL του αρχείου εξόδου. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XmlReader](../../../system.xml/xmlreader/)
* Κλάση [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Κλάση [XsltArgumentList](../../xsltargumentlist/)
* Κλάση [XmlResolver](../../../system.xml/xmlresolver/)
* Κλάση [XslTransform](../)
* Κλάση [XmlWriter](../../../system.xml/xmlwriter/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [TextWriter](../../../system.io/textwriter/)
* Κλάση [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)