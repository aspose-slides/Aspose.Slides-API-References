---
title: get_IsPasswordProtected()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Λαμβάνει μια τιμή η οποία υποδεικνύει εάν μια συνδεδεμένη παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα.
type: docs
weight: 14
url: /el/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() μέθοδος

Λαμβάνει μια τιμή που υποδεικνύει εάν μια συνδεδεμένη παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Παρατηρήσεις



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Δείτε επίσης

* Κλάση [PresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)