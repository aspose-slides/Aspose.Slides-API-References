---
title: AlignShapes()
second_title: Aspose.Slides pro C++ – reference API
description: Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k hraně snímku nebo je zarovnává vůči sobě navzájem.
type: docs
weight: 27
url: /cs/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) metoda


Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku, nebo je zarovnává vůči sobě navzájem.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Určuje, který typ zarovnání se použije. |
| alignToSlide | **bool** | Pokud je true, tvary budou zarovnány vůči okrajům snímku. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Nadřazený snímek. |
## Poznámky



Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) metoda


Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku, nebo je zarovnává vůči sobě navzájem.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Určuje, který typ zarovnání se použije. |
| alignToSlide | **bool** | Pokud je true, tvary budou zarovnány vůči okrajům snímku. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Nadřazený snímek. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexy tvarů, které mají být zarovnány. |
## Poznámky



Příklad: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) metoda


Mění umístění všech tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku, nebo je zarovnává vůči sobě navzájem.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Určuje, který typ zarovnání se použije. |
| alignToSlide | **bool** | Pokud je true, tvary budou zarovnány vůči okrajům snímku. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Nadřazený skupinový tvar. |
## Poznámky



Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) metoda


Mění umístění vybraných tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku, nebo je zarovnává vůči sobě navzájem.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Určuje, který typ zarovnání se použije. |
| alignToSlide | **bool** | Pokud je true, tvary budou zarovnány vůči okrajům snímku. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Nadřazený skupinový tvar. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexy tvarů, které mají být zarovnány. |
## Poznámky



Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## See Also

* Výčet [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Třída [SlideUtil](../)
* Třída [IGroupShape](../../../aspose.slides/igroupshape/)
* Jmenný prostor [Aspose::Slides::Util](../../)
* Knihovna [Aspose.Slides](../../../)