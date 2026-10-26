---
title: Compile()
second_title: Αναφορά API Aspose.Slides για C++
description: Μεταγλωττίζει την καθορισμένη έκφραση XPath και επιστρέφει ένα αντικείμενο XPathExpression που αντιπροσωπεύει την έκφραση XPath.
type: docs
weight: 66
url: /el/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) method

Μεταγλωττίζει την [XPath](../../) έκφραση που καθορίζεται και επιστρέφει ένα [XPathExpression](../) αντικείμενο που αντιπροσωπεύει την [XPath](../../) έκφραση.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Μια [XPath](../../) έκφραση. |

### Τιμή επιστροφής

Ένα [XPathExpression](../) αντικείμενο.

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) method

Μεταγλωττίζει την καθορισμένη [XPath](../../) έκφραση, με το αντικείμενο [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) που έχει καθοριστεί για την επίλυση ονομάτων χώρου, και επιστρέφει ένα [XPathExpression](../) αντικείμενο που αντιπροσωπεύει την [XPath](../../) έκφραση.

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Μια [XPath](../../) έκφραση. |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Ένα αντικείμενο που υλοποιεί τη διεπαφή [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) για την επίλυση ονομάτων χώρου. |

### Τιμή επιστροφής

Ένα [XPathExpression](../) αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [XPathExpression](../)
* Κλάση [String](../../../system/string/)
* Κλάση [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)