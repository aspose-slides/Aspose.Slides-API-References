---
title: CheckWriteProtection()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση.
type: docs
weight: 157
url: /el/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) μέθοδος


Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό για τροποποίηση.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός για έλεγχο. |

### Τιμή Επιστροφής

True if the password is valid; otherwise, false.
## Σχόλια



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Θα πρέπει να ελέγξετε την ιδιότητα [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) πριν καλέσετε αυτή τη μέθοδο.
1. Όταν ο κωδικός είναι null ή κενός, αυτή η μέθοδος επιστρέφει false.


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [ProtectionManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)