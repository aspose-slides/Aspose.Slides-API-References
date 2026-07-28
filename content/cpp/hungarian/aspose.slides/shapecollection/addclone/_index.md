---
title: AddClone()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez.
type: docs
weight: 547
url: /hu/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metódus


Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó alakzat. |
| x | **float** | Az új alakzat keretének x-koordinátája pontokban. |
| y | **float** | Az új alakzat keretének y-koordinátája pontokban. |
| width | **float** | Az új alakzat keretének szélessége pontokban. |
| height | **float** | Az új alakzat keretének magassága pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metódus


Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez. Az új alakzat megőrzi a *sourceShape* szélességét és magasságát.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó alakzat. |
| x | **float** | Az új alakzat keretének x-koordinátája pontokban. |
| y | **float** | Az új alakzat keretének y-koordinátája pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) metódus


Létrehoz egy másolatot a megadott alakzatról, és hozzáadja az alakzatgyűjtemény végéhez. A klónozott alakzat megtartja az eredeti pozícióját és méretét.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A [IShape](../../ishape/) a klónozáshoz. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)