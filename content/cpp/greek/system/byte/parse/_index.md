---
title: Parse()
second_title: Αναφορά API του Aspose.Slides για C++
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον αντίστοιχο 8-bit ακέραιο χωρίς πρόσημο.
type: docs
weight: 1
url: /el/system/byte/parse/
---
## Byte::Parse(const String\&) μέθοδος


Μετατρέπει το καθορισμένο συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον αντίστοιχο 8-bit ακέραιο χωρίς πρόσημο.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |

### Τιμή Επιστροφής

Ο 8-bit ακέραιος χωρίς πρόσημο ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος


Μετατρέπει το καθορισμένο συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον αντίστοιχο 8-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 8-bit ακέραιος χωρίς πρόσημο ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος


Μετατρέπει το καθορισμένο συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον αντίστοιχο 8-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός bitwise τιμών του enum NumberStyles που καθορίζει το επιτρεπτό στυλ της αναπαράστασης κειμένου ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Ο 8-bit ακέραιος χωρίς πρόσημο ίσος με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος 




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος 




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Απαρίθμηση [NumberStyles](../../../system.globalization/numberstyles/)
* Ορισμός τύπου [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Byte](../)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [CultureInfo](../../../system.globalization/cultureinfo/)
* Κλάση [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)