---
title: CheckPassword()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση που είναι προστατευμένη με ανοιχτό κωδικό πρόσβασης.
type: docs
weight: 53
url: /el/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) μέθοδος


Ελέγχει εάν ένας κωδικός πρόσβασης είναι σωστός για μια παρουσίαση που είναι προστατευμένη με ανοιχτό κωδικό πρόσβασης.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Ο κωδικός πρόσβασης προς έλεγχο. |

### Τιμή Επιστροφής

True εάν η παρουσίαση είναι προστατευμένη με ανοιχτό κωδικό πρόσβασης και ο κωδικός πρόσβασης είναι σωστός, και false αλλιώς.
## Παρατηρήσεις



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



Όταν ο κωδικός πρόσβασης είναι null ή κενός, αυτή η μέθοδος επιστρέφει false. 
## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IPresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)