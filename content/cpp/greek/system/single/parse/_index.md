---
title: Parse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας.
type: docs
weight: 1
url: /el/system/single/parse/
---
## Single::Parse(const String\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας.

```cpp
static float System::Single::Parse(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής μονής ακρίβειας ίση με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής μονής ακρίβειας ίση με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Η συμβολοσειρά προς μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός τιμών της απαρίθμησης NumberStyles με χρήση bitwise, που καθορίζει το επιτρεπόμενο στυλ της αναπαράστασης αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφοποίησης της συμβολοσειράς. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής μονής ακρίβειας ίση με τον αριθμό που αντιπροσωπεύεται από τη συγκεκριμένη συμβολοσειρά.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)