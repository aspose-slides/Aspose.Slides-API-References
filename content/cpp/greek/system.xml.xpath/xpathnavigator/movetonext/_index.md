---
title: MoveToNext()
second_title: Αναφορά API Aspose.Slides για C++
description: Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινεί το XPathNavigator στον επόμενο αδερφό κόμβο του τρέχοντος κόμβου.
type: docs
weight: 586
url: /el/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() μέθοδος

Όταν παρακαμφθεί σε μια παράγωγη κλάση, μετακινεί το [XPathNavigator](../) στον επόμενο αδερφό κόμβο του τρέχοντος κόμβου.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινείται επιτυχώς στον επόμενο αδερφό κόμβο· διαφορετικά **false** εάν δεν υπάρχουν άλλοι αδερφοί ή εάν το [XPathNavigator](../) βρίσκεται επί του παρόντος σε κόμβο χαρακτηριστικού. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## XPathNavigator::MoveToNext(String, String) μέθοδος

Μετακινεί το [XPathNavigator](../) στον επόμενο αδερφό κόμβο με το τοπικό όνομα και το URI ονόματος χώρου που καθορίζονται.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του επόμενου αδερφικού κόμβου στον οποίο θα μεταφερθεί. |
| namespaceURI | [String](../../../system/string/) | Το URI ονόματος χώρου του επόμενου αδερφικού κόμβου στον οποίο θα μεταφερθεί. |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινείται επιτυχώς στον επόμενο αδερφό κόμβο· **false** εάν δεν υπάρχουν άλλοι αδερφοί ή εάν το [XPathNavigator](../) βρίσκεται επί του παρόντος σε κόμβο χαρακτηριστικού. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## XPathNavigator::MoveToNext(XPathNodeType) μέθοδος

Μετακινεί το [XPathNavigator](../) στον επόμενο αδερφό κόμβο του τρέχοντος κόμβου που ταιριάζει με τον καθορισμένο XPathNodeType.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Το XPathNodeType του αδερφικού κόμβου στον οποίο θα μεταφερθεί. |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινείται επιτυχώς στον επόμενο αδερφό κόμβο· διαφορετικά **false** εάν δεν υπάρχουν άλλοι αδερφοί ή εάν το [XPathNavigator](../) βρίσκεται σε κόμβο χαρακτηριστικού. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## Δείτε επίσης

* Απαρίθμηση [XPathNodeType](../../xpathnodetype/)
* Κλάση [XPathNavigator](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)