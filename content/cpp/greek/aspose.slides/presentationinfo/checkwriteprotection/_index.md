---
title: CheckWriteProtection()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει εάν ο κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση με προστασία εγγραφής.
type: docs
weight: 66
url: /el/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) μέθοδος

Ελέγχει αν ο κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση με προστασία εγγραφής.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης για έλεγχο. |

### Τιμή Επιστροφής

True αν η παρουσίαση είναι write protected και ο κωδικός πρόσβασης είναι σωστός. False διαφορετικά.

## Παρατηρήσεις

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Πρέπει να ελέγξετε την ιδιότητα [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) πριν καλέσετε αυτή τη μέθοδο.
1. Όταν password είναι null ή empty, αυτή η μέθοδος επιστρέφει false.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [PresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)