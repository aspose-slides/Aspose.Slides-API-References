---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an dem angegebenen Index ein.
type: docs
weight: 508
url: /de/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die geklonte Form eingefügt wird. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zum Klonen. |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der geklonten Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der geklonten Form, in Punkten. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein. Die neue Form behält die Breite und Höhe der *sourceShape* bei.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die geklonte Form eingefügt wird. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zum Klonen. |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form, in Punkten. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie in die Formsammlung an der angegebenen Position ein. Die geklonte Form behält die Position und Größe des Originals bei.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die geklonte Form eingefügt wird. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zum Klonen. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)