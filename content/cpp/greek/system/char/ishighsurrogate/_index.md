---
title: IsHighSurrogate()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση στην καθορισμένη συμβολοσειρά είναι μονάδα κώδικα UTF-16 υψηλής αντιστοιχίας.
type: docs
weight: 40
url: /el/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) μέθοδος


Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση στην καθορισμένη συμβολοσειρά είναι μονάδα κώδικα UTF-16 υψηλής αντιστοιχίας.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | Μια συμβολοσειρά |
| index | int | Η θέση στη συγκεκριμένη συμβολοσειρά του χαρακτήρα που θα δοκιμαστεί |

### Τιμή επιστροφής

Αληθές εάν ο χαρακτήρας στη συγκεκριμένη θέση είναι μονάδα κώδικα UTF-16 υψηλής αντιστοιχίας, διαφορετικά - ψευδές

## Char::IsHighSurrogate(const char_t *, int) μέθοδος


Καθορίζει αν ο χαρακτήρας στη συγκεκριμένη θέση στον καθορισμένο buffer χαρακτήρων είναι υψηλή αντιστοιχία.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | Δείκτης στην αρχή του buffer χαρακτήρων |
| idx | int | Μηδενική θέση στον καθορισμένο buffer του χαρακτήρα που θα δοκιμαστεί |

### Τιμή επιστροφής

Αληθές εάν ο χαρακτήρας στη συγκεκριμένη θέση είναι υψηλή αντιστοιχία, διαφορετικά - ψευδές

## Char::IsHighSurrogate(char_t) μέθοδος


Καθορίζει αν ο καθορισμένος χαρακτήρας είναι υψηλή αντιστοιχία.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | Ο χαρακτήρας που θα δοκιμαστεί |

### Τιμή επιστροφής

Αληθές εάν ο καθορισμένος χαρακτήρας είναι υψηλή αντιστοιχία, διαφορετικά - ψευδές

## Δείτε επίσης

* Κλάση [String](../../string/)
* Κλάση [Char](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)