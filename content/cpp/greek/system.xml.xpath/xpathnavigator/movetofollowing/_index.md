---
title: MoveToFollowing()
second_title: Αναφορά API Aspose.Slides για C++
description: Μετακινεί το XPathNavigator στο στοιχείο με το τοπικό όνομα και το URI του χώρου ονομάτων που καθορίζονται με τη σειρά του εγγράφου.
type: docs
weight: 703
url: /el/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) μέθοδος

Μετακινεί το [XPathNavigator](../) στο στοιχείο με το τοπικό όνομα και το URI χώρου ονομάτων που έχουν καθοριστεί με τη σειρά του εγγράφου.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινήθηκε επιτυχώς· διαφορετικά, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) μέθοδος

Μετακινεί το [XPathNavigator](../) στο στοιχείο με το τοπικό όνομα και το URI χώρου ονομάτων που έχουν καθοριστεί, στο όριο που έχει καθοριστεί, με τη σειρά του εγγράφου.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Το τοπικό όνομα του στοιχείου. |
| namespaceURI | [String](../../../system/string/) | Το URI του χώρου ονομάτων του στοιχείου. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Το αντικείμενο [XPathNavigator](../) τοποθετημένο στο όριο του στοιχείου, το οποίο το τρέχον [XPathNavigator](../) δεν θα περάσει κατά την αναζήτηση του επόμενου στοιχείου. |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινήθηκε επιτυχώς· διαφορετικά, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) μέθοδος

Μετακινεί το [XPathNavigator](../) στο επόμενο στοιχείο του καθορισμένου XPathNodeType με τη σειρά του εγγράφου.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Το XPathNodeType του στοιχείου. Το XPathNodeType δεν μπορεί να είναι [XPathNodeType::Attribute](../../xpathnodetype/) ή [XPathNodeType::Namespace](../../xpathnodetype/). |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινήθηκε επιτυχώς· διαφορετικά, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) μέθοδος

Μετακινεί το [XPathNavigator](../) στο επόμενο στοιχείο του καθορισμένου XPathNodeType, στο όριο που έχει καθοριστεί, με τη σειρά του εγγράφου.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Το XPathNodeType του στοιχείου. Το XPathNodeType δεν μπορεί να είναι [XPathNodeType::Attribute](../../xpathnodetype/) ή [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Το αντικείμενο [XPathNavigator](../) τοποθετημένο στο όριο του στοιχείου, το οποίο το τρέχον [XPathNavigator](../) δεν θα περάσει κατά την αναζήτηση του επόμενου στοιχείου. |

### Τιμή Επιστροφής

**true** εάν το [XPathNavigator](../) μετακινήθηκε επιτυχώς· διαφορετικά, **false**.

## Δείτε επίσης

* Απαρίθμηση [XPathNodeType](../../xpathnodetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)