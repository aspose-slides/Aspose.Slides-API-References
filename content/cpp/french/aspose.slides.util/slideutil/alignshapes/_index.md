---
title: AlignShapes()
second_title: Référence de l'API Aspose.Slides for C++
description: Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.
type: docs
weight: 27
url: /fr/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) méthode

Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | **bool** | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositive parente. |

## Remarques



Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) méthode

Modifie le placement des formes sélectionnées sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | **bool** | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositive parente. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indices des formes à aligner. |

## Remarques



Exemple :
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) méthode

Modifie le placement de toutes les formes au sein du groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | **bool** | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Groupe de formes parent. |

## Remarques



Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) méthode

Modifie le placement des formes sélectionnées au sein du groupe de formes. Aligne les formes aux marges ou au bord de la diapositive ou les aligne les unes par rapport aux autres.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Détermine le type d'alignement qui sera appliqué. |
| alignToSlide | **bool** | Si vrai, les formes seront alignées par rapport aux bords de la diapositive. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Groupe de formes parent. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indices des formes à aligner. |

## Remarques



Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Voir aussi

* Énum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Classe [SlideUtil](../)
* Classe [IGroupShape](../../../aspose.slides/igroupshape/)
* Espace de noms [Aspose::Slides::Util](../../)
* Bibliothèque [Aspose.Slides](../../../)