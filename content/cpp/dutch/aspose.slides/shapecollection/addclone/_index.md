---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie.
type: docs
weight: 547
url: /nl/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) methode


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De vorm die gekloond moet worden. |
| x | **float** | Het x-coördinaat van het kader van de nieuwe vorm, in punten. |
| y | **float** | Het y-coördinaat van het kader van de nieuwe vorm, in punten. |
| width | **float** | De breedte van het kader van de nieuwe vorm, in punten. |
| height | **float** | De hoogte van het kader van de nieuwe vorm, in punten. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) methode


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De vorm die gekloond moet worden. |
| x | **float** | Het x-coördinaat van het kader van de nieuwe vorm, in punten. |
| y | **float** | Het y-coördinaat van het kader van de nieuwe vorm, in punten. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) methode


Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie. De geklonde vorm behoudt de oorspronkelijke positie en grootte.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) die gekloond moet worden. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)