---
title: AddZoomFrame()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 105
url: /el/aspose.slides/shapecollection/addzoomframe/
---
## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) μέθοδος


Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Η [ISlide](../../islide/) στην οποία αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτή την παρουσίαση. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Σχόλια


Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Zoom στο τέλος μιας συλλογής (υποθέτετε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```


## ShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) μέθοδος


Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IZoomFrame> Aspose::Slides::ShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Η [ISlide](../../islide/) στην οποία αναφέρεται το πλαίσιο Zoom· πρέπει να ανήκει σε αυτή την παρουσίαση. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η εικόνα για τη διαφάνεια [IPPImage](../../ippimage/). |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Σχόλια


Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Zoom στο τέλος μιας συλλογής (υποθέτετε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```




## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IZoomFrame](../../izoomframe/)
* Κλάση [ISlide](../../islide/)
* Κλάση [ShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)