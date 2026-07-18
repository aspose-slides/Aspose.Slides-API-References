---
title: LastIndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναζήτηση υποσυμβολοσειράς προς τα πίσω.
type: docs
weight: 651
url: /el/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const method

Αναζήτηση υποσυμβολοσειράς προς τα πίσω.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή της συμβολοσειράς από την οποία ξεκινά η αναζήτηση. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει το μήκος της συμβολοσειράς.

## String::LastIndexOf(const String\&, System::StringComparison) const method

Αναζήτηση υποσυμβολοσειράς προς τα πίσω.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει το μήκος της συμβολοσειράς.

## String::LastIndexOf(const String\&, int, System::StringComparison) const method

Αναζήτηση υποσυμβολοσειράς προς τα πίσω.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή της συμβολοσειράς από την οποία ξεκινά η αναζήτηση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει το μήκος της συμβολοσειράς.

## String::LastIndexOf(const String\&, int, int, StringComparison) const method

Αναζήτηση υποσυμβολοσειράς προς τα πίσω.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή της συμβολοσειράς από την οποία ξεκινά η αναζήτηση. |
| count | int | Αριθμός χαρακτήρων για αναζήτηση. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει startIndex+count.

## String::LastIndexOf(char_t) const method

Αναζήτηση χαρακτήρα προς τα πίσω.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char_t | Χαρακτήρας προς αναζήτηση. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας θέσης χαρακτήρα ή -1 αν δεν βρεθεί.

## String::LastIndexOf(char_t, int32_t) const method

Αναζήτηση χαρακτήρα προς τα πίσω.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char_t | Χαρακτήρας προς αναζήτηση. |
| startIndex | **int32_t** | Δείκτης από τον οποίο ξεκινά η αναζήτηση. |

### Τιμή Επιστροφής

Δείκτης της τελευταίας θέσης χαρακτήρα από το startIndex ή -1 αν δεν βρεθεί.

## String::LastIndexOf(char_t, int32_t, int32_t) const method

Αναζήτηση χαρακτήρα προς τα πίσω.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char_t | Χαρακτήρας προς αναζήτηση. |
| startIndex | **int32_t** | Δείκτης από τον οποίο ξεκινά η αναζήτηση. |
| count | **int32_t** | Αριθμός χαρακτήρων για αναζήτηση |

### Τιμή Επιστροφής

Δείκτης της τελευταίας θέσης χαρακτήρα από το startIndex ή -1 αν δεν βρεθεί.

## Δείτε επίσης

* Enum [StringComparison](../../stringcomparison/)
* Κλάση [String](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)