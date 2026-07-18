---
title: ResolveUri()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιλύει το απόλυτο URI από το βασικό και το σχετικό URI.
type: docs
weight: 40
url: /el/system.xml.resolvers/xmlpreloadedresolver/resolveuri/
---
## XmlPreloadedResolver::ResolveUri(SharedPtr\<Uri\>, String) μέθοδος


Επιλύει το απόλυτο URI από τα βασικά και τα σχετικά URIs.

```cpp
SharedPtr<Uri> System::Xml::Resolvers::XmlPreloadedResolver::ResolveUri(SharedPtr<Uri> baseUri, String relativeUri) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| baseUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το βασικό URI που χρησιμοποιείται για την επίλυση του σχετικού URI. |
| relativeUri | [String](../../../system/string/) | Το URI που πρέπει να επιλυθεί. Το URI μπορεί να είναι απόλυτο ή σχετικό. Εάν είναι απόλυτο, αυτή η τιμή αντικαθιστά ουσιαστικά την τιμή **baseUri**. Εάν είναι σχετικό, συνδυάζεται με το **baseUri** για να δημιουργήσει ένα απόλυτο URI. |

### Τιμή Επιστροφής

Το [Uri](../../../system/uri/) που αντιπροσωπεύει το απόλυτο URI ή **nullptr** εάν το σχετικό URI δεν μπορεί να επιλυθεί.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [XmlPreloadedResolver](../)
* Χώρος ονομάτων [System::Xml::Resolvers](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)