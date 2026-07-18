---
title: Write()
second_title: Aspose.Slides για C++ Αναφορά API
description: Γράφει τον καθορισμένο χαρακτήρα στη ροή.
type: docs
weight: 40
url: /el/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) μέθοδος

Γράφει τον καθορισμένο χαρακτήρα στη ροή.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | char_t | Η τιμή προς εγγραφή |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποσύνολο χαρακτήρων από τον καθορισμένο πίνακα χαρακτήρων στη ροή.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Ο πίνακας που περιέχει τους χαρακτήρες προς εγγραφή |
| index | **int32_t** | Ένας δείκτης με βάση το 0 του στοιχείου στο **buffer** στο οποίο αρχίζει το υποσύνολο προς εγγραφή |
| count | **int32_t** | Ο αριθμός των χαρακτήρων στο υποσύνολο προς εγγραφή |

## StringWriter::Write(const String\&) μέθοδος

Γράφει τη καθορισμένη συμβολοσειρά στη ροή.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Η συμβολοσειρά προς εγγραφή |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [StringWriter](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::IO](../../)
* Library [Aspose.Slides](../../../)