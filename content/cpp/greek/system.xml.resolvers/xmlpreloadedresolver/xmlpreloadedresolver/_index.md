---
title: XmlPreloadedResolver()
second_title: Αναφορά API Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης XmlPreloadedResolver.
type: docs
weight: 27
url: /el/system.xml.resolvers/xmlpreloadedresolver/xmlpreloadedresolver/
---
## XmlPreloadedResolver::XmlPreloadedResolver() Κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlPreloadedResolver](../).

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver()
```

## XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds) Κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlPreloadedResolver](../) με τα συγκεκριμένα προφορτωμένα γνωστά DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(XmlKnownDtds preloadedDtds)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Τα γνωστά DTD που πρέπει να προσυμπληρωθούν στην κρυφή μνήμη. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&) Κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlPreloadedResolver](../) με τον καθορισμένο εναλλακτικό resolver.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Ο [XmlResolver](../../../system.xml/xmlresolver/) ή ο δικός σας resolver. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds) Κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlPreloadedResolver](../) με τον καθορισμένο εναλλακτικό resolver και προφορτωμένα γνωστά DTD.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Ο [XmlResolver](../../../system.xml/xmlresolver/) ή ο δικός σας resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Τα γνωστά DTD που πρέπει να προσυμπληρωθούν στην κρυφή μνήμη. |

## XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr\<XmlResolver\>\&, XmlKnownDtds, const SharedPtr\<Collections::Generic::IEqualityComparer\<SharedPtr\<Uri\>\>\>\&) Κατασκευαστής

Αρχικοποιεί μια νέα παρουσία της κλάσης [XmlPreloadedResolver](../) με τον καθορισμένο εναλλακτικό resolver, προφορτωμένα γνωστά DTD και σύγκριση ισότητας URI.

```cpp
System::Xml::Resolvers::XmlPreloadedResolver::XmlPreloadedResolver(const SharedPtr<XmlResolver> &fallbackResolver, XmlKnownDtds preloadedDtds, const SharedPtr<Collections::Generic::IEqualityComparer<SharedPtr<Uri>>> &uriComparer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fallbackResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Ο [XmlResolver](../../../system.xml/xmlresolver/) ή ο δικός σας resolver. |
| preloadedDtds | [XmlKnownDtds](../../xmlknowndtds/) | Τα γνωστά DTD που πρέπει να προσυμπληρωθούν στην κρυφή μνήμη. |
| uriComparer | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\>\>\>\& | Η υλοποίηση της διεπαφής IEqualityComparer που θα χρησιμοποιηθεί κατά τη σύγκριση URI. |

## Δείτε επίσης

* Enum [XmlKnownDtds](../../xmlknowndtds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlPreloadedResolver](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IEqualityComparer](../../../system.collections.generic/iequalitycomparer/)
* Class [Uri](../../../system/uri/)
* Namespace [System::Xml::Resolvers](../../)
* Library [Aspose.Slides](../../../)