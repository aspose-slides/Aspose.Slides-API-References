---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie.
type: docs
weight: 495
url: /nl/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De vorm om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm\\u2019s, in points. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm\\u2019s, in points. |
| width | **float** | De breedte van het frame van de gekloonde vorm\\u2019s, in points. |
| height | **float** | De hoogte van het frame van de gekloonde vorm\\u2019s, in points. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |
| x | **float** | De x-coördinaat van het frame van de gekloonde vorm\\u2019s, in points. |
| y | **float** | De y-coördinaat van het frame van de gekloonde vorm\\u2019s, in points. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormcollectie. De gekloonde vorm behoudt de positie en grootte van het origineel\\u2019s.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | De [IShape](../../ishape/) om te klonen. |

### Retourwaarde

De nieuw aangemaakte [IShape](../../ishape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../ishape/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)