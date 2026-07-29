---
title: AlignShapes()
second_title: Aspose.Slides för C++ API-referens
description: Ändrar placeringen av alla former på bilden. Justerar former mot marginalerna eller bildens kant eller justerar dem relativt till varandra.
type: docs
weight: 27
url: /sv/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) metod

Ändrar placeringen av alla former på bilden. Justerar former mot marginalerna eller bildens kant eller justerar dem relativt till varandra.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | **bool** | Om true, justeras former relativt till bildens kanter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Föräldrabild. |

## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) metod

Ändrar placeringen av alla former på bilden. Justerar former mot marginalerna eller bildens kant eller justerar dem relativt till varandra.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | **bool** | Om true, justeras former relativt till bildens kanter. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Föräldrabild. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Index för former som ska justeras. |

## Anmärkningar



Exempel: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) metod

Ändrar placeringen av alla former inom gruppformen. Justerar former mot marginalerna eller bildens kant eller justerar dem relativt till varandra.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | **bool** | Om true, justeras former relativt till bildens kanter. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Föräldragruppform. |

## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) metod

Ändrar placeringen av valda former inom gruppformen. Justerar former mot marginalerna eller bildens kant eller justerar dem relativt till varandra.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestämmer vilken typ av justering som ska tillämpas. |
| alignToSlide | **bool** | Om true, justeras former relativt till bildens kanter. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Föräldragruppform. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Index för former som ska justeras. |

## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Se även

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klass [SlideUtil](../)
* Klass [IGroupShape](../../../aspose.slides/igroupshape/)
* Namnrymd [Aspose::Slides::Util](../../)
* Bibliotek [Aspose.Slides](../../../)