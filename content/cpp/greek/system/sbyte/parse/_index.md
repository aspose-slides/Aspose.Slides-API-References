---
title: Parse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση του αριθμού σε μορφή συμβολοσειράς στον ισοδύναμο 8-bit με πρόσημο ακέραιο.
type: docs
weight: 1
url: /el/system/sbyte/parse/
---
## SByte::Parse(const String\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση του αριθμού σε μορφή συμβολοσειράς στον ισοδύναμο 8-bit με πρόσημο ακέραιο.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |

### Τιμή Επιστροφής

Ο 8-bit με πρόσημο ακέραιο ίσος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση του αριθμού σε μορφή συμβολοσειράς στον ισοδύναμο 8-bit με πρόσημο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες διαμόρφωσης.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Δείκτης προς ένα αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 8-bit με πρόσημο ακέραιο ίσος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση του αριθμού σε μορφή συμβολοσειράς στον ισοδύναμο 8-bit με πρόσημο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες διαμόρφωσης και το στυλ αριθμού.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Μια σύνθεση με bitwise των τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της αναπαράστασης του αριθμού σε μορφή συμβολοσειράς. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Δείκτης προς ένα αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 8-bit με πρόσημο ακέραιο ίσος με τον αριθμό που αναπαριστά η συγκεκριμένη συμβολοσειρά.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος




```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)