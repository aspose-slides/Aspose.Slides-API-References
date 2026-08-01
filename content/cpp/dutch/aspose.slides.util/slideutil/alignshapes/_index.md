---
title: AlignShapes()
second_title: Aspose.Slides voor C++ API-referentie
description: Wijzigt de plaatsing van alle vormen op de dia. Rangschikt vormen op de marges of de rand van de dia of rangschikt ze relatief ten opzichte van elkaar.
type: docs
weight: 27
url: /nl/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) methode


Wijzigt de plaatsing van alle vormen op de dia. Rangschikt vormen op de marges of de rand van de dia of rangschikt ze relatief ten opzichte van elkaar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bepaalt welk type uitlijning zal worden toegepast. |
| alignToSlide | **bool** | Indien true, worden vormen uitgelijnd ten opzichte van de randen van de dia. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Bovenliggende dia. |
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) methode


Wijzigt de plaatsing van geselecteerde vormen op de dia. Rangschikt vormen op de marges of de rand van de dia of rangschikt ze relatief ten opzichte van elkaar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bepaalt welk type uitlijning zal worden toegepast. |
| alignToSlide | **bool** | Indien true, worden vormen uitgelijnd ten opzichte van de randen van de dia. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Bovenliggende dia. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexen van vormen die uitgelijnd moeten worden. |
## Opmerkingen



Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slide = pres->get_Slides()->idx_get(0);
auto shape1 = slide->get_Shapes()->idx_get(0);
auto shape2 = slide->get_Shapes()->idx_get(1);
SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, false, pres->get_Slides()->idx_get(0),
    System::MakeArray<int32_t>({
        slide->get_Shapes()->IndexOf(shape1),
        slide->get_Shapes()->IndexOf(shape2)
    }));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) methode


Wijzigt de plaatsing van alle vormen binnen een groepsvorm. Rangschikt vormen op de marges of de rand van de dia of rangschikt ze relatief ten opzichte van elkaar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bepaalt welk type uitlijning zal worden toegepast. |
| alignToSlide | **bool** | Indien true, worden vormen uitgelijnd ten opzichte van de randen van de dia. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Bovenliggende groepsvorm. |
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) methode


Wijzigt de plaatsing van geselecteerde vormen binnen een groepsvorm. Rangschikt vormen op de marges of de rand van de dia of rangschikt ze relatief ten opzichte van elkaar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bepaalt welk type uitlijning zal worden toegepast. |
| alignToSlide | **bool** | Indien true, worden vormen uitgelijnd ten opzichte van de randen van de dia. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Bovenliggende groepsvorm. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexen van vormen die uitgelijnd moeten worden. |
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Zie ook

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)