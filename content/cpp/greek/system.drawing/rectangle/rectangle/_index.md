---
title: Rectangle()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο παράδειγμα του αντικειμένου Rectangle που αντιπροσωπεύει ένα ορθογώνιο με συντεταγμένες X και Y και τιμές πλάτους και ύψους ορισμένες σε 0.
type: docs
weight: 1
url: /el/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() κατασκευαστής

Δημιουργεί ένα νέο παράδειγμα του αντικειμένου [Rectangle](../) που αντιπροσωπεύει ένα ορθογώνιο με συντεταγμένες X και Y και τιμές πλάτους και ύψους ορισμένες σε 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) κατασκευαστής

Δημιουργεί ένα νέο παράδειγμα του αντικειμένου [Rectangle](../) που αντιπροσωπεύει ένα ορθογώνιο με τις συγκεκριμένες συντεταγμένες της άνω αριστερής γωνίας του και το πλάτος και το ύψος του.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | int | Μια τιμή της συντεταγμένης X της άνω αριστερής γωνίας του ορθογωνίου |
| y | int | Μια τιμή της συντεταγμένης Y της άνω αριστερής γωνίας του ορθογωνίου |
| width | int | Το πλάτος του ορθογωνίου |
| height | int | Το ύψος του ορθογωνίου |

## Rectangle::Rectangle(const Point\&, const Size\&) κατασκευαστής

Δημιουργεί ένα νέο παράδειγμα του αντικειμένου [Rectangle](../) που αντιπροσωπεύει ένα ορθογώνιο με τις συντεταγμένες της άνω αριστερής γωνίας του καθορισμένες ως ένα παράδειγμα της κλάσης [Point](../../point/) και το πλάτος και το ύψος του ως ένα παράδειγμα της κλάσης [Size](../../size/).

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Καθορίζει τη θέση της άνω αριστερής γωνίας του ορθογωνίου |
| size | const [Size](../../size/)\& | Καθορίζει το πλάτος και το ύψος του ορθογωνίου |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) κατασκευαστής

Δημιουργεί ένα νέο παράδειγμα του αντικειμένου [Rectangle](../) που αντιπροσωπεύει το ορθογώνιο ισοδύναμο με το καθορισμένο.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Ένα παράδειγμα της κλάσης **System::Windows::Forms::Screen::Rectangle_** που καθορίζει τη θέση και το μέγεθος του ορθογωνίου που θα αναπαρασταθεί από το αντικείμενο που κατασκευάζεται |

## Δείτε επίσης

* Κλάση [Rectangle](../)
* Κλάση [Point](../../point/)
* Κλάση [Size](../../size/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)