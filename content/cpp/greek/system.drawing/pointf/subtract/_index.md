---
title: Subtract()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αφαιρεί τις τιμές του πλάτους και του ύψους του καθορισμένου αντικειμένου SizeF από τις τιμές των συντεταγμένων X και Y του καθορισμένου αντικειμένου PointF αντίστοιχα.
type: docs
weight: 157
url: /el/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) μέθοδος


Αφαιρεί τις τιμές του πλάτους και του ύψους του καθορισμένου [SizeF](../../sizef/) αντικειμένου από τις τιμές των συντεταγμένων X και Y του καθορισμένου [PointF](../) αντικειμένου αντίστοιχα.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [SizeF](../../sizef/)\& | The [SizeF](../../sizef/) object that specifies the values to subtract from the coordinates values of the **point** |

### Τιμή επιστροφής

Ένα νέο [PointF](../) αντικείμενο του οποίου η τιμή της συντεταγμένης X είναι ίση με το αποτέλεσμα της αφαίρεσης της τιμής του πλάτους του **size** από την τιμή της συντεταγμένης X του **point** και η τιμή της συντεταγμένης Y είναι ίση με το αποτέλεσμα της αφαίρεσης της τιμής του ύψους του **size** από την τιμή της συντεταγμένης Y του **point**


## PointF::Subtract(const PointF\&, const Size\&) μέθοδος


Αφαιρεί τις τιμές του πλάτους και του ύψους του καθορισμένου [Size](../../size/) αντικειμένου από τις τιμές των συντεταγμένων X και Y του καθορισμένου [PointF](../) αντικειμένου αντίστοιχα.

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```


### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [PointF](../)\& | The point to translate |
| size | const [Size](../../size/)\& | The [Size](../../size/) object that specifies the values to subtract from the coordinates values of the **point** |

### Τιμή επιστροφής

Ένα νέο [PointF](../) αντικείμενο του οποίου η τιμή της συντεταγμένης X είναι ίση με το αποτέλεσμα της αφαίρεσης της τιμής του πλάτους του **size** από την τιμή της συντεταγμένης X του **point** και η τιμή της συντεταγμένης Y είναι ίση με το αποτέλεσμα της αφαίρεσης της τιμής του ύψους του **size** από την τιμή της συντεταγμένης Y του **point**


## Δείτε επίσης

* Κλάση [PointF](../)
* Κλάση [SizeF](../../sizef/)
* Κλάση [Size](../../size/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)