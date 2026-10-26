---
title: Parse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αλφαριθμητική αναπαράσταση ενός αριθμού στον ισοδύναμο 64-bit ακέραιο χωρίς πρόσημο.
type: docs
weight: 1
url: /el/system/uint64/parse/
---
## UInt64::Parse(const String\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αλφαριθμητική αναπαράσταση ενός αριθμού στον ισοδύναμο 64-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |

### Τιμή Επιστροφής

Ο 64-bit ακέραιος χωρίς πρόσημο ισοδύναμος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αλφαριθμητική αναπαράσταση ενός αριθμού στον ισοδύναμο 64-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 64-bit ακέραιος χωρίς πρόσημο ισοδύναμος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αλφαριθμητική αναπαράσταση ενός αριθμού στον ισοδύναμο 64-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Συνδυασμός bitwise τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της αλφαριθμητικής αναπαράστασης του αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 64-bit ακέραιος χωρίς πρόσημο ισοδύναμος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος 




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος 




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Δομή [UInt64](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)