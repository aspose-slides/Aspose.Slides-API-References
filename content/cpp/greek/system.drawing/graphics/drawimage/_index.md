---
title: DrawImage()
second_title: Aspose.Slides για C++ API Αναφορά
description: ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.
type: docs
weight: 430
url: /el/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | IGNORED |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | IGNORED |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Ένας πίνακας που περιέχει τρία σημεία τα οποία ορίζουν ένα παραλληλόγραμμο στην επιφάνεια σχεδίασης για σχεδίαση της εικόνας |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Μια προβολή πίνακα που περιγράφει τρία σημεία τα οποία ορίζουν ένα παραλληλόγραμμο στην επιφάνεια σχεδίασης για σχεδίαση της εικόνας |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Ένας στοίβα πίνακα που περιέχει τρία σημεία τα οποία ορίζουν ένα παραλληλόγραμμο στην επιφάνεια σχεδίασης για σχεδίαση της εικόνας |
| srcRect | const [RectangleF](../../rectanglef/)\& | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | int | Η συντεταγμένη X της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |
| y | int | Η συντεταγμένη Y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | **float** | Η συντεταγμένη X της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |
| y | **float** | Η συντεταγμένη Y της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| pt | [Point](../../point/) | Η θέση της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| pt | [PointF](../../pointf/) | Η θέση της επάνω αριστερής γωνίας της σχεδιασμένης εικόνας |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | int | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| y | int | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| width | int | Το πλάτος του επάνω αριστερού γωνίου του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| height | int | Το ύψος του επάνω αριστερού γωνίου του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | **float** | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| y | **float** | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| width | **float** | Το πλάτος του επάνω αριστερού γωνίου του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| height | **float** | Το ύψος του επάνω αριστερού γωνίου του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [RectangleF](../../rectanglef/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcRect | [RectangleF](../../rectanglef/) | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | int | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| y | int | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| srcRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| rect | const [Rectangle](../../rectangle/)\& | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) μέθοδος


Σχεδιάζει την καθορισμένη εικόνα στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| rect | const [RectangleF](../../rectanglef/)\& | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcX | int | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcY | int | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcWidth | int | Το πλάτος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcHeight | int | Το ύψος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης στις οποίες καθορίζονται οι παράμετροι **srcX**, **srcY**, **srcWidth** και **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcX | **float** | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcY | **float** | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcWidth | **float** | Το πλάτος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcHeight | **float** | Το ύψος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης στις οποίες καθορίζονται οι παράμετροι **srcX**, **srcY**, **srcWidth** και **srcHeight** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcX | int | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcY | int | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcWidth | int | Το πλάτος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcHeight | int | Το ύψος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης στις οποίες καθορίζονται οι παράμετροι **srcX**, **srcY**, **srcWidth** και **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στο καθορισμένο ορθογώνιο.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο στο οποίο θα σχεδιαστεί η εικόνα |
| srcX | **float** | Η συντεταγμένη X της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcY | **float** | Η συντεταγμένη Y της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcWidth | **float** | Το πλάτος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcHeight | **float** | Το ύψος της επάνω αριστερής γωνίας του ορθογωνίου που καθορίζει το τμήμα της εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης στις οποίες καθορίζονται οι παράμετροι **srcX**, **srcY**, **srcWidth** και **srcHeight** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΙΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) μέθοδος


ΔΕΝ ΥΛΟΠΟΙΕΤΑΙ.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```


## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Ένας πίνακας που περιέχει τρία σημεία τα οποία ορίζουν ένα παραλληλόγραμμο στην επιφάνεια σχεδίασης για σχεδίαση της εικόνας |
| srcRect | [Rectangle](../../rectangle/) | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Καθορίζει πληροφορίες χρωματισμού και γάμα για την εικόνα |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) μέθοδος


Σχεδιάζει την καθορισμένη περιοχή της καθορισμένης εικόνας στην καθορισμένη θέση.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Η εικόνα για σχεδίαση |
| x | **float** | Η συντεταγμένη X της επάν ω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| y | **float** | Η συντεταγμένη Y της επάν ω αριστερής γωνίας του ορθογωνίου στο οποίο θα σχεδιαστεί η εικόνα |
| srcRect | [RectangleF](../../rectanglef/) | Ένα ορθογώνιο που ορίζει την περιοχή της καθορισμένης εικόνας που θα σχεδιαστεί |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Οι μονάδες μέτρησης που χρησιμοποιούνται από την παράμετρο **srcRect** |

## See Also

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)