---
title: Load()
second_title: Αναφορά API του Aspose.Slides για C++
description: Φορτώνει το φύλλο στυλ XSLT που περιέχεται στο XmlReader.
type: docs
weight: 27
url: /el/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) μέθοδος

Φορτώνει το φύλλο στυλ XSLT που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) αντικείμενο που περιέχει το φύλλο στυλ XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Φορτώνει το φύλλο στυλ XSLT που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) αντικείμενο που περιέχει το φύλλο στυλ XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για τη φόρτωση τυχόν φύλλων στυλ που αναφέρονται στα στοιχεία **xsl:import** και **xsl:include**. Αν είναι **nullptr**, δεν επιλύονται εξωτερικοί πόροι. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην κρυφή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) μέθοδος

Φορτώνει το φύλλο στυλ XSLT που περιέχεται στο IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει το φύλλο στυλ XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Φορτώνει το φύλλο στυλ XSLT που περιέχεται στο IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει το φύλλο στυλ XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για τη φόρτωση τυχόν φύλλων στυλ που αναφέρονται στα στοιχεία **xsl:import** και **xsl:include**. Αν είναι **nullptr**, δεν επιλύονται εξωτερικοί πόροι. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην κρυφή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) μέθοδος

Φορτώνει το φύλλο στυ λ XSLT που περιέχεται στο XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα αντικείμενο XPathNavigator που περιέχει το φύλλο στυλ XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Φορτώνει το φύλλο στυ λ XSLT που περιέχεται στο XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ένα αντικείμενο XPathNavigator που περιέχει το φύλλο στυ λ XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για τη φόρτωση τυχόν φύλλων στυλ που αναφέρονται στα στοιχεία **xsl:import** και **xsl:include**. Αν είναι **nullptr**, δεν επιλύονται εξωτερικοί πόροι. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην κρυφή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## XslTransform::Load(const String\&) μέθοδος

Φορτώνει το φύλλο στυ λ XSLT που ορίζεται από ένα URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που καθορίζει το φύλλο στυ λ XSLT που θα φορτωθεί. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) μέθοδος

Φορτώνει το φύλλο στυ λ XSLT που ορίζεται από ένα URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | Το URL που καθορίζει το φύλλο στυ λ XSLT που θα φορτωθεί. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για τη φόρτωση του φύλλου στυλ και τυχόν φύλλου(ων) στυλ που αναφέρονται στα στοιχεία **xsl:import** και **xsl:include**. Αν είναι **nullptr**, χρησιμοποιείται ένα προεπιλεγμένο [XmlUrlResolver](../../../system.xml/xmlurlresolver/) χωρίς διαπιστευτήρια χρήστη για το άνοιγμα του φύλλου στυλ. Το προεπιλεγμένο [XmlUrlResolver](../../../system.xml/xmlurlresolver/) δεν χρησιμοποιείται για την επίλυση εξωτερικών πόρων στο φύλλο στυλ, έτσι τα στοιχεία **xsl:import** και **xsl:include** δεν επιλύονται. Το [XmlResolver](../../../system.xml/xmlresolver/) δεν αποθηκεύεται στην κρυφή μνήμη μετά την ολοκλήρωση αυτής της μεθόδου. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)