---
title: ResolveUri()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όταν αντικαθίσταται σε μια παράγωγη κλάση, επιλύει το απόλυτο URI από το βασικό και το σχετικό URI.
type: docs
weight: 27
url: /el/system.xml/xmlresolver/resolveuri/
---
## XmlResolver::ResolveUri(SharedPtr\<Uri\>, String) μέθοδος

Όταν αντικαθίσταται σε μια παράγωγη κλάση, επιλύει το απόλυτο URI από το βασικό και το σχετικό URI.

```cpp
virtual SharedPtr<Uri> System::Xml::XmlResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το βασικό URI που χρησιμοποιείται για την επίλυση του σχετικού URI. |
| relativeUri | [String](../../../system/string/) | Το URI προς επίλυση. Το URI μπορεί να είναι απόλυτο ή σχετικό. Εάν είναι απόλυτο, αυτή η τιμή αντικαθιστά ουσιαστικά την τιμή **baseUri**. Εάν είναι σχετικό, συνδυάζεται με το **baseUri** για να δημιουργήσει ένα απόλυτο URI. |

## Τιμή Επιστροφής

Το απόλυτο URI ή **nullptr** εάν το σχετικό URI δεν μπορεί να επιλυθεί.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlResolver](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)