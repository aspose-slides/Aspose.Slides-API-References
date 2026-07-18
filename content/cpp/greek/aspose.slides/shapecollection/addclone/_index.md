---
title: AddClone()
second_title: Aspose.Slides για την αναφορά API C++
description: Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 547
url: /el/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) μέθοδος

Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το σχήμα προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του νέου σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του νέου σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του νέου σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του νέου σχήματος, σε σημεία. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) μέθοδος

Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το σχήμα προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του νέου σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του νέου σχήματος, σε σημεία. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) μέθοδος

Δημιουργεί ένα αντίγραφο του συγκεκριμένου σχήματος και το προσθέτει στο τέλος της συλλογής σχημάτων. Το κλωνοποιημένο σχήμα διατηρεί τη θέση και το μέγεθος του αρχικού.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IShape](../../ishape/).

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [ShapeCollection](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)