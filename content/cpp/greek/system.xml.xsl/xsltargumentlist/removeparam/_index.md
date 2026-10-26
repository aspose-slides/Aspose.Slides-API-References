---
title: RemoveParam()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Αφαιρεί την παράμετρο από το XsltArgumentList.
type: docs
weight: 66
url: /el/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) μέθοδος


Αφαιρεί την παράμετρο από το [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Το όνομα της παραμέτρου που θα αφαιρεθεί. [XsltArgumentList](../) δεν ελέγχει αν το παρεχόμενο όνομα είναι έγκυρο τοπικό όνομα· ωστόσο, το όνομα δεν μπορεί να είναι **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | Το URI του χώρου ονομάτων της παραμέτρου που θα αφαιρεθεί. |

### Τιμή Επιστροφής

Το αντικείμενο παραμέτρου ή **nullptr** εάν δεν βρέθηκε.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Τάξη [Object](../../../system/object/)
* Τάξη [String](../../../system/string/)
* Τάξη [XsltArgumentList](../)
* Χώρος ονομάτων [System::Xml::Xsl](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)