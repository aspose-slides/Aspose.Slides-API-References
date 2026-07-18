---
title: DrawPie()
second_title: Aspose.Slides – Αναφορά API για C++
description: Σχεδίαζει το συγκεκριμένο κομμάτι πίτας χρησιμοποιώντας το καθορισμένο πεν στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 261
url: /el/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) μέθοδος

Σχεδιάζει το συγκεκριμένο pie χρησιμοποιώντας το συγκεκριμένο pen στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα pen για χρήση κατά τη σχεδίαση του pie |
| x | **int32_t** | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| y | **int32_t** | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| width | **int32_t** | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | **int32_t** | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | **int32_t** | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του pie |
| sweepAngle | **int32_t** | Γωνία σε μοίρες που μετράται δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του pie |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) μέθοδος

Σχεδιάζει το συγκεκριμένο pie χρησιμοποιώντας το συγκεκριμένο pen στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα pen για χρήση κατά τη σχεδίαση του pie |
| x | **float** | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| y | **float** | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| width | **float** | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | **float** | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του pie |
| sweepAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του pie |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) μέθοδος

Σχεδιάζει το συγκεκριμένο pie χρησιμοποιώντας το συγκεκριμένο pen στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα pen για χρήση κατά τη σχεδίαση του pie |
| rect | [Rectangle](../../rectangle/) | Το ορθογώνιο που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του pie |
| sweepAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του pie |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) μέθοδος

Σχεδιάζει το συγκεκριμένο pie χρησιμοποιώντας το συγκεκριμένο pen στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα pen για χρήση κατά τη σχεδίαση του pie |
| rect | [RectangleF](../../rectanglef/) | Το ορθογώνιο που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του pie |
| sweepAngle | **float** | Γωνία σε μοίρες που μετράται δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του pie |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Pen](../../pen/)
* Κλάση [Graphics](../)
* Κλάση [Rectangle](../../rectangle/)
* Κλάση [RectangleF](../../rectanglef/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)