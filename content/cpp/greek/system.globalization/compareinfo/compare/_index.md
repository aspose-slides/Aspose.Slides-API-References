---
title: Compare()
second_title: Aspose.Slides για C++ API Αναφορά
description: Συγκρίνει αλφαριθμητικά. Δεν έχει υλοποιηθεί.
type: docs
weight: 66
url: /el/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const μέθοδος

Συγκρίνει αλφαριθμητικά. Δεν έχει υλοποιηθεί.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Αλφαριθμητικό στην αριστερή πλευρά. |
| string2 | const [String](../../../system/string/)\& | Αλφαριθμητικό στη δεξιά πλευρά. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το αλφαριθμητικό της αριστερής πλευράς προηγείται του αλφαριθμητικού της δεξιάς πλευράς, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const μέθοδος

Συγκρίνει αλφαριθμητικά. Υποστηρίζονται μόνο οι λειτουργίες Ordinal και OrdinalIgnoreCase.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | Αλφαριθμητικό στην αριστερή πλευρά. |
| b | const [String](../../../system/string/)\& | Αλφαριθμητικό στη δεξιά πλευρά. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) τύπος σύγκρισης. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το αλφαριθμητικό της αριστερής πλευράς προηγείται του αλφαριθμητικού της δεξιάς πλευράς, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const μέθοδος

Συγκρίνει τμήμα ενός αλφαριθμητικού με τμήμα δεύτερου αλφαριθμητικού. Δεν έχει υλοποιηθεί.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Πρώτο αλφαριθμητικό. |
| offset1 | int | Δείκτης έναρξης χαρακτήρων στο **string1**. |
| length1 | int | Αριθμός χαρακτήρων στο **string1** προς σύγκριση. |
| string2 | const [String](../../../system/string/)\& | Δεύτερο αλφαριθμητικό. |
| offset2 | int | Δείκτης έναρξης χαρακτήρων στο **string2**. |
| length2 | int | Αριθμός χαρακτήρων στο **string2** προς σύγκριση. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το τμήμα του πρώτου αλφαριθμητικού προηγείται του τμήματος του δεύτερου αλφαριθμητικού, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const μέθοδος

Συγκρίνει το τμήμα τέλους ενός αλφαριθμητικού με το τμήμα τέλους του δεύτερου αλφαριθμητικού χρησιμοποιώντας μεθόδους σύγκρισης αλφαριθμητικών. Δεν έχει υλοποιηθεί.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Πρώτο αλφαριθμητικό. |
| offset1 | int | Δείκτης έναρξης χαρακτήρων στο **string1**. |
| string2 | const [String](../../../system/string/)\& | Δεύτερο αλφαριθμητικό. |
| offset2 | int | Δείκτης έναρξης χαρακτήρων στο **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) επιλογές σύγκρισης. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το τμήμα του πρώτου αλφαριθμητικού προηγείται του τμήματος του δεύτερου αλφαριθμητικού, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## CompareInfo::Compare(const String\&, int, const String\&, int) const μέθοδος

Συγκρίνει το τμήμα τέλους ενός αλφαριθμητικού με το τμήμα τέλους του δεύτερου αλφαριθμητικού. Δεν έχει υλοποιηθεί.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Πρώτο αλφαριθμητικό. |
| offset1 | int | Δείκτης έναρξης χαρακτήρων στο **string1**. |
| string2 | const [String](../../../system/string/)\& | Δεύτερο αλφαριθμητικό. |
| offset2 | int | Δείκτης έναρξης χαρακτήρων στο **string2**. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το τμήμα του πρώτου αλφαριθμητικού προηγείται του τμήματος του δεύτερου αλφαριθμητικού, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const μέθοδος

Συγκρίνει τμήμα ενός αλφαριθμητικού με τμήμα δεύτερου αλφαριθμητικού χρησιμοποιώντας μεθόδους σύγκρισης αλφαριθμητικών. Δεν έχει υλοποιηθεί.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | Πρώτο αλφαριθμητικό. |
| offset1 | int | Δείκτης έναρξης χαρακτήρων στο **string1**. |
| length1 | int | Αριθμός χαρακτήρων στο **string1** προς σύγκριση. |
| string2 | const [String](../../../system/string/)\& | Δεύτερο αλφαριθμητικό. |
| offset2 | int | Δείκτης έναρξης χαρακτήρων στο **string2**. |
| length2 | int | Αριθμός χαρακτήρων στο **string2** προς σύγκριση. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) επιλογές σύγκρισης. |

### Τιμή Επιστροφής

Αρνητική τιμή αν το τμήμα του πρώτου αλφαριθμητικού προηγείται του τμήματος του δεύτερου αλφαριθμητικού, μηδέν αν είναι ίσα, θετική τιμή διαφορετικά.

## See Also

* Enum [CompareOptions](../../compareoptions/)
* Κλάση [String](../../../system/string/)
* Κλάση [CompareInfo](../)
* Χώρος ονομάτων [System::Globalization](../../)
* Library [Aspose.Slides](../../../)