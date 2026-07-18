---
title: Fallback()
second_title: Aspose.Slides για Αναφορά API C++
description: Εφαρμόζει πραγματική διαδικασία εφεδρείας.
type: docs
weight: 14
url: /el/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) μέθοδος

Εφαρμόζει πραγματική διαδικασία εφεδρείας.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) των bytes που περιλαμβάνουν το byte που ο αποκωδικοποιητής δεν μπορεί να αποκωδικοποιήσει. |
| index | int | Δείκτης του byte που προκάλεσε σφάλμα. |

### Τιμή Επιστροφής

Αληθές εάν η buffer επεξεργάζεται τα άγνωστα bytes, ψευδές εάν τα αγνοεί.

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [DecoderFallbackBuffer](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)