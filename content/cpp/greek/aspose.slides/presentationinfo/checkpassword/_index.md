---
title: CheckPassword()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση που προστατεύεται με ανοιχτό κωδικό.
type: docs
weight: 53
url: /el/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) μέθοδος

Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση που προστατεύεται με ανοιχτό κωδικό.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης που θα ελεγχθεί. |

### Τιμή Επιστροφής

Επιστρέφει true εάν η παρουσίαση προστατεύεται με ανοιχτό κωδικό και ο κωδικός πρόσβασης είναι σωστός, και false διαφορετικά.

## Σχόλια

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false.

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [PresentationInfo](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)