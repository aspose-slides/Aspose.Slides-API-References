---
title: IndexOf()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αναζήτηση υποσυμβολοσειράς προς εμπρός.
type: docs
weight: 625
url: /el/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const μέθοδος


Αναζήτηση υποσυμβολοσειράς προς εμπρός.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή επιστροφής

Δείκτης της πρώτης βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει 0.

## String::IndexOf(char_t, int) const μέθοδος


Αναζήτηση χαρακτήρα προς εμπρός.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Χαρακτήρας προς αναζήτηση. |
| startIndex | int | Δείκτης έναρξης αναζήτησης. |

### Τιμή επιστροφής

Δείκτης της πρώτης θέσης χαρακτήρα μετά το startIndex ή -1 αν δεν βρεθεί.

## String::IndexOf(char_t, int, int) const μέθοδος


Αναζήτηση χαρακτήρα προς εμπρός σε υποσυμβολοσειρά.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Χαρακτήρας προς αναζήτηση. |
| startIndex | int | Δείκτης έναρξης αναζήτησης. |
| count | int | Αριθμός χαρακτήρων προς εξέταση. |

### Τιμή επιστροφής

Δείκτης της πρώτης θέσης χαρακτήρα μετά το startIndex ή -1 αν δεν βρεθεί.

## String::IndexOf(const String\&, int) const μέθοδος


Αναζήτηση υποσυμβολοσειράς προς εμπρός.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή συμβολοσειράς για έναρξη αναζήτησης. |

### Τιμή επιστροφής

Δείκτης της πρώτης βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const μέθοδος


Αναζήτηση υποσυμβολοσειράς προς εμπρός.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή συμβολοσειράς για έναρξη αναζήτησης. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή επιστροφής

Δείκτης της πρώτης βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const μέθοδος


Αναζήτηση υποσυμβολοσειράς προς εμπρός.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή συμβολοσειράς για έναρξη αναζήτησης. |
| count | int | Αριθμός χαρακτήρων προς εξέταση. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) λειτουργία. |

### Τιμή επιστροφής

Δείκτης της πρώτης βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει startIndex.

## String::IndexOf(const String\&, int, int) const μέθοδος


Αναζήτηση υποσυμβολοσειράς προς εμπρός.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Υποσυμβολοσειρά προς αναζήτηση. |
| startIndex | int | Θέση στη πηγή συμβολοσειράς για έναρξη αναζήτησης. |
| count | int | Αριθμός χαρακτήρων προς εξέταση. |

### Τιμή επιστροφής

Δείκτης της πρώτης βρεθείσας υποσυμβολοσειράς ή -1 αν δεν βρεθεί. Για κενή συμβολοσειρά αναζήτησης, πάντα επιστρέφει startIndex.

## Δείτε επίσης

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)