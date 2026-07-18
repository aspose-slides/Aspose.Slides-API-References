---
title: Parse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση συμβολοσειράς ενός αριθμού στον ισοδύναμο 16-bit μη υπογεγραμμένο ακέραιο.
type: docs
weight: 1
url: /el/system/uint16/parse/
---
## UInt16::Parse(const String\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση συμβολοσειράς ενός αριθμού στον ισοδύναμο 16-bit μη υπογεγραμμένο ακέραιο.

```cpp
static uint16_t System::UInt16::Parse(const String &value)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |

### Τιμή Επιστροφής

Ο 16-bit μη υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύει η καθορισμένη συμβολοσειρά.

## UInt16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση συμβολοσειράς ενός αριθμού στον ισοδύναμο 16-bit μη υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε ένα αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 16-bit μη υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύει η καθορισμένη συμβολοσειρά.

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, std::nullptr_t)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση συμβολοσειράς ενός αριθμού στον ισοδύναμο 16-bit μη υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός τιμών του enum NumberStyles με τελεία bit που καθορίζει το επιτρεπόμενο στυλ της αναπαράστασης της συμβολοσειράς ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε ένα αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 16-bit μη υπογεγραμμένος ακέραιος ίσος με τον αριθμό που αντιπροσωπεύει η καθορισμένη συμβολοσειρά.

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος




```cpp
static uint16_t System::UInt16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)