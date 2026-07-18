---
title: InsertClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη.
type: docs
weight: 560
url: /el/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του κλωνοποιημένου σχήματος, σε σημεία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του πρωτότυπου\\u2019s.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο μηδενικός δείκτης στο οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IShape](../../ishape/).

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)