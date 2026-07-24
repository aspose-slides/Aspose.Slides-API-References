---
title: AlignShapes()
second_title: Aspose.Slides für C++ API-Referenz
description: Ändert die Position aller Formen auf der Folie. Richten Sie Formen an den Rändern oder am Rand der Folie aus oder richten Sie sie relativ zueinander aus.
type: docs
weight: 27
url: /de/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) Methode

Ändert die Position aller Formen auf der Folie. Richten Sie Formen an den Rändern oder am Rand der Folie aus oder richten Sie sie relativ zueinander aus.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | **bool** | Wenn true, werden Formen relativ zu den Folienkanten ausgerichtet. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Übergeordnete Folie. |

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) Methode

Ändert die Position der ausgewählten Formen auf der Folie. Richten Sie Formen an den Rändern oder am Rand der Folie aus oder richten Sie sie relativ zueinander aus.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | **bool** | Wenn true, werden Formen relativ zu den Folienkanten ausgerichtet. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Übergeordnete Folie. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indizes der Formen, die ausgerichtet werden sollen. |

## Bemerkungen

Beispiel: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) Methode

Ändert die Position aller Formen innerhalb einer Gruppierung. Richten Sie Formen an den Rändern oder am Rand der Folie aus oder richten Sie sie relativ zueinander aus.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | **bool** | Wenn true, werden Formen relativ zu den Folienkanten ausgerichtet. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Übergeordnete Gruppierung. |

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) Methode

Ändert die Position der ausgewählten Formen innerhalb einer Gruppierung. Richten Sie Formen an den Rändern oder am Rand der Folie aus oder richten Sie sie relativ zueinander aus.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Bestimmt, welcher Ausrichtungstyp angewendet wird. |
| alignToSlide | **bool** | Wenn true, werden Formen relativ zu den Folienkanten ausgerichtet. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Übergeordnete Gruppierung. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indizes der Formen, die ausgerichtet werden sollen. |

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Siehe auch

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klasse [SlideUtil](../)
* Klasse [IGroupShape](../../../aspose.slides/igroupshape/)
* Namensraum [Aspose::Slides::Util](../../)
* Bibliothek [Aspose.Slides](../../../)