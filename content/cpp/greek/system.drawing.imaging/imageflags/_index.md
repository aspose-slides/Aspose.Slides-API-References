---
title: ImageFlags
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τις ιδιότητες των δεδομένων pixel που αντιπροσωπεύονται από ένα αντικείμενο Image.
type: docs
weight: 274
url: /el/system.drawing.imaging/imageflags/
---
## ImageFlags enum

Αντιπροσωπεύει τις ιδιότητες των δεδομένων pixel που αντιπροσωπεύονται από ένα αντικείμενο [Image](../../system.drawing/image/).

```cpp
enum class ImageFlags
```

### Values

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Κλιμακώσιμο. |
| HasAlpha | 2 | Περιέχει πληροφορίες άλφα. |
| HasTranslucent | 4 | Υπάρχουν τιμές άλφα μεγαλύτερες από 0 και μικρότερες από 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | Τα δεδομένα pixel εμφανίζονται σε χρωματικό χώρο RGB. |
| ColorSpaceCmyk | 32 | Τα δεδομένα pixel εμφανίζονται σε χρωματικό χώρο CMYK. |
| ColorSpaceGray | 64 | Τα δεδομένα pixel είναι σε αποχρώσεις του γκρι. |
| ColorSpaceYcbcr | 128 | Τα δεδομένα pixel εμφανίζονται σε χρωματικό χώρο YCBCR. |
| ColorSpaceYcck | 256 | Τα δεδομένα pixel εμφανίζονται σε χρωματικό χώρο YCCK. |
| HasRealDpi | 4096 | Οι πληροφορίες DPI αποθηκεύονται στην εικόνα. |
| HasRealPixelSize | 8192 | Το μέγεθος ενός pixel αποθηκεύεται στην εικόνα. |
| ReadOnly | 65536 | Τα δεδομένα pixel είναι μόνο για ανάγνωση. |
| Caching | 131072 | Μπορεί να προεγγραφεί για ταχύτερη πρόσβαση. |

## See Also

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.Slides](../../)