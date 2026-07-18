---
title: AddGroupShape()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας\u2019 θα προσαρμόζεται αυτόματα ώστε να χωράει τυχόν σχήματα που προστίθενται σε αυτό.
type: docs
weight: 391
url: /el/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() μέθοδος


Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμοστεί αυτόματα ώστε να χωρέσει τυχόν σχήματα που προστίθενται σε αυτό.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```


### Τιμή επιστροφής

Το νεοδημιουργημένο [IGroupShape](../../igroupshape/).

## Παρατηρήσεις



Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ένα σχήμα ομάδας σε μια διαφάνεια του PowerPoint [Presentation](../../presentation/). 
```cpp
// Δημιουργία αντικειμένου Presentation
auto pres = System::MakeObject<Presentation>();

// Λήψη της πρώτης διαφάνειας
auto slide = pres->get_Slides()->idx_get(0);
// Πρόσβαση στη συλλογή σχημάτων των διαφανειών
auto slideShapes = slide->get_Shapes();
// Προσθήκη σχήματος ομάδας στη διαφάνεια
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Προσθήκη σχημάτων μέσα στο προστιθέμενο σχήμα ομάδας
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Προσθήκη πλαισίου σχήματος ομάδας
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Αποθήκευση του αρχείου PPTX στο δίσκο
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) μέθοδος


Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε μεμονωμένα σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) που περιέχει διανυσματικό περιεχόμενο για μετατροπή σε σχήματα. |
| x | **float** | Η συντεταγμένη x του πλαισίου της ομάδας, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου της ομάδας, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου της ομάδας, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου της ομάδας, σε σημεία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IGroupShape](../../igroupshape/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGroupShape](../../igroupshape/)
* Κλάση [ShapeCollection](../)
* Κλάση [ISvgImage](../../isvgimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)