---
title: Double
second_title: Aspose.Slides για Αναφορά API C++
description: Περιέχει μεθόδους για εργασία με αριθμό κινητής υποδιαστολής διπλής ακρίβειας.
type: docs
weight: 1548
url: /el/system/double/
---
## Δομή Double

Περιέχει μεθόδους για εργασία με αριθμό κινητής υποδιαστολής διπλής ακρίβειας.

```cpp
class Double
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχη τιμή κινητής υποδιαστολής διπλής ακρίβειας. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχη τιμή κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχη τιμή κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχη τιμή κινητής υποδιαστολής διπλής ακρίβειας. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε αντίστοιχη τιμή κινητής υποδιαστολής διπλής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Πεδία

| Πεδία | Περιγραφή |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Η μικρότερη θετική τιμή που είναι μεγαλύτερη του μηδενός. |
| static constexpr [MaxValue](./maxvalue/) | Η μεγαλύτερη δυνατή τιμή. |
| static constexpr [MinValue](./minvalue/) | Η μικρότερη δυνατή τιμή. |
| static constexpr [NaN](./nan/) | Τιμή που δεν είναι αριθμός. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Αρνητικό άπειρο. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Θετικό άπειρο. |

## Δείτε επίσης

* Namespace [System](../)
* Library [Aspose.Slides](../../)