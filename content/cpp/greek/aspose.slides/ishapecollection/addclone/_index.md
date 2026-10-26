---
title: AddClone()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 495
url: /el/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το σχήμα προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε points. |
| width | **float** | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε points. |
| height | **float** | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε points. |

### Τιμή επιστροφής

Το πρόσφατα δημιουργημένο [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε points. |

### Τιμή επιστροφής

Το πρόσφατα δημιουργημένο [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |

### Τιμή επιστροφής

Το πρόσφατα δημιουργημένο [IShape](../../ishape/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)