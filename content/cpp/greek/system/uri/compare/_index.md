---
title: Compare()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συγκρίνει τα καθορισμένα αντικείμενα Uri χρησιμοποιώντας τους καθορισμένους κανόνες σύγκρισης.
type: docs
weight: 521
url: /el/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) μέθοδος


Συγκρίνει τα καθορισμένα [Uri](../) αντικείμενα χρησιμοποιώντας τους καθορισμένους κανόνες σύγκρισης.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Ο πρώτος συγκριτέος |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Ο δεύτερος συγκριτέος |
| partsToCompare | [UriComponents](../../uricomponents/) | Καθορίζει τα μέρη του **uri1** και **uri2** που θα συγκριθούν |
| compareFormat | [UriFormat](../../uriformat/) | Καθορίζει την διαφυγή χαρακτήρων που χρησιμοποιείται όταν τα στοιχεία των URI συγκρίνονται |
| comparisonType | [StringComparison](../../stringcomparison/) | Μία από τις τιμές του StringComparison |

### Τιμή επιστροφής

Μια αρνητική τιμή εάν **uri1** είναι μικρότερη από **uri2**· 0 εάν uri1 και uri2 είναι ίσα· μια θετική τιμή εάν **uri1** είναι μεγαλύτερο από **uri2**

## Δείτε επίσης

* Απαρίθμηση [UriComponents](../../uricomponents/)
* Απαρίθμηση [UriFormat](../../uriformat/)
* Απαρίθμηση [StringComparison](../../stringcomparison/)
* Ορισμός τύπου [SharedPtr](../../sharedptr/)
* Κλάση [Uri](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)