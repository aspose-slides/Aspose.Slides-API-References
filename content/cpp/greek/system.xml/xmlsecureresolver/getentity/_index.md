---
title: GetEntity()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.
type: docs
weight: 27
url: /el/system.xml/xmlsecureresolver/getentity/
---
## XmlSecureResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) μέθοδος

Χαρτογραφεί ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

```cpp
SharedPtr<Object> System::Xml::XmlSecureResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI που επιστρέφεται από την κλήση [XmlSecureResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Προς το παρόν δεν χρησιμοποιείται. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος του αντικειμένου που θα επιστραφεί. Η τρέχουσα έκδοση επιστρέφει μόνο αντικείμενα Stream. |

### Τιμή Επιστροφής

Η ροή που επιστρέφεται με την κλήση του **GetEntity** στο υποκείμενο [XmlResolver](../../xmlresolver/). Αν καθοριστεί τύπος διαφορετικός από Stream, η μέθοδος επιστρέφει **nullptr**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [XmlSecureResolver](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)