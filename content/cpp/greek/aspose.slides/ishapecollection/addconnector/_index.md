---
title: AddConnector()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στιλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 378
url: /el/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσης με προεπιλεγμένο στιλ προτύπου και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσης που θα προστεθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου της σύνδεσης, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου της σύνδεσης, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου της σύνδεσης, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου της σύνδεσης, σε σημεία. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσης και το προσθέτει στο τέλος της συλλογής σχημάτων, με δυνατότητα εφαρμογής προεπιλεγμένου στιλ προτύπου.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσης που θα δημιουργηθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου της σύνδεσης, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου της σύνδεσης, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου της σύνδεσης, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου της σύνδεσης, σε σημεία. |
| createFromTemplate | **bool** | Αληθές για να εφαρμόσει το προεπιλεγμένο στιλ προτύπου (μη κενό όνομα, απλό στυλ); ψευδές για να δημιουργήσει τη σύνδεση με προεπιλεγμένες τιμές ιδιοτήτων. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IConnector](../../iconnector/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)