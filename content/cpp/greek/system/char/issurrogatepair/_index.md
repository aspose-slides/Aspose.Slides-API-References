---
title: IsSurrogatePair()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει αν οι δύο καθορισμένοι χαρακτήρες αποτελούν ζεύγος διακριτικού UTF-16.
type: docs
weight: 27
url: /el/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) μέθοδος

Καθορίζει αν οι δύο καθορισμένοι χαρακτήρες αποτελούν ζεύγος διακριτικού UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Παράμετροι

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| highSurrogate | char_t | Ένας χαρακτήρας που ελέγχεται για το αν είναι υψηλό διακριτικό |
| lowSurrogate | char_t | Ένας χαρακτήρας που ελέγχεται για το αν είναι χαμηλό διακριτικό |

### Τιμή Επιστροφής

True εάν οι καθορισμένοι χαρακτήρες σχηματίζουν ζεύγος διακριτικού, διαφορετικά - false

## Char::IsSurrogatePair(const String\&, int) μέθοδος

Καθορίζει αν δύο διαδοχικοί χαρακτήρες στο καθορισμένο buffer χαρακτήρων αποτελούν ζεύγος διακριτικού.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Παράμετροι

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| str | const [String](../../string/)\& | Μια συμβολοσειρά |
| index | int | Ένας δείκτης που αρχίζει από το μηδέν στο καθορισμένο buffer, στο σημείο όπου αρχίζει η ακολουθία χαρακτήρων προς έλεγχο |

### Τιμή Επιστροφής

True εάν οι καθορισμένοι χαρακτήρες σχηματίζουν ζεύγος διακριτικού, διαφορετικά - false

## Δείτε επίσης

* Κλάση [Char](../)
* Κλάση [String](../../string/)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)