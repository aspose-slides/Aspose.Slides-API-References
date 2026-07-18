---
title: Single
second_title: Αναφορά API Aspose.Slides για C++
description: Περιέχει μεθόδους για εργασία με αριθμούς κινητής υποδιαστολής μονής ακρίβειας.
type: docs
weight: 1873
url: /el/system/single/
---
## Μονή δομή

Περιέχει μεθόδους για εργασία με αριθμούς κινητής υποδιαστολής μονής ακρίβειας.

```cpp
class Single
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση ενός αριθμού σε ισοδύναμη τιμή κινητής υποδιαστολής μονής ακρίβειας χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Η μικρότερη θετική τιμή που είναι μεγαλύτερη του μηδενός. |
| static constexpr [MaxValue](./maxvalue/) | Η μεγαλύτερη δυνατή τιμή. |
| static constexpr [MinValue](./minvalue/) | Η μικρότερη δυνατή τιμή. |
| static constexpr [NaN](./nan/) | Τιμή που δεν είναι αριθμός. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Αρνητικό άπειρο. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Θετικό άπειρο. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)