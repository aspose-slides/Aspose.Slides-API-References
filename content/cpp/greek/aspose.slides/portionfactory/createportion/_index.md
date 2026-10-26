---
title: CreatePortion()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα κενό τμήμα κειμένου.
type: docs
weight: 1
url: /el/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() μέθοδος

Δημιουργεί ένα κενό τμήμα κειμένου.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```

### Τιμή επιστροφής

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) μέθοδος

Δημιουργεί ένα τμήμα κειμένου από την καθορισμένη συμβολοσειρά.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Συμβολοσειρά. |

### Τιμή επιστροφής

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) μέθοδος

Δημιουργεί ένα τμήμα με χρήση των δεδομένων του συγκεκριμένου τμήματος.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Ένα τμήμα προς χρήση. |

### Τιμή επιστροφής

[Portion](../../portion/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPortion](../../iportion/)
* Κλάση [PortionFactory](../)
* Κλάση [String](../../../system/string/)
* Ονοματοχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)