---
title: TryParse()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσπαθεί να μετατρέψει την καθορισμένη συμβολοσειρά σε ισοδύναμη σταθερά enum.
type: docs
weight: 79
url: /el/system/enum/tryparse/
---
## Enum::TryParse(const String\&, E\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε ισοδύναμη σταθερά enum.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, E &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) που ερμηνεύεται ως περιέχοντας το όνομα της σταθεράς enum |
| result | E\& | Η παράμετρος εξόδου που εάν η μετατροπή είναι επιτυχής περιέχει το αποτέλεσμα της μετατροπής στη συνάρτηση |

### Return Value

Αληθές εάν η μετατροπή ήταν επιτυχής, διαφορετικά - ψευδές

## Enum::TryParse(const String\&, bool, E\&) μέθοδος

Προσπαθεί να μετατρέψει τη συγκεκριμένη συμβολοσειρά σε ισοδύναμη σταθερά enum.

```cpp
static bool System::Enum<E, Guard>::TryParse(const String &str, bool ignoreCase, E &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../string/)\& | [String](../../string/) που ερμηνεύεται ως περιέχοντας το όνομα της σταθεράς enum |
| ignoreCase | **bool** | Καθορίζει αν η διάκριση πεζών/κεφαλαίων πρέπει να αγνοηθεί κατά την ερμηνεία της συμβολοσειράς |
| result | E\& | Η παράμετρος εξόδου που εάν η μετατροπή είναι επιτυχής περιέχει το αποτέλεσμα της μετατροπής στην επιστροφή της συνάρτησης |

### Return Value

Αληθές εάν η μετατροπή ήταν επιτυχής, διαφορετικά - ψευδές

## See Also

* Κλάση [String](../../string/)
* Δομή [Enum](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)