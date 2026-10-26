---
title: AddSectionZoomFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο Section Zoom πλαίσιο και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 118
url: /el/aspose.slides/ishapecollection/addsectionzoomframe/
---
## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>) method

Δημιουργεί ένα νέο [Section](../../section/) Zoom frame και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) που αναφέρεται από το [Section](../../section/) Zoom frame· πρέπει να ανήκει σε αυτή την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την προσθήκη ενός [Section](../../section/) Zoom αντικειμένου στο τέλος μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```

## IShapeCollection::AddSectionZoomFrame(float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) method

Δημιουργεί ένα νέο [Section](../../section/) Zoom frame με προορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::AddSectionZoomFrame(float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom frame, σε πόντους. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) που αναφέρεται από το [Section](../../section/) Zoom frame· πρέπει να ανήκει σε αυτή την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η [IPPImage](../../ippimage/) που θα εμφανιστεί μέσα στο [Section](../../section/) Zoom frame. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).
## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την προσθήκη ενός [Section](../../section/) Zoom αντικειμένου στο τέλος μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):

```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISectionZoomFrame](../../isectionzoomframe/)
* Κλάση [ISection](../../isection/)
* Κλάση [IShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)