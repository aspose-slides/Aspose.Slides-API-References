---
title: CompareDocument()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν παρατεθεί σε μια παράγωγη κλάση, συγκρίνει τους βασικούς Uniform Resource Identifiers (URIs) δύο εγγράφων με βάση τη σειρά με την οποία φορτώθηκαν τα έγγραφα από τον επεξεργαστή XSLT (δηλαδή, η κλάση XslTransform).
type: docs
weight: 53
url: /el/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) μέθοδος

Όταν παρακαμφθεί σε μια παράγωγη κλάση, συγκρίνει τους βασικούς Αναγνωριστές Καθολικού Πόρου (URIs) δύο εγγράφων με βάση τη σειρά που φορτώθηκαν από τον επεξεργαστή XSLT (δηλαδή, η [XslTransform](../../xsltransform/) κλάση).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | Το βασικό URI του πρώτου εγγράφου προς σύγκριση. |
| nextbaseUri | [String](../../../system/string/) | Το βασικό URI του δεύτερου εγγράφου προς σύγκριση. |

### Τιμή Επιστροφής

Μια ακέραια τιμή που περιγράφει τη σχετική σειρά των δύο βασικών URIs: -1 εάν το **baseUri** εμφανίζεται πριν το **nextbaseUri**· 0 εάν τα δύο URIs είναι ταυτόσημα· και 1 εάν το **baseUri** εμφανίζεται μετά το **nextbaseUri**.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [XsltContext](../)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)