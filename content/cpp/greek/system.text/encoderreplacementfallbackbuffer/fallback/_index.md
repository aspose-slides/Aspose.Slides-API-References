---
title: Fallback()
second_title: Aspose.Slides για C++ Αναφορά API
description: Διαχειρίζεται την αποτυχία κωδικοποίησης.
type: docs
weight: 27
url: /el/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) method

Διαχειρίζεται την αποτυχία κωδικοποίησης.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknown | char_t | Unknown character; ignored. |
| index | int | Unknown character position; ignored. |

### Τιμή Επιστροφής

Αληθής εάν παρέχεται συμβολοσειρά αντικατάστασης και δεν είναι κενή, ψευδής διαφορετικά.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) method

Διαχειρίζεται την αποτυχία κωδικοποίησης.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| charUnknownHigh | char_t | High part of surrogate pair that triggered error. |
| charUnknownLow | char_t | Low part of surrogate pair that triggered error. |
| index | int | Unknown character position; ignored. |

### Τιμή Επιστροφής

Αληθής εάν παρέχεται συμβολοσειρά αντικατάστασης και δεν είναι κενή, ψευδής διαφορετικά.

## Δείτε επίσης

* Κλάση [EncoderReplacementFallbackBuffer](../)
* Χώρος ονομάτων [System::Text](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)