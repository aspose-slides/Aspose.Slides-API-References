---
title: Fallback()
second_title: Αναφορά API του Aspose.Slides για C++
description: Υλοποιεί την πραγματική διαδικασία εναλλακτικού χαρακτήρα.
type: docs
weight: 14
url: /el/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) μέθοδος


Υλοποιεί την πραγματική διαδικασία εναλλακτικού χαρακτήρα.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charUnknown | char_t | Ο κωδικοποιητής χαρακτήρων αποτυγχάνει να κωδικοποιήσει. |
| index | int | Δείκτης του χαρακτήρα που προκάλεσε το σφάλμα. |

### Τιμή Επιστροφής

Αληθές εάν η μνήμη buffer επεξεργάζεται άγνωστους χαρακτήρες, ψευδές εάν τους αγνοεί.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) μέθοδος


Υλοποιεί την πραγματική διαδικασία εναλλακτικού χαρακτήρα.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| charUnknownHigh | char_t | Άνω μέρος του ζεύγους υποκατάστασης που προκάλεσε το σφάλμα. |
| charUnknownLow | char_t | Κάτω μέρος του ζεύγους υποκατάστασης που προκάλεσε το σφάλμα. |
| index | int | Δείκτης του χαρακτήρα που προκάλεσε το σφάλμα. |

### Τιμή Επιστροφής

Αληθές εάν η μνήμη buffer επεξεργάζεται άγνωστους χαρακτήρες, ψευδές εάν τους αγνοεί.

## Δείτε επίσης

* Κλάση [EncoderFallbackBuffer](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)