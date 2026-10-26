---
title: BlackWhiteConversionMode
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει επιλογές που ελέγχουν πώς οι εικόνες των διαφανειών θα μετατραπούν σε δυαδικές εικόνες.
type: docs
weight: 820
url: /el/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

Παρέχει επιλογές που ελέγχουν πώς οι εικόνες των διαφανειών θα μετατραπούν σε δυαδικές εικόνες.

```cpp
enum class BlackWhiteConversionMode
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| Default | 0 | Καθορίζει ότι δεν υπάρχει αλγόριθμος μετατροπής. Θα χρησιμοποιηθεί ο αλγόριθμος που υλοποιείται στον κωδικοποιητή TIFF. (Default) |
| Dithering | 1 | Καθορίζει τον αλγόριθμο ψήφισματος (Floyd-Steinberg). |
| DitheringFloydSteinberg | 2 | Καθορίζει τον αλγόριθμο ψήφισματος Floyd-Steinberg. |
| Auto | 3 | Καθορίζει τον αλγόριθμο κατωφλίου που υπολογίζεται αυτόματα (Otsu). |
| AutoOtsu | 4 | Καθορίζει τον αλγόριθμο κατωφλίου Otsu που υπολογίζεται αυτόματα. |
| Threshold25 | 5 | Καθορίζει τον στατικό αλγόριθμο κατωφλίου (25%). |
| Threshold50 | 6 | Καθορίζει τον στατικό αλγόριθμο κατωφλίου (50%). |
| Threshold75 | 7 | Καθορίζει τον στατικό αλγόριθμο κατωφλίου (75%). |

## Δείτε επίσης

* Χώρος ονομάτων [Aspose::Slides::Export](../)
* Βιβλιοθήκη [Aspose.Slides](../../)