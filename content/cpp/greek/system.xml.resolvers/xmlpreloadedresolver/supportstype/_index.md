---
title: SupportsType()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν ο resolver υποστηρίζει άλλους Types εκτός του Stream.
type: docs
weight: 66
url: /el/system.xml.resolvers/xmlpreloadedresolver/supportstype/
---
## XmlPreloadedResolver::SupportsType(SharedPtr\<Uri\>, const TypeInfo\&) μέθοδος

Καθορίζει εάν ο resolver υποστηρίζει άλλους Type εκτός του Stream.

```cpp
bool System::Xml::Resolvers::XmlPreloadedResolver::SupportsType(SharedPtr<Uri> absoluteUri, const TypeInfo &type) override
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| absoluteUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Το απόλυτο URI για έλεγχο. |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Ο Type που θα επιστραφεί. |

### Τιμή Επιστροφής

**true** εάν ο Type υποστηρίζεται· αλλιώς, **false**.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Uri](../../../system/uri/)
* Κλάση [TypeInfo](../../../system/typeinfo/)
* Κλάση [XmlPreloadedResolver](../)
* Χώρος ονομάτων [System::Xml::Resolvers](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)