---
title: CheckWriteProtection()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση που είναι προστατευμένη κατά τη γραφή.
type: docs
weight: 66
url: /el/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) μέθοδος

Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση που είναι προστατευμένη κατά τη γραφή.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης προς έλεγχο. |

### Τιμή Επιστροφής

True εάν η παρουσίαση είναι προστατευμένη κατά τη γραφή και ο κωδικός πρόσβασης είναι σωστός. False διαφορετικά.

## Παρατηρήσεις

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Πρέπει να ελέγξετε την ιδιότητα [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) πριν καλέσετε αυτή τη μέθοδο.
1. Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IPresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)