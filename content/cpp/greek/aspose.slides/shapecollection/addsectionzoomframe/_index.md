---
title: AddSectionZoomFrame()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο Section Zoom και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 131
url: /el/aspose.slides/shapecollection/addsectionzoomframe/
---
## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) Zoom πλαίσιο και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) που αναφέρεται από το [Section](../../section/) Zoom πλαίσιο· πρέπει να ανήκει σε αυτή την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).

## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει την προσθήκη ενός [Section](../../section/) Zoom αντικειμένου στο τέλος μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) Zoom πλαίσιο με προκαθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom πλαισίου, σε σημεία. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) που αναφέρεται από το [Section](../../section/) Zoom πλαίσιο· πρέπει να ανήκει σε αυτή την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Το [IPPImage](../../ippimage/) που θα εμφανιστεί μέσα στο [Section](../../section/) Zoom πλαίσιο. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).

## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει την προσθήκη ενός [Section](../../section/) Zoom αντικειμένου στο τέλος μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISectionZoomFrame](../../isectionzoomframe/)
* Κλάση [ISection](../../isection/)
* Κλάση [ShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)