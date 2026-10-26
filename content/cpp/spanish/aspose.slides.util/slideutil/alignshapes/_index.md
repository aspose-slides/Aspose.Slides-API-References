---
title: AlignShapes()
second_title: Referencia de API de Aspose.Slides para C++
description: Cambia la posición de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.
type: docs
weight: 27
url: /es/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) método


Cambia la posición de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determina qué tipo de alineación se aplicará. |
| alignToSlide | **bool** | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositiva principal. |
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) método


Cambia la posición de las formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determina qué tipo de alineación se aplicará. |
| alignToSlide | **bool** | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Diapositiva principal. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Índices de las formas que se alinearán. |
## Observaciones



Ejemplo: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) método


Cambia la posición de todas las formas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determina qué tipo de alineación se aplicará. |
| alignToSlide | **bool** | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Grupo de formas principal. |
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) método


Cambia la posición de las formas seleccionadas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva o las alinea entre sí.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determina qué tipo de alineación se aplicará. |
| alignToSlide | **bool** | Si es true, las formas se alinearán respecto a los bordes de la diapositiva. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Grupo de formas principal. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Índices de las formas que se alinearán. |
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Ver también

* Enumeración [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Clase [SlideUtil](../)
* Clase [IGroupShape](../../../aspose.slides/igroupshape/)
* Espacio de nombres [Aspose::Slides::Util](../../)
* Biblioteca [Aspose.Slides](../../../)