---
title: CheckWriteProtection()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση.
type: docs
weight: 157
url: /el/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) μέθοδος

Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης για έλεγχο. |

### Τιμή Επιστροφής

True εάν ο κωδικός πρόσβασης είναι έγκυρος· διαφορετικά, false.

## Σχόλια

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Θα πρέπει να ελέγξετε την [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) ιδιότητα πριν καλέσετε αυτή η μέθοδο.
1. Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)