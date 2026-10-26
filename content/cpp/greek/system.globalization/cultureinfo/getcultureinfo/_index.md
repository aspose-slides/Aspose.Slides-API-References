---
title: GetCultureInfo()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τον πολιτισμό βάσει του ονόματός του. Ίδιο με τη CreateSpecificCulture.
type: docs
weight: 586
url: /el/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) μέθοδος

Λαμβάνει τον πολιτισμό με βάση το όνομά του. Ίδιο με τη CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Προκαθορισμένο όνομα πολιτισμού ή όνομα υπάρχοντος αντικειμένου πολιτισμού. |

### Τιμή επιστροφής

Νέο δημιουργημένο αντικείμενο πολιτισμού.

## CultureInfo::GetCultureInfo(const String\&, const String\&) μέθοδος

Λαμβάνει τον πολιτισμό με βάση το όνομά του.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Όνομα πολιτισμού. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | Όνομα πολιτισμού που χρησιμοποιείται για αντικείμενα [TextInfo](../../textinfo/) και [CompareInfo](../../compareinfo/). |

### Τιμή επιστροφής

Αντικείμενο πολιτισμού.

## CultureInfo::GetCultureInfo(int32_t) μέθοδος

Λαμβάνει τον πολιτισμό με βάση το αναγνωριστικό.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| culture | **int32_t** | Αναγνωριστικό πολιτισμού. |

### Τιμή επιστροφής

Νέο δημιουργημένο αντικείμενο πολιτισμού.

## Δείτε επίσης

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [CultureInfo](../)
* Χώρος ονομάτων [System::Globalization](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)