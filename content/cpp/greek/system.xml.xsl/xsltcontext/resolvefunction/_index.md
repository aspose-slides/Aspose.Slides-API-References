---
title: ResolveFunction()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όταν αντικαθίσταται σε μια παράγωγη κλάση, επιλύει μια αναφορά συνάρτησης και επιστρέφει ένα IXsltContextFunction που αντιπροσωπεύει τη συνάρτηση. Το IXsltContextFunction χρησιμοποιείται κατά τη διάρκεια της εκτέλεσης για να ληφθεί η τιμή επιστροφής της συνάρτησης.
type: docs
weight: 27
url: /el/system.xml.xsl/xsltcontext/resolvefunction/
---
## XsltContext::ResolveFunction(String, String, ArrayPtr\<System::Xml::XPath::XPathResultType\>) μέθοδος

Όταν αντικαθίσταται σε μια παράγωγη κλάση, επιλύει μια αναφορά συνάρτησης και επιστρέφει ένα [IXsltContextFunction](../../ixsltcontextfunction/) που αντιπροσωπεύει τη συνάρτηση. Το [IXsltContextFunction](../../ixsltcontextfunction/) χρησιμοποιείται κατά την εκτέλεση για να ληφθεί η τιμή επιστροφής της συνάρτησης.

```cpp
virtual SharedPtr<IXsltContextFunction> System::Xml::Xsl::XsltContext::ResolveFunction(String prefix, String name, ArrayPtr<System::Xml::XPath::XPathResultType> ArgTypes)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Το πρόθεμα της συνάρτησης όπως εμφανίζεται στην [XPath](../../../system.xml.xpath/) έκφραση. |
| name | [String](../../../system/string/) | Το όνομα της συνάρτησης. |
| ArgTypes | [ArrayPtr](../../../system/arrayptr/)\<[System::Xml::XPath::XPathResultType](../../../system.xml.xpath/xpathresulttype/)\> | Ένας πίνακας τύπων ορισμάτων για τη συνάρτηση που επιλύεται. Αυτό σας επιτρέπει να επιλέξετε μεταξύ μεθόδων με το ίδιο όνομα (για παράδειγμα, υπερφορτωμένες μέθοδοι). |

### Τιμή Επιστροφής

Ένα [IXsltContextFunction](../../ixsltcontextfunction/) που αντιπροσωπεύει τη συνάρτηση.

## Δείτε επίσης

* Απαρίθμηση [XPathResultType](../../../system.xml.xpath/xpathresulttype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Ορισμός τύπου [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IXsltContextFunction](../../ixsltcontextfunction/)
* Κλάση [String](../../../system/string/)
* Κλάση [XsltContext](../)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)