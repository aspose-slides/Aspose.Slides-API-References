---
title: Int32
second_title: Aspose.Slides για C++ Αναφορά API
description: Περιέχει μεθόδους για εργασία με τον 32-bit ακέραιο.
type: docs
weight: 1028
url: /el/system/int32/
---
## Int32 κλάση

Περιέχει μεθόδους για εργασία με τον 32-bit ακέραιο.

```cpp
class Int32
```

## Μέθοδοι

| Μεθοδος | Περιγραφή |
| --- | --- |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον ισοδύναμο 32-bit υπογεγραμμένο ακέραιο. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον ισοδύναμο 32-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον ισοδύναμο 32-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, std::nullptr_t) |  |
| static **int32_t** [Parse](./parse/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int32_t**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον ισοδύναμο 32-bit υπογεγραμμένο ακέραιο. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int32_t**\&) | Μετατρέπει τη συγκεκριμένη συμβολοσειρά που περιέχει την αναπαράσταση κειμένου ενός αριθμού στον ισοδύναμο 32-bit υπογεγραμμένο ακέραιο χρησιμοποιώντας τις παρεχόμενες πληροφορίες μορφοποίησης και το στυλ αριθμού. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int32_t**\&) |  |

## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Η μεγαλύτερη δυνατή τιμή. |
| static constexpr [MinValue](./minvalue/) | Η μικρότερη δυνατή τιμή. |

## Δείτε επίσης

* Namespace [System](../)
* Library [Aspose.Slides](../../)