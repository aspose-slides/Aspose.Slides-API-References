---
title: MoveToNextNamespace()
second_title: Αναφορά API Aspose.Slides για C++
description: Όταν παρακάμπτεται σε μια παράγωγη κλάση, μετακινεί τον XPathNavigator στον επόμενο κόμβο χώρου ονομάτων που ταιριάζει με το καθορισμένο XPathNamespaceScope.
type: docs
weight: 573
url: /el/system.xml.xpath/xpathnavigator/movetonextnamespace/
---
## XPathNavigator::MoveToNextNamespace(XPathNamespaceScope) μέθοδος


Όταν παρακάμπτεται σε μια παράγωγη κλάση, μετακινεί το [XPathNavigator](../) στον επόμενο κόμβο χώρου ονομάτων που ταιριάζει με το καθορισμένο XPathNamespaceScope.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace(XPathNamespaceScope namespaceScope)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceScope | [XPathNamespaceScope](../../xpathnamespacescope/) | Μια τιμή XPathNamespaceScope που περιγράφει το πεδίο του χώρου ονομάτων. |

### Return Value

**true** εάν το [XPathNavigator](../) είναι επιτυχές μετακινώντας στον επόμενο κόμβο χώρου ονομάτων· διαφορετικά, **false**. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## XPathNavigator::MoveToNextNamespace() μέθοδος


Μετακινεί το [XPathNavigator](../) στον επόμενο κόμβο χώρου ονομάτων.

```cpp
bool System::Xml::XPath::XPathNavigator::MoveToNextNamespace()
```


### Return Value

**true** εάν το [XPathNavigator](../) είναι επιτυχές μετακινώντας στον επόμενο κόμβο χώρου ονομάτων· διαφορετικά, **false**. Εάν **false**, η θέση του [XPathNavigator](../) παραμένει αμετάβλητη.

## Δείτε επίσης

* Enum [XPathNamespaceScope](../../xpathnamespacescope/)
* Κλάση [XPathNavigator](../)
* Χώρος ονομάτων [System::Xml::XPath](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)