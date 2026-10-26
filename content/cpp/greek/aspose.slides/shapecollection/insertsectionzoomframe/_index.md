---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 144
url: /el/aspose.slides/shapecollection/insertsectionzoomframe/
---
## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης αρχής μηδέν στον οποίο θα εισαχθεί το [Section](../../section/) πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| height | **float** | Το ύψος του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Η [ISection](../../isection/) στην οποία αναφέρεται το [Section](../../section/) πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).

## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός [Section](../../section/) αντικειμένου Zoom στον καθορισμένο δείκτη μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## ShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) πλαίσιο Zoom με προορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<ISectionZoomFrame> Aspose::Slides::ShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης αρχής μηδέν στον οποίο θα εισαχθεί το [Section](../../section/) πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| height | **float** | Το ύψος του νέου [Section](../../section/) πλαισίου Zoom, σε points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Η [ISection](../../isection/) στην οποία αναφέρεται το [Section](../../section/) πλαίσιο Zoom· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η εικόνα που θα εμφανιστεί μέσα στο [Section](../../section/) πλαίσιο Zoom. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).

## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός [Section](../../section/) αντικειμένου Zoom στον καθορισμένο δείκτη μιας συλλογής (υποθέτουμε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1), image);
```


## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISectionZoomFrame](../../isectionzoomframe/)
* Κλάση [ISection](../../isection/)
* Κλάση [ShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)