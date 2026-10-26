---
title: AddClone()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez.
type: docs
weight: 495
url: /hu/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metódus

Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó alakzat. |
| x | **float** | A klónozott alakzat keretének x koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y koordinátája pontban. |
| width | **float** | A klónozott alakzat keretének szélessége pontban. |
| height | **float** | A klónozott alakzat keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metódus

Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez. Az új alakzat megtartja a *sourceShape* szélességét és magasságát.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) klónozandó. |
| x | **float** | A klónozott alakzat keretének x koordinátája pontban. |
| y | **float** | A klónozott alakzat keretének y koordinátája pontban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metódus

Létrehozza a megadott alakzat másolatát, és hozzáadja az alakzatgyűjtemény végéhez. A klónozott alakzat megtartja az eredeti pozícióját és méretét.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) klónozandó. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)