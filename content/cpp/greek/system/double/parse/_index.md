---
title: Parse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση κειμένου ενός αριθμού στην ισοδύναμη τιμή κινητής υποδιαστολής διπλής ακρίβειας.
type: docs
weight: 1
url: /el/system/double/parse/
---
## Double::Parse(const String\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση κειμένου ενός αριθμού στην ισοδύναμη τιμή κινητής υποδιαστολής διπλής ακρίβειας.

```cpp
static double System::Double::Parse(const String &value)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το κείμενο για μετατροπή. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής διπλής ακρίβειας που ισούται με τον αριθμό που αναπαρίσταται από το καθορισμένο κείμενο.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση κειμένου ενός αριθμού στην ισοδύναμη τιμή κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το κείμενο για μετατροπή. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφής του κειμένου. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής διπλής ακρίβειας που ισούται με τον αριθμό που αναπαρίσταται από το καθορισμένο κείμενο.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) μέθοδος




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) μέθοδος

Μετατρέπει το καθορισμένο κείμενο που περιέχει την αναπαράσταση κειμένου ενός αριθμού στην ισοδύναμη τιμή κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../string/)\& | Το κείμενο για μετατροπή. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας δυαδικός συνδυασμός τιμών του enum NumberStyles που καθορίζει το επιτρεπόμενο στυλ της αναπαράστασης κειμένου ενός αριθμού. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Ένας δείκτης σε αντικείμενο που περιέχει τις πληροφορίες μορφής του κειμένου. |

### Τιμή Επιστροφής

Η τιμή κινητής υποδιαστολής διπλής ακρίβειας που ισούται με τον αριθμό που αναπαρίσταται από το καθορισμένο κείμενο.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) μέθοδος




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) μέθοδος




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) μέθοδος




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Δείτε επίσης

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)