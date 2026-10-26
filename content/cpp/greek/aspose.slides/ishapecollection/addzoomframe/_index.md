---
title: AddZoomFrame()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 92
url: /el/aspose.slides/ishapecollection/addzoomframe/
---
## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Το [ISlide](../../islide/) που αναφέρεται από το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Zoom στο τέλος μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
```

## IShapeCollection::AddZoomFrame(float, float, float, float, System::SharedPtr\<ISlide\>, System::SharedPtr\<IPPImage\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
virtual System::SharedPtr<IZoomFrame> Aspose::Slides::IShapeCollection::AddZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISlide> slide, System::SharedPtr<IPPImage> image)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η x-συντεταγμένη του νέου πλαισίου Zoom, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου πλαισίου Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε σημεία. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Το [ISlide](../../islide/) που αναφέρεται από το πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η εικόνα για τη διαφάνεια που αναφέρεται [IPPImage](../../ippimage/). |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IZoomFrame](../../izoomframe/).

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την προσθήκη ενός αντικειμένου Zoom στο τέλος μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο διαφάνειες στην παρουσίαση "Presentation.pptx"):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IZoomFrame](../../izoomframe/)
* Κλάση [ISlide](../../islide/)
* Κλάση [IShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)