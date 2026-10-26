---
title: AlignShapes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.
type: docs
weight: 27
url: /id/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) metode


Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Menentukan tipe penyelarasan yang akan diterapkan. |
| alignToSlide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slide induk. |
## Catatan



Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) metode


Mengubah penempatan bentuk yang dipilih pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Menentukan tipe penyelarasan yang akan diterapkan. |
| alignToSlide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slide induk. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indeks bentuk yang akan diselaraskan. |
## Catatan



Contoh: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) metode


Mengubah penempatan semua bentuk di dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Menentukan tipe penyelarasan yang akan diterapkan. |
| alignToSlide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Grup bentuk induk. |
## Catatan



Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) metode


Mengubah penempatan bentuk yang dipilih di dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskannya relatif satu sama lain.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Menentukan tipe penyelarasan yang akan diterapkan. |
| alignToSlide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Grup bentuk induk. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indeks bentuk yang akan diselaraskan. |
## Catatan



Contoh: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## Lihat Juga

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Kelas [SlideUtil](../)
* Kelas [IGroupShape](../../../aspose.slides/igroupshape/)
* Ruang Nama [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)