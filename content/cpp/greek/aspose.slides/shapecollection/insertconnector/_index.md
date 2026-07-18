---
title: InsertConnector()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου.
type: docs
weight: 430
url: /el/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας το προεπιλεγμένο στυλ προτύπου.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στο οποίο θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσης που θα εισαχθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο σχήμα σύνδεσης και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση, εφαρμόζοντας προαιρετικά το προεπιλεγμένο στυλ προτύπου.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στο οποίο θα εισαχθεί το σχήμα σύνδεσης. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του σχήματος σύνδεσης που θα εισαχθεί. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σύνδεσμου, σε πόντους. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σύνδεσμου, σε πόντους. |
| width | **float** | Το πλάτος του πλαισίου του σύνδεσμου, σε πόντους. |
| height | **float** | Το ύψος του πλαισίου του σύνδεσμου, σε πόντους. |
| createFromTemplate | **bool** | Αληθές για την εφαρμογή του προεπιλεγμένου στυλ προτύπου (μη κενό όνομα, απλό στυλ); ψευδές για τη δημιουργία του σύνδεσμου με προεπιλεγμένες τιμές ιδιοτήτων. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IConnector](../../iconnector/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)