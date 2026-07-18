---
title: MoveToChild()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετακινεί τον XPathNavigator στον κόμβο-παιδί με το καθορισμένο τοπικό όνομα και το URI ονόματος χώρου.
type: docs
weight: 690
url: /el/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) μέθοδος

Μετακινεί το [XPathNavigator](../) στον κόμβο-παιδί με το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του κόμβου-παιδιού στον οποίο θα μετακινηθεί. |
| namespaceURI | [String](../../../system/string/) | Το URI ονόματος χώρου του κόμβου-παιδιού στον οποίο θα μετακινηθεί. |

### Τιμή επιστροφής

**true** εάν το [XPathNavigator](../) μετακινείται επιτυχώς στον κόμβο-παιδί· διαφορετικά, **false**. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## XPathNavigator::MoveToChild(XPathNodeType) μέθοδος

Μετακινεί το [XPathNavigator](../) στον κόμβο-παιδί του καθορισμένου XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Το XPathNodeType του κόμβου-παιδιού στον οποίο θα μετακινηθεί. |

### Τιμή επιστροφής

**true** εάν το [XPathNavigator](../) μετακινείται επιτυχώς στον κόμβο-παιδί· διαφορετικά, **false**. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## Δείτε επίσης

* Απαρίθμηση [XPathNodeType](../../xpathnodetype/)
* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)