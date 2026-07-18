---
title: DrawArc()
second_title: Αναφορά API του Aspose.Slides για C++
description: Σχεδίαζει το καθορισμένο τόξο χρησιμοποιώντας το καθορισμένο στυλό στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.
type: docs
weight: 248
url: /el/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) μέθοδος

Σχεδίαζει το συγκεκριμένο τόξο χρησιμοποιώντας το καθορισμένο στυλό στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση του τόξου |
| x | **int32_t** | Η συντεταγμένη X της άνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| y | **int32_t** | Η συντεταγμένη Y της άνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| width | **int32_t** | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | **int32_t** | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | **int32_t** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του τόξου |
| sweepAngle | **int32_t** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του τόξου |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) μέθοδος

Σχεδίαζει το συγκεκριμένο τόξο χρησιμοποιώντας το καθορισμένο στυλό στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση του τόξου |
| x | **float** | Η συντεταγμένη X της άνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| y | **float** | Η συντεταγμένη Y της άνω αριστερής γωνίας του ορθογωνίου που ορίζει την έλλειψη |
| width | **float** | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | **float** | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του τόξου |
| sweepAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του τόξου |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) μέθοδος

Σχεδίαζει το συγκεκριμένο τόξο χρησιμοποιώντας το καθορισμένο στυλό στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση του τόξου |
| rect | [Rectangle](../../rectangle/) | Το ορθογώνιο που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του τόξου |
| sweepAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του τόξου |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) μέθοδος

Σχεδίαζει το συγκεκριμένο τόξο χρησιμοποιώντας το καθορισμένο στυλό στην επιφάνεια που αντιπροσωπεύεται από το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ένα στυλό για χρήση κατά τη σχεδίαση του τόξου |
| rect | [RectangleF](../../rectanglef/) | Το ορθογώνιο που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από τον άξονα X μέχρι το αρχικό σημείο του τόξου |
| sweepAngle | **float** | Γωνία σε μοίρες μετρώντας δεξιόστροφα από το **startAngle** μέχρι το τελικό σημείο του τόξου |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Pen](../../pen/)
* Κλάση [Graphics](../)
* Κλάση [Rectangle](../../rectangle/)
* Κλάση [RectangleF](../../rectanglef/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)