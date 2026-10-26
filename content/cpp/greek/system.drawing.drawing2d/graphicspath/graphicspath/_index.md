---
title: GraphicsPath()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο στιγμιότυπο της κλάσης GraphicsPath με την καθορισμένη λειτουργία γεμίσματος.
type: docs
weight: 1
url: /el/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης [GraphicsPath](../) με την καθορισμένη λειτουργία γεμίσματος.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | Καθορίζει πώς πρέπει να γεμιστεί το εσωτερικό του κλειστού μονοπατιού που αντιπροσωπεύει το αντικείμενο που δημιουργείται |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο του αντικειμένου [GraphicsPath](../) που αντιπροσωπεύει τη καθορισμένη διαδρομή.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Πίνακας που περιέχει τα σημεία που καθορίζουν τη διαδρομή που θα αντιπροσωπεύσει το αντικείμενο που δημιουργείται |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Πίνακας που περιέχει τις τιμές που καθορίζουν τους τύπους των αντίστοιχων σημείων στον πίνακα **pts** |
| fillMode | [FillMode](../../fillmode/) | Καθορίζει πώς πρέπει να γεμιστεί το εσωτερικό του κλειστού μονοπατιού που αντιπροσωπεύει το αντικείμενο που δημιουργείται |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) Κατασκευαστής


Δημιουργεί ένα νέο στιγμιότυπο του αντικειμένου [GraphicsPath](../) που αντιπροσωπεύει τη καθορισμένη διαδρομή.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Πίνακας που περιέχει τα σημεία που καθορίζουν τη διαδρομή που θα αντιπροσωπεύσει το αντικείμενο που δημιουργείται |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Πίνακας που περιέχει τις τιμές που καθορίζουν τους τύπους των αντίστοιχων σημείων στον πίνακα **pts** |
| fillMode | [FillMode](../../fillmode/) | Καθορίζει πώς πρέπει να γεμιστεί το εσωτερικό του κλειστού μονοπατιού που αντιπροσωπεύει το αντικείμενο που δημιουργείται |

## GraphicsPath::GraphicsPath(const SkPath\&) Κατασκευαστής




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## Δείτε επίσης

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [GraphicsPath](../)
* Κλάση [Point](../../../system.drawing/point/)
* Κλάση [PointF](../../../system.drawing/pointf/)
* Χώρος ονομάτων [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)