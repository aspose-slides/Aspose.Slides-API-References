---
title: GetPresentationInfo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί νέο αντικείμενο PresentationInfo από αρχείο και συνδέει την παρουσίαση με αυτό.
type: docs
weight: 27
url: /el/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) μέθοδος

Δημιουργεί νέο αντικείμενο [PresentationInfo](../../presentationinfo/) από αρχείο και συνδέει την παρουσίαση σε αυτό.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) αρχείο. |

### Τιμή Επιστροφής

[Presentation](../../presentation/) πληροφορίες δεσμευμένες στην παρουσίαση.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί νέο αντικείμενο [PresentationInfo](../../presentationinfo/) από ροή και συνδέει την παρουσίαση σε αυτό. Λαμβάνει πληροφορίες για την παρουσίαση στη συγκεκριμένη ροή.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) ροή. |

### Τιμή Επιστροφής

[Presentation](../../presentation/) πληροφορίες δεσμευμένες στην παρουσίαση.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPresentationInfo](../../ipresentationinfo/)
* Κλάση [String](../../../system/string/)
* Κλάση [PresentationFactory](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)