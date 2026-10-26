---
title: ResolveVariable()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Όταν αντικαθίσταται σε μια κληρονομημένη κλάση, επιλύει μια αναφορά μεταβλητής και επιστρέφει ένα IXsltContextVariable που αντιπροσωπεύει τη μεταβλητή.
type: docs
weight: 14
url: /el/system.xml.xsl/xsltcontext/resolvevariable/
---
## XsltContext::ResolveVariable(String, String) μέθοδος

Όταν αντικαθίσταται σε μια κληρονομημένη κλάση, επιλύει μια αναφορά μεταβλητής και επιστρέφει ένα [IXsltContextVariable](../../ixsltcontextvariable/) που αντιπροσωπεύει τη μεταβλητή.

```cpp
virtual SharedPtr<IXsltContextVariable> System::Xml::Xsl::XsltContext::ResolveVariable(String prefix, String name)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Το πρόθεμα της μεταβλητής όπως εμφανίζεται στην έκφραση [XPath](../../../system.xml.xpath/). |
| name | [String](../../../system/string/) | Το όνομα της μεταβλητής. |

### Τιμή Επιστροφής

Ένα [IXsltContextVariable](../../ixsltcontextvariable/) που αντιπροσωπεύει τη μεταβλητή κατά την εκτέλεση.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IXsltContextVariable](../../ixsltcontextvariable/)
* Κλάση [String](../../../system/string/)
* Κλάση [XsltContext](../)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)