---
title: Flatten()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ισοπεδώνει κάθε καμπύλη στο μονοπάτι μετατρέποντάς την σε σειρά συνδεδεμένων γραμμών. Η τιμή ισοπεδότητας 0.25 χρησιμοποιείται.
type: docs
weight: 391
url: /el/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() μέθοδος

Ισοπεδώνει κάθε καμπύλη στο μονοπάτι μετατρέποντάς την σε σειρά συνδεδεμένων γραμμών. Η τιμή ισοπεδότητας 0.25 χρησιμοποιείται.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```
## GraphicsPath::Flatten(const MatrixPtr\&) μέθοδος

Ισοπεδώνει κάθε καμπύλη στο μονοπάτι μετατρέποντάς την σε σειρά συνδεδεμένων γραμμών. Η τιμή ισοπεδότητας 0.25 χρησιμοποιείται.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Ο πίνακας μετασχηματισμού που θα εφαρμοστεί στο μονοπάτι πριν την ισοπεδωση |

## GraphicsPath::Flatten(const MatrixPtr\&, float) μέθοδος

Ισοπεδώνει κάθε καμπύλη στο μονοπάτι μετατρέποντάς την σε σειρά συνδεδεμένων γραμμών.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | Ο πίνακας μετασχηματισμού που θα εφαρμοστεί στο μονοπάτι πριν την ισοπεδωση |
| flatness | **float** | Καθορίζει το μέγιστο επιτρεπτό σφάλμα μεταξύ της καμπύλης και της ισοπεδωμένης προσέγγισής της |

## Δείτε επίσης

* Typedef [MatrixPtr](../../matrixptr/)
* Κλάση [GraphicsPath](../)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)