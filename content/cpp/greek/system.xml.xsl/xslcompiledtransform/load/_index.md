---
title: Load()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Μεταγλωττίζει το φύλλο στυλ που περιέχεται στο XmlReader.
type: docs
weight: 27
url: /el/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) μέθοδος

Μεταγλωττίζει το φύλλο στυλ που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ένα [XmlReader](../../../system.xml/xmlreader/) που περιέχει το φύλλο στυλ. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) μέθοδος

Μεταγλωττίζει το φύλλο στυλ XSLT που περιέχεται στο [XmlReader](../../../system.xml/xmlreader/). Το [XmlResolver](../../../system.xml/xmlresolver/) επιλύει τυχόν στοιχεία **import** ή **include** του XSLT και οι ρυθμίσεις XSLT καθορίζουν τα δικαιώματα για το φύλλο στυλ.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Το [XmlReader](../../../system.xml/xmlreader/) που περιέχει το φύλλο στυλ. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Οι [XsltSettings](../../xsltsettings/) που θα εφαρμοστούν στο φύλλο στυλ. Εάν είναι **nullptr**, εφαρμόζεται η ρύθμιση [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση τυχόν φύλλων στυλ που αναφέρονται σε στοιχεία **import** και **include** του XSLT. Εάν είναι **nullptr**, οι εξωτερικοί πόροι δεν επιλύονται. |

## XslCompiledTransform::Load(const String\&) μέθοδος

Φορτώνει και μεταγλωττίζει το φύλλο στυλ που βρίσκεται στην καθορισμένη URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Η URI του φύλλου στυλ. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) μέθοδος

Φορτώνει και μεταγλωττίζει το φύλλο στυλ XSLT που καθορίζεται από το URI. Το [XmlResolver](../../../system.xml/xmlresolver/) επιλύει τυχόν στοιχεία **import** ή **include** του XSLT και οι ρυθμίσεις XSLT καθορίζουν τα δικαιώματα για το φύλλο στυλ.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Η URI του φύλλου στυλ. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Οι [XsltSettings](../../xsltsettings/) που θα εφαρμοστούν στο φύλλο στυλ. Εάν είναι **nullptr**, εφαρμόζεται η ρύθμιση [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση του URI του φύλλου στυλ και τυχόν φύλλων στυλ που αναφέρονται σε στοιχεία **import** και **include** του XSLT. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) μέθοδος

Μεταγλωττίζει το φύλλο στυλ που περιέχεται στο αντικείμενο IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει το φύλλο στυλ. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) μέθοδος

Μεταγλωττίζει το φύλλο στυλ XSLT που περιέχεται στο IXPathNavigable. Το [XmlResolver](../../../system.xml/xmlresolver/) επιλύει τυχόν στοιχεία **import** ή **include** του XSLT και οι ρυθμίσεις XSLT καθορίζουν τα δικαιώματα για το φύλλο στυλ.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή IXPathNavigable. Μπορεί να είναι είτε ένα [XmlNode](../../../system.xml/xmlnode/) (συνήθως ένα [XmlDocument](../../../system.xml/xmldocument/)), είτε ένα XPathDocument που περιέχει το φύλλο στυλ. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Οι [XsltSettings](../../xsltsettings/) που θα εφαρμοστούν στο φύλλο στυλ. Εάν είναι **nullptr**, εφαρμόζεται η ρύθμιση [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | Το [XmlResolver](../../../system.xml/xmlresolver/) που χρησιμοποιείται για την επίλυση τυχόν φύλλων στυλ που αναφέρονται σε στοιχεία **import** και **include** του XSLT. Εάν είναι **nullptr**, οι εξωτερικοί πόροι δεν επιλύονται. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)