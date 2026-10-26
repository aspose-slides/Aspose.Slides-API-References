---
title: Split()
second_title: Αναφορά API του Aspose.Slides για C++
description: Διαχωρίζει τη συμβολοσειρά κατά χαρακτήρα.
type: docs
weight: 768
url: /el/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά κατά χαρακτήρα.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | char_t | Χαρακτήρας με τον οποίο θα διαχωριστεί η συμβολοσειρά. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(char_t, int32_t, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά κατά χαρακτήρα.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | char_t | Χαρακτήρας με τον οποίο θα διαχωριστεί η συμβολοσειρά. |
| count | **int32_t** | Το μέγιστο πλήθος υποσυμβολοσειρών που θα επιστραφεί. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(char_t, char_t, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά κατά έναν από δύο χαρακτήρες.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorA | char_t | Πρώτος χαρακτήρας με τον οποίο θα διαχωριστεί η συμβολοσειρά. |
| separatorB | char_t | Δεύτερος χαρακτήρας με τον οποίο θα διαχωριστεί η συμβολοσειρά. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση έναν από τους καθορισμένους χαρακτήρες.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) των χαρακτήρων διαχωρισμού. Εάν είναι κενό, οποιοσδήποτε λευκός χαρακτήρας θεωρείται διαχωριστής. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση έναν από τους καθορισμένους χαρακτήρες.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) των χαρακτήρων διαχωρισμού. Εάν είναι κενό, οποιοσδήποτε λευκός χαρακτήρας θεωρείται διαχωριστής. |
| count | **int32_t** | Το μέγιστο πλήθος υποσυμβολοσειρών που θα επιστραφεί. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const String\&, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση την υποσυμβολοσειρά.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | Υποσυμβολοσειρά που λειτουργεί ως διαχωριστής. Εάν είναι κενό, ο λευκός χαρακτήρας λειτουργεί ως διαχωριστής. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const String\&, int, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση την υποσυμβολοσειρά.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separator | const [String](../)\& | Υποσυμβολοσειρά που λειτουργεί ως διαχωριστής. Εάν είναι κενό, ο λευκός χαρακτήρας λειτουργεί ως διαχωριστής. |
| count | int | Μέγιστος αριθμός στοιχείων στο πίνακα διαχωρισμών. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση την υποσυμβολοσειρά.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) των συμβολοσειρών διαχωρισμού. Εάν είναι κενό, δεν γίνεται διαχωρισμός. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const μέθοδος

Διαχωρίζει τη συμβολοσειρά με βάση την υποσυμβολοσειρά. Επί του παρόντος, υποστηρίζεται μόνο πίνακας διαχωριστών με μηδέν ή ένα στοιχεία.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) των συμβολοσειρών διαχωρισμού. Εάν είναι κενό, δεν γίνεται διαχωρισμός. |
| count | int | Μέγιστος αριθμός στοιχείων στο πίνακα διαχωρισμών. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Επιλογές διαχωρισμού. |

### Τιμή επιστροφής

[Array](../../array/) από υποσυμβολοσειρές.

## Δείτε επίσης

* Απαρίθμηση [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Κλάση [String](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)