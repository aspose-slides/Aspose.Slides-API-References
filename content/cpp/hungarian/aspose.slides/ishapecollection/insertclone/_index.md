---
title: InsertClone()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza a megadott alakzat másolatát, és beilleszti az alakzatgyűjteménybe a megadott indexnél.
type: docs
weight: 508
url: /hu/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metódus


Létrehozza a megadott alakzat másolatát, és beilleszti az alakzatgyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullártól kezdődő index, amelynél a klónozott alakzatot be kell illeszteni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó [IShape](../../ishape/). |
| x | **float** | A klónozott alakzat\\u2019s keretének x-koordinátája, pontokban. |
| y | **float** | A klónozott alakzat\\u2019s keretének y-koordinátája, pontokban. |
| width | **float** | A klónozott alakzat\\u2019s keretének szélessége, pontokban. |
| height | **float** | A klónozott alakzat\\u2019s keretének magassága, pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metódus


Létrehozza a megadott alakzat másolatát, és beilleszti az alakzatgyűjteménybe a megadott indexnél. Az új alakzat megtartja a *sourceShape* szélességét és magasságát.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullártól kezdődő index, amelynél a klónozott alakzatot be kell illeszteni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó [IShape](../../ishape/). |
| x | **float** | A klónozott alakzat\\u2019s keretének x-koordinátája, pontokban. |
| y | **float** | A klónozott alakzat\\u2019s keretének y-koordinátája, pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metódus


Létrehozza a megadott alakzat másolatát, és beilleszti az alakzatgyűjteménybe a megadott indexnél. A klónozott alakzat megtartja az eredeti pozícióját és méretét.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullártól kezdődő index, amelynél a klónozott alakzatot be kell illeszteni. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A klónozandó [IShape](../../ishape/). |

### Visszatérési érték

Az újonnan létrehozott [IShape](../../ishape/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IShape](../../ishape/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)