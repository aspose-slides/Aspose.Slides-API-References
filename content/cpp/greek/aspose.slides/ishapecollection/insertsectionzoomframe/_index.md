---
title: InsertSectionZoomFrame()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Δημιουργεί ένα νέο Section Zoom frame και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.
type: docs
weight: 131
url: /el/aspose.slides/ishapecollection/insertsectionzoomframe/
---
## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) Zoom frame και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το [Section](../../section/) Zoom frame. |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom frame, σε points. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom frame, σε points. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom frame, σε points. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom frame, σε points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) στο οποίο παραπέμπει το [Section](../../section/) Zoom frame· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).
## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός [Section](../../section/) Zoom αντικειμένου στη καθορισμένη θέση μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSectionZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
```


## IShapeCollection::InsertSectionZoomFrame(int32_t, float, float, float, float, System::SharedPtr\<ISection\>, System::SharedPtr\<IPPImage\>) μέθοδος


Δημιουργεί ένα νέο [Section](../../section/) Zoom frame με προορισμένη εικόνα και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<ISectionZoomFrame> Aspose::Slides::IShapeCollection::InsertSectionZoomFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<ISection> section, System::SharedPtr<IPPImage> image)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το [Section](../../section/) Zoom frame. |
| x | **float** | Η συντεταγμένη x του νέου [Section](../../section/) Zoom frame, σε points. |
| y | **float** | Η συντεταγμένη y του νέου [Section](../../section/) Zoom frame, σε points. |
| width | **float** | Το πλάτος του νέου [Section](../../section/) Zoom frame, σε points. |
| height | **float** | Το ύψος του νέου [Section](../../section/) Zoom frame, σε points. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | Το [ISection](../../isection/) στο οποίο παραπέμπει το [Section](../../section/) Zoom frame· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η εικόνα που θα εμφανιστεί μέσα στο [Section](../../section/) Zoom frame. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [ISectionZoomFrame](../../isectionzoomframe/).
## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει τη δημιουργία και την εισαγωγή ενός [Section](../../section/) Zoom αντικειμένου στη καθορισμένη θέση μιας συλλογής (υποθέστε ότι υπάρχουν τουλάχιστον δύο ενότητες στην παρουσίαση "Presentation.pptx"):
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
* Κλάση [IShapeCollection](../)
* Κλάση [IPPImage](../../ippimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)