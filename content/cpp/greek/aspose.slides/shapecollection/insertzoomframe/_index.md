---
title: InsertZoomFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη.
type: docs
weight: 118
url: /el/aspose.slides/shapecollection/insertzoomframe/
---
## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Το [ISlide](../../islide/) στο οποίο αναφέρεται το πλαίσιο Zoom. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Παρατηρήσεις

Αυτό το παράδειγμά δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Zoom στον καθορισμένο δείκτη μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## ShapeCollection::InsertZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχήματος στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::InsertZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Το [ISlide](../../islide/) στο οποίο αναφέρεται το πλαίσιο Zoom. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η εικόνα για τη διαφάνεια [IPPImage](../../ippimage/) που αναφέρεται. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Παρατηρήσεις

Αυτό το παράδειγμά δείχνει τη δημιουργία και την εισαγωγή ενός αντικειμένου Zoom στον καθορισμένο δείκτη μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->InsertZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IZoomFrame](../../izoomframe/)
* Κλάση [ISlide](../../islide/)
* Κλάση [ShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)