---
title: SlideUtil
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يوفر طرقًا تساعد في البحث عن الأشكال والنص في عرض تقديمي.
type: docs
weight: 14
url: /ar/aspose.slides.util/slideutil/
---
## SlideUtil فئة

يقدم طرقًا تساعد في البحث عن الأشكال والنص في عرض تقديمي.

```cpp
class SlideUtil
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | يغيّر موضع جميع الأشكال على الشريحة. يضبط الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها نسبةً إلى بعضها البعض. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | يغيّر موضع جميع الأشكال على الشريحة. يضبط الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها نسبةً إلى بعضها البعض. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | يغيّر موضع جميع الأشكال على الشريحة. يضبط الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها نسبةً إلى بعضها البعض. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | يغيّر موضع جميع الأشكال على الشريحة. يضبط الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها نسبةً إلى بعضها البعض. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | يبحث ويستبدل النص في العرض التقديمي بالتنسيق المحدد. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | العثور على الشكل بواسطة النص البديل في عرض PPTX. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | العثور على الشكل بواسطة النص البديل على شريحة في عرض PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | يبحث عن جميع الأشكال في الشريحة المحددة التي تطابق نوع العنصر النائب المحدد. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | يرجع جميع إطارات النص على شريحة في عرض PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | يرجع جميع إطارات النص في عرض PPTX. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | يرجع جميع إطارات النص على الشريحة المحددة التي تحتوي على النص المعطى. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | يحوّل تنسيق ملف المصدر إلى [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) المقابل. |

## انظر أيضًا

* نطاق الاسم [Aspose::Slides::Util](../)
* مكتبة [Aspose.Slides](../../)