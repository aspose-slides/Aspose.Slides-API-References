---
title: CreatePortion()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια κενή περιοχή κειμένου.
type: docs
weight: 1
url: /el/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() μέθοδος

Δημιουργεί μια κενή περιοχή κειμένου.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```

### Τιμή Επιστροφής

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) μέθοδος

Δημιουργεί μια περιοχή κειμένου από την καθορισμένη συμβολοσειρά.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | Συμβολοσειρά. |

### Τιμή Επιστροφής

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) μέθοδος

Δημιουργεί μια περιοχή χρησιμοποιώντας δεδομένα καθορισμένης περιοχής.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | Μια περιοχή προς χρήση. |

### Τιμή Επιστροφής

[Portion](../../portion/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPortion](../../iportion/)
* Κλάση [IPortionFactory](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)