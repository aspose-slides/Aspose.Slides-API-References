---
title: UInt32
second_title: Aspose.Slides για την Αναφορά API C++
description: Περιέχει μεθόδους για εργασία με τον μη υπογεγραμμένο 32-bit ακέραιο.
type: docs
weight: 1951
url: /el/system/uint32/
---
## UInt32 δομή

Περιέχει μεθόδους για εργασία με τον μη-υπογεγραμμένο 32-bit ακέραιο.

```cpp
class UInt32
```

## Methods

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει το συγκεκριμένο κείμενο που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει το συγκεκριμένο κείμενο που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει το συγκεκριμένο κείμενο που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Μετατρέπει το συγκεκριμένο κείμενο που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Μετατρέπει το συγκεκριμένο κείμενο που περιέχει την αναπαράσταση αριθμού σε ισοδύναμο 32-bit ακέραιο χωρίς πρόσημο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Fields

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Μεγαλύτερη δυνατή τιμή. |
| static constexpr [MinValue](./minvalue/) | Μικρότερη δυνατή τιμή. |

## See Also

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)