---
title: FillPie()
second_title: Αναφορά API Aspose.Slides για C++
description: Γεμίζει το καθορισμένο πίτα χρησιμοποιώντας το καθορισμένο πινέλο στην επιφάνεια που αναπαριστά το τρέχον αντικείμενο.
type: docs
weight: 274
url: /el/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr\<Brush\>\&, int, int, int, int, int, int) μέθοδος

Γεμίζει το καθορισμένο πίτα χρησιμοποιώντας το καθορισμένο πινέλο στην επιφάνεια που αναπαριστά το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα πινέλο για χρήση κατά το γέμισμα του πίτα |
| x | int | Η συντεταγμένη X του πάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη |
| y | int | Η συντεταγμένη Y του πάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη |
| width | int | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | int | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα X μέχρι το σημείο εκκίνησης του πίτα |
| sweepAngle | int | Γωνία σε μοίρες που μετριέται δεξιόστροφα από το **startAngle** μέχρι το σημείο λήξης του πίτα |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, float, float, float, float, float, float) μέθοδος

Γεμίζει το καθορισμένο πίτα χρησιμοποιώντας το καθορισμένο πινέλο στην επιφάνεια που αναπαριστά το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα πινέλο για χρήση κατά το γέμισμα του πίτα |
| x | **float** | Η συντεταγμένη X του πάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη |
| y | **float** | Η συντεταγμένη Y του πάνω αριστερού γωνίου του ορθογωνίου που ορίζει την έλλειψη |
| width | **float** | Το πλάτος του ορθογωνίου που ορίζει την έλλειψη |
| height | **float** | Το ύψος του ορθογωνίου που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα X μέχρι το σημείο εκκίνησης του πίτα |
| sweepAngle | **float** | Γωνία σε μοίρες που μετριέται δεξιόστροφα από το **startAngle** μέχρι το σημείο λήξης του πίτα |

## Graphics::FillPie(const SharedPtr\<Brush\>\&, Rectangle, float, float) μέθοδος

Γεμίζει το καθορισμένο πίτα χρησιμοποιώντας το καθορισμένο πινέλο στην επιφάνεια που αναπαριστά το τρέχον αντικείμενο.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ένα πινέλο για χρήση κατά το γέμισμα του πίτα |
| rect | [Rectangle](../../rectangle/) | Το ορθογώνιο που ορίζει την έλλειψη |
| startAngle | **float** | Γωνία σε μοίρες που μετριέται δεξιόστροφα από τον άξονα X μέχρι το σημείο εκκίνησης του πίτα |
| sweepAngle | **float** | Γωνία σε μοίρες που μετριέται δεξιόστροφα από το **startAngle** μέχρι το σημείο λήξης του πίτα |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Brush](../../brush/)
* Κλάση [Graphics](../)
* Κλάση [Rectangle](../../rectangle/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)