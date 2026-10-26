---
title: InsertClone()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 508
url: /el/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | **float** | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| width | **float** | Το πλάτος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| height | **float** | Το ύψος του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

### Τιμή Επιστροφής

Το νεοδημιούργητο [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το νέο σχήμα διατηρεί το πλάτος και το ύψος του *sourceShape*.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |
| x | **float** | Η συντεταγμένη x του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |
| y | **float** | Η συντεταγμένη y του πλαισίου του κλωνοποιημένου σχήματος, σε πόντους. |

### Τιμή Επιστροφής

Το νεοδημιούργητο [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) μέθοδος


Δημιουργεί ένα αντίγραφο του καθορισμένου σχήματος και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Το κλωνοποιημένο σχήμα διατηρεί την αρχική θέση και μέγεθος.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το κλωνοποιημένο σχήμα. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Το [IShape](../../ishape/) προς κλωνοποίηση. |

### Τιμή Επιστροφής

Το νεοδημιούργητο [IShape](../../ishape/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)