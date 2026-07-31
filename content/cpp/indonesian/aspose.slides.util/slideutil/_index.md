---
title: SlideUtil
second_title: Aspose.Slides untuk C++ Referensi API
description: Menawarkan metode yang membantu mencari bentuk dan teks dalam presentasi.
type: docs
weight: 14
url: /id/aspose.slides.util/slideutil/
---
## SlideUtil kelas

Menawarkan metode yang membantu mencari bentuk dan teks dalam presentasi.

```cpp
class SlideUtil
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskan mereka relatif satu sama lain. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Mengubah penempatan bentuk yang dipilih pada slide. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskan mereka relatif satu sama lain. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Mengubah penempatan semua bentuk dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskan mereka relatif satu sama lain. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Mengubah penempatan bentuk yang dipilih dalam grup bentuk. Menyelaraskan bentuk ke margin atau tepi slide atau menyelaraskan mereka relatif satu sama lain. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Menemukan dan mengganti teks dalam presentasi dengan format yang diberikan |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | Menemukan bentuk berdasarkan teks alternatif dalam presentasi PPTX. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | Menemukan bentuk berdasarkan teks alternatif pada slide dalam presentasi PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Mencari semua bentuk pada slide yang ditentukan yang cocok dengan tipe placeholder yang diberikan. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Mengembalikan semua bingkai teks pada slide dalam presentasi PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | Mengembalikan semua bingkai teks dalam presentasi PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Mengembalikan semua bingkai teks pada slide yang ditentukan yang berisi teks yang diberikan. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Mengkonversi format file sumber ke [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) yang sesuai. |
## Lihat Juga

* Ruang Nama [Aspose::Slides::Util](../)
* Perpustakaan [Aspose.Slides](../../)