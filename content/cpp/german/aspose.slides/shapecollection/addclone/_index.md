---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu.
type: docs
weight: 547
url: /de/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die Form, die geklont werden soll. |
| x | **float** | Die x-Koordinate des Rahmens der neuen Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der neuen Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der neuen Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der neuen Form, in Punkten. |

### Rückgabewert

Das neu erstellte [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die neue Form behält die Breite und Höhe der *sourceShape* bei.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die Form, die geklont werden soll. |
| x | **float** | Die x-Koordinate des Rahmens der neuen Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der neuen Form, in Punkten. |

### Rückgabewert

Das neu erstellte [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die geklonte Form behält die Position und Größe des Originals bei.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Der [IShape](../../ishape/) zum Klonen. |

### Rückgabewert

Das neu erstellte [IShape](../../ishape/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)