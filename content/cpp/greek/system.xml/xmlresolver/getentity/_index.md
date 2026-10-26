---
title: GetEntity()
second_title: Aspose.Slides για την αναφορά API της C++
description: Όταν επανακαθορίζεται σε μια κληρονομημένη κλάση, αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.
type: docs
weight: 14
url: /el/system.xml/xmlresolver/getentity/
---
## XmlResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) μέθοδος

Όταν επανακαθορίζεται σε μια κληρονομημένη κλάση, αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

```cpp
virtual SharedPtr<Object> System::Xml::XmlResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI που επιστρέφεται από την κλήση [XmlResolver::ResolveUri(SharedPtr<Uri>, String)](../resolveuri/). |
| role | [String](../../../system/string/) | Προς το παρόν δεν χρησιμοποιείται. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος του αντικειμένου που θα επιστραφεί. Η τρέχουσα έκδοση επιστρέφει μόνο αντικείμενα Stream. |

### Τιμή Επιστροφής

Ένα αντικείμενο ροής ή **nullptr** εάν έχει καθοριστεί τύπος διαφορετικός από ροή.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [String](../../../system/string/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [XmlResolver](../)
* Χώρος ονομάτων [System::Xml](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)