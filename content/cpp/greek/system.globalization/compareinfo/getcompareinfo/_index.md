---
title: GetCompareInfo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποκτά το CompareInfo που σχετίζεται με την καθορισμένη κουλτούρα και χρησιμοποιεί μεθόδους σύγκρισης συμβολοσειρών στην καθορισμένη συναρμολόγηση.
type: docs
weight: 183
url: /el/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) μέθοδος

Λαμβάνει το [CompareInfo](../) που σχετίζεται με την καθορισμένη κουλτούρα και χρησιμοποιεί μεθόδους σύγκρισης συμβολοσειρών στην καθορισμένη συναρμολόγηση.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| culture | int | Αναγνωριστικό κουλτούρας (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Συλλογή που περιέχει μεθόδους σύγκρισης συμβολοσειρών. |

### Τιμή επιστροφής

[CompareInfo](../) αντικείμενο.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) μέθοδος

Λαμβάνει το [CompareInfo](../) που σχετίζεται με την καθορισμένη κουλτούρα και χρησιμοποιεί μεθόδους σύγκρισης συμβολοσειρών στην καθορισμένη συναρμολόγηση.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Όνομα κουλτούρας. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | Συλλογή που περιέχει μεθόδους σύγκρισης συμβολοσειρών. |

### Τιμή επιστροφής

[CompareInfo](../) αντικείμενο.

## CompareInfo::GetCompareInfo(int) μέθοδος

Λαμβάνει το [CompareInfo](../) που σχετίζεται με την καθορισμένη κουλτούρα.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| culture | int | Αναγνωριστικό κουλτούρας (LCID). |

### Τιμή επιστροφής

[CompareInfo](../) αντικείμενο.

## CompareInfo::GetCompareInfo(const String\&) μέθοδος

Λαμβάνει το [CompareInfo](../) που σχετίζεται με την καθορισμένη κουλτούρα.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Όνομα κουλτούρας. |

### Τιμή επιστροφής

[CompareInfo](../) αντικείμενο.

## Δείτε επίσης

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Assembly](../../../system.reflection/assembly/)
* Κλάση [CompareInfo](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Globalization](../../)
* Library [Aspose.Slides](../../../)