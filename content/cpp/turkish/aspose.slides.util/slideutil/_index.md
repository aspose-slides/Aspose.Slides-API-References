---
title: SlideUtil
second_title: Aspose.Slides için C++ API Referansı
description: Sunumda şekil ve metin aramaya yardımcı yöntemler sunar.
type: docs
weight: 14
url: /tr/aspose.slides.util/slideutil/
---
## SlideUtil sınıfı


Sunumda şekil ve metin aramaya yardımcı yöntemler sunar.

```cpp
class SlideUtil
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | Slayttaki tüm şekillerin yerleşimini değiştirir. Şekilleri slayt kenar boşluklarına veya slayt kenarına hizalar ya da birbirlerine göre hizalar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Seçili şekillerin slayttaki yerleşimini değiştirir. Şekilleri slayt kenar boşluklarına veya slayt kenarına hizalar ya da birbirlerine göre hizalar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | Grup şekli içindeki tüm şekillerin yerleşimini değiştirir. Şekilleri slayt kenar boşluklarına veya slayt kenarına hizalar ya da birbirlerine göre hizalar. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | Grup şekli içindeki seçili şekillerin yerleşimini değiştirir. Şekilleri slayt kenar boşluklarına veya slayt kenarına hizalar ya da birbirlerine göre hizalar. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | Sunum içinde verilen formatla metni bulur ve değiştirir. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | PPTX sunumunda alternatif metne göre şekil bulur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | PPTX sunumundaki bir slaytta alternatif metne göre şekil bulur. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | Belirtilen slaytta verilen yer tutucu türüne uyan tüm şekilleri arar. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | PPTX sunumundaki bir slaytta tüm metin çerçevelerini döndürür. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | PPTX sunumundaki tüm metin çerçevelerini döndürür. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | Belirtilen slaytta verilen metni içeren tüm metin çerçevelerini döndürür. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | Kaynak dosya formatını karşılık gelen [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) biçimine dönüştürür. |
## Ayrıca Bakınız

* Ad alanı [Aspose::Slides::Util](../)
* Kütüphane [Aspose.Slides](../../)