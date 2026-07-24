---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu.
type: docs
weight: 495
url: /de/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die zu klonende Form. |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form\\u2019s, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form\\u2019s, in Punkten. |
| width | **float** | Die Breite des Rahmens der geklonten Form\\u2019s, in Punkten. |
| height | **float** | Die Höhe des Rahmens der geklonten Form\\u2019s, in Punkten. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die neue Form behält die Breite und Höhe des *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zu klonen. |
| x | **float** | Die x-Koordinate des Rahmens der geklonten Form\\u2019s, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der geklonten Form\\u2019s, in Punkten. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) Methode

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die geklonte Form behält die ursprüngliche\\u2019s Position und Größe bei.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Die [IShape](../../ishape/) zu klonen. |

### Rückgabewert

Die neu erstellte [IShape](../../ishape/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)