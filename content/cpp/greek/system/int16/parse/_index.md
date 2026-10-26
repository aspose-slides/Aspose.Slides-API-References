---
title: Parse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 16-bit υπογεγραμμένο ακέραιο.
type: docs
weight: 1
url: /el/system/int16/parse/
---
## Int16::Parse(const String\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 16-bit υπογεγραμμένο ακέραιο.

```cpp
static int16_t System::Int16::Parse(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή. |

### Τιμή επιστροφής

Ο 16-bit υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 16-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή επιστροφής

Ο 16-bit υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμο 16-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά για μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός bitwise τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της αναπαράστασης της συμβολοσειράς ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή επιστροφής

Ο 16-bit υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Απαριθμήσιμο [NumberStyles](../../../system.globalization/numberstyles/)
* Τύπος ορισμού [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Int16](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)