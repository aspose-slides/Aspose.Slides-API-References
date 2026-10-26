---
title: Fallback()
second_title: Aspose.Slides για C++ API Αναφορά
description: Διαχειρίζεται την αποτυχία κωδικοποίησης.
type: docs
weight: 27
url: /el/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) μέθοδος

Διαχειρίζεται την αποτυχία κωδικοποίησης.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charUnknown | char_t | Άγνωστοι χαρακτήρες· αγνοούνται. |
| index | int | Μετατόπιση άγνωστων χαρακτήρων· αγνοείται. |

### Τιμή Επιστροφής

Ποτέ δεν επιστρέφει πραγματικά, εγείρει εξαίρεση αντ' αυτού.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) μέθοδος

Διαχειρίζεται την αποτυχία κωδικοποίησης.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charUnknownHigh | char_t | Άνω μέρος του ζεύγους αντιπροσώπων που προκάλεσε σφάλμα. |
| charUnknownLow | char_t | Κάτω μέρος του ζεύγους αντιπροσώπων που προκάλεσε σφάλμα. |
| index | int | Μετατόπιση άγνωστου χαρακτήρα· αγνοείται. |

### Τιμή Επιστροφής

Ποτέ δεν επιστρέφει πραγματικά, εγείρει εξαίρεση αντ' αυτού.

## Δείτε επίσης

* Κλάση [EncoderExceptionFallbackBuffer](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)