---
title: get_IsPasswordProtected()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει μια τιμή που υποδεικνύει εάν μια δεσμευμένη παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα.
type: docs
weight: 14
url: /el/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() μέθοδος


Λαμβάνει μια τιμή που υποδεικνύει εάν μια δεσμευμένη παρουσίαση προστατεύεται με κωδικό πρόσβασης για άνοιγμα.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Σχόλια



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Δείτε επίσης

* Κλάση [IPresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)