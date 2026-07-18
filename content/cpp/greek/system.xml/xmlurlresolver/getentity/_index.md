---
title: GetEntity()
second_title: Αναφορά API του Aspose.Slides για C++
description: Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.
type: docs
weight: 53
url: /el/system.xml/xmlurlresolver/getentity/
---
## XmlUrlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

```cpp
SharedPtr<Object> System::Xml::XmlUrlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI που επιστρέφεται από την κλήση [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../../xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Προς το παρόν δεν χρησιμοποιείται. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος του αντικειμένου που θα επιστραφεί. Η τρέχουσα υλοποίηση επιστρέφει μόνο αντικείμενα Stream. |

### Τιμή Επιστροφής

Ένα αντικείμενο ροής ή **nullptr** εάν καθοριστεί τύπος διαφορετικός από stream.

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [XmlUrlResolver](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)