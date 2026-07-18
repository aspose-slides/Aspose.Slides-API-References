---
title: Parse()
second_title: Aspose.Slides για C++ Αναφορά API
description: Μετατρέπει την αναπαράσταση κειμένου ενός δεκαδικού αριθμού σε ένα ισοδύναμο στιγμιότυπο της κλάσης Decimal.
type: docs
weight: 469
url: /el/system/decimal/parse/
---
## Decimal::Parse(const String\&) method

Μετατρέπει την αναπαράσταση κειμένου ενός δεκαδικού αριθμού σε ένα ισοδύναμο στιγμιότυπο της κλάσης [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση κειμένου ενός αριθμού |

### Return Value

Ένα νέο στιγμιότυπο της κλάσης [Decimal](../) που αντιπροσωπεύει μια τιμή ισοδύναμη με αυτή που αναπαρίσταται από τη συγκεκριμένη συμβολοσειρά.

## Decimal::Parse(const String\&, Globalization::NumberStyles) method

Μετατρέπει την αναπαράσταση κειμένου ενός δεκαδικού αριθμού σε ένα ισοδύναμο στιγμιότυπο της κλάσης [Decimal](../) χρησιμοποιώντας το καθορισμένο στυλ.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση κειμένου μιας δεκαδικής τιμής προς μετατροπή |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός κατά τιμής bitwise των τιμών της απαρίθμησης που παρέχει πρόσθετες πληροφορίες σχετικά με **s**, σχετικά με τα στοιχεία στυλ που ενδέχεται να υπάρχουν στο **s**, ή σχετικά με τη μετατροπή από το **s** σε ένα αντικείμενο [Decimal](../) |

### Return Value

Ένα νέο στιγμιότυπο της κλάσης [Decimal](../) που αντιπροσωπεύει μια τιμή ισοδύναμη με αυτή που αναπαρίσταται από τη συγκεκριμένη συμβολοσειρά.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Μετατρέπει την αναπαράσταση κειμένου ενός δεκαδικού αριθμού σε ένα ισοδύναμο στιγμιότυπο της κλάσης [Decimal](../) χρησιμοποιώντας τον καθορισμένο πάροχο μορφοποίησης.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση κειμένου μιας δεκαδικής τιμής προς μετατροπή |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφοποίησης |

### Return Value

Ένα νέο στιγμιότυπο της κλάσης [Decimal](../) που αντιπροσωπεύει μια τιμή ισοδύναμη με αυτή που αναπαρίσταται από τη συγκεκριμένη συμβολοσειρά.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Μετατρέπει την αναπαράσταση κειμένου ενός δεκαδικού αριθμού σε ένα ισοδύναμο στιγμιότυπο της κλάσης [Decimal](../) χρησιμοποιώντας το καθορισμένο στυλ και πάροχο μορφοποίησης.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Η αναπαράσταση κειμένου μιας δεκαδικής τιμής προς μετατροπή |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Ένας συνδυασμός κατά τιμής bitwise των τιμών της απαρίθμησης που παρέχει πρόσθετες πληροφορίες σχετικά με **s**, σχετικά με τα στοιχεία στυλ που ενδέχεται να υπάρχουν στο **s**, ή σχετικά με τη μετατροπή από το **s** σε ένα αντικείμενο [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Πάροχος μορφοποίησης |

### Return Value

Ένα νέο στιγμιότυπο της κλάσης [Decimal](../) που αντιπροσωπεύει μια τιμή ισοδύναμη με αυτή που αναπαρίσταται από τη συγκεκριμένη συμβολοσειρά.

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)