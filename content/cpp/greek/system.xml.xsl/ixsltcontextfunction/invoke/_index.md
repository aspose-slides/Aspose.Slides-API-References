---
title: Invoke()
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει τη μέθοδο για την κλήση της συνάρτησης με τα δοσμένα ορίσματα στο δοσμένο περιβάλλον.
type: docs
weight: 53
url: /el/system.xml.xsl/ixsltcontextfunction/invoke/
---
## IXsltContextFunction::Invoke(SharedPtr\<XsltContext\>, ArrayPtr\<SharedPtr\<Object\>\>, SharedPtr\<System::Xml::XPath::XPathNavigator\>) μέθοδος

Παρέχει τη μέθοδο για την κλήση της συνάρτησης με τα δεδομένα ορίσματα στο δεδομένο περιβάλλον.

```cpp
virtual SharedPtr<Object> System::Xml::Xsl::IXsltContextFunction::Invoke(SharedPtr<XsltContext> xsltContext, ArrayPtr<SharedPtr<Object>> args, SharedPtr<System::Xml::XPath::XPathNavigator> docContext)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xsltContext | [SharedPtr](../../../system/sharedptr/)\<[XsltContext](../../xsltcontext/)\> | Το XSLT περιβάλλον για την κλήση της συνάρτησης. |
| args | [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\> | Τα ορίσματα της κλήσης της συνάρτησης. Κάθε όρισμα είναι ένα στοιχείο στον πίνακα. |
| docContext | [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Ο κόμβος περιβάλλοντος για την κλήση της συνάρτησης. |

### Τιμή Επιστροφής

Ένα [Object](../../../system/object/) που αντιπροσωπεύει την τιμή επιστροφής της συνάρτησης.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [XsltContext](../../xsltcontext/)
* Κλάση [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Κλάση [IXsltContextFunction](../)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)