---
title: get_IsWriteProtected()
second_title: Aspose.Slides για C++ API Reference
description: Λαμβάνει μια τιμή που υποδεικνύει εάν μια συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή.
type: docs
weight: 27
url: /el/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() μέθοδος

Λαμβάνει μια τιμή που υποδεικνύει εάν μια συνδεδεμένη παρουσίαση είναι προστατευμένη από εγγραφή.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Παρατηρήσεις


```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα, η τιμή της ιδιότητας είναι ίση με NotDefined. 
## Δείτε επίσης

* Απαρίθμηση [NullableBool](../../nullablebool/)
* Κλάση [PresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)