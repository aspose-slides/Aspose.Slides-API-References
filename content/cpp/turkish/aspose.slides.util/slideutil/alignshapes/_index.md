---
title: AlignShapes()
second_title: Aspose.Slides for C++ API Referansı
description: Slayttaki tüm şekillerin yerleşimini değiştirir. Şekilleri kenar boşluklarına veya slayt kenarına hizalar veya birbirlerine göre hizalar.
type: docs
weight: 27
url: /tr/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) metod

Slayttaki tüm şekillerin yerleşimini değiştirir. Şekilleri kenar boşluklarına veya slayt kenarına hizalar veya birbirlerine göre hizalar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | **bool** | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Üst slayt. |
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) metod

Seçili şekillerin slayttaki yerleşimini değiştirir. Şekilleri kenar boşluklarına veya slayt kenarına hizalar veya birbirlerine göre hizalar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | **bool** | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Üst slayt. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Hizalanacak şekillerin dizinleri. |
## Açıklamalar



Örnek: 
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

Grup şekli içindeki tüm şekillerin yerleşimini değiştirir. Şekilleri kenar boşluklarına veya slayt kenarına hizalar veya birbirlerine göre hizalar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | **bool** | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Üst grup şekli. |
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) metod

Grup şekli içinde seçili şekillerin yerleşimini değiştirir. Şekilleri kenar boşluklarına veya slayt kenarına hizalar veya birbirlerine göre hizalar.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Hangi hizalama türünün uygulanacağını belirler. |
| alignToSlide | **bool** | Doğruysa, şekiller slayt kenarlarına göre hizalanır. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Üst grup şekli. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Hizalanacak şekillerin dizinleri. |
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Ayrıca Bakınız

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Sınıf [SlideUtil](../)
* Sınıf [IGroupShape](../../../aspose.slides/igroupshape/)
* Ad alanı [Aspose::Slides::Util](../../)
* Kütüphane [Aspose.Slides](../../../)