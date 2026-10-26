---
title: InsertConnector()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη, εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου.
type: docs
weight: 391
url: /el/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση, εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσμου προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσμου και το εισάγει στη συλλογή σχημάτων στην καθορισμένη θέση, προαιρετικά εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το σχήμα σύνδεσμου. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσμου προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε σημεία. |
| createFromTemplate | **bool** | True για να εφαρμόσει το προεπιλεγμένο στυλ προτύπου (μη κενό όνομα, απλό στυλ); false για να δημιουργήσει το σύνδεσμο με τις προεπιλεγμένες τιμές ιδιοτήτων. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IConnector](../../iconnector/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IConnector](../../iconnector/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)