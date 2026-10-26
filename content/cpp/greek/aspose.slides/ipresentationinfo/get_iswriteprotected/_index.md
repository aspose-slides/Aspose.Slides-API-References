---
title: get_IsWriteProtected()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά μια τιμή που υποδεικνύει εάν μια συνδεδεμένη παρουσίαση είναι προστατευμένη κατά την εγγραφή.
type: docs
weight: 27
url: /el/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() method

Ανακτά μια τιμή που υποδεικνύει αν μια συνδεδεμένη παρουσίαση είναι προστατευμένη κατά την εγγραφή.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Παρατηρήσεις



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Εάν η παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για άνοιγμα, η τιμή της ιδιότητας είναι NotDefined. Δείτε την [NullableBool](../../nullablebool/) απαρίθμηση. 
## Δείτε επίσης

* Απαρίθμηση [NullableBool](../../nullablebool/)
* Κλάση [IPresentationInfo](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)