---
title: GetEntity()
second_title: Αναφορά API Aspose.Slides για C++
description: Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.
type: docs
weight: 53
url: /el/system.xml.resolvers/xmlpreloadedresolver/getentity/
---
## XmlPreloadedResolver::GetEntity(SharedPtr\<Uri\>, String, const TypeInfo\&) method

Αντιστοιχίζει ένα URI σε ένα αντικείμενο που περιέχει τον πραγματικό πόρο.

```cpp
SharedPtr<Object> System::Xml::Resolvers::XmlPreloadedResolver::GetEntity(SharedPtr<Uri> absoluteUri, String role, const TypeInfo &ofObjectToReturn) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το URI που επιστρέφεται από την κλήση [XmlResolver::ResolveUri(SharedPtr<Uri>,String)](../../../system.xml/xmlresolver/resolveuri/). |
| role | [String](../../../system/string/) | Προς το παρόν δεν χρησιμοποιείται. |
| ofObjectToReturn | const [TypeInfo](../../../system/typeinfo/)\& | Ο τύπος του αντικειμένου που θα επιστραφεί. Το [XmlPreloadedResolver](../) υποστηρίζει αντικείμενα Stream και αντικείμενα TextReader για URIs που προστέθηκαν ως [String](../../../system/string/). Αν ο ζητούμενος τύπος δεν υποστηρίζεται από τον resolver, θα ριχθεί μια εξαίρεση. Χρησιμοποιήστε τη μέθοδο XmlPreloadedResolver::SupportsType(SharedPtr<Uri>,TypeInfo) για να προσδιορίσετε εάν ένας συγκεκριμένος **Type** υποστηρίζεται από αυτόν τον resolver. |

### Τιμή Επιστροφής

Ένα αντικείμενο Stream ή TextReader που αντιστοιχεί στην πραγματική πηγή.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [XmlPreloadedResolver](../)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)