---
title: SlideUtil
second_title: Aspose.Slides برای C++ مرجع API
description: متدهایی را ارائه می‌دهد که به جستجوی اشکال و متن در یک ارائه کمک می‌کنند.
type: docs
weight: 14
url: /fa/aspose.slides.util/slideutil/
---
## کلاس SlideUtil

متدهایی را ارائه می‌دهد که به جستجوی اشکال و متن در یک ارائه کمک می‌کنند.

```cpp
class SlideUtil
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | محل قرارگیری تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | محل قرارگیری اشکال انتخاب شده روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>) | محل قرارگیری تمام اشکال درون شکل گروه را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند. |
| static void [AlignShapes](./alignshapes/)([ShapesAlignmentType](../../aspose.slides/shapesalignmenttype/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | محل قرارگیری اشکال انتخاب شده درون شکل گروه را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند. |
| static void [FindAndReplaceText](./findandreplacetext/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**, [System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[PortionFormat](../../aspose.slides/portionformat/)\>) | متن را در ارائه پیدا کرده و با قالب‌گذاری داده‌شده جایگزین می‌کند |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, [System::String](../../system/string/)) | شکل را بر اساس متن جایگزین در یک ارائه PPTX پیدا می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [FindShape](./findshape/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/)) | شکل را بر اساس متن جایگزین در یک اسلاید از ارائه PPTX پیدا می‌کند. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>\> [FindShapesByPlaceholderType](./findshapesbyplaceholdertype/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [PlaceholderType](../../aspose.slides/placeholdertype/)) | تمام اشکالی را که در اسلاید مشخص‌شده با نوع جایگزین داده‌شده مطابقت دارند، جستجو می‌کند. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextBoxes](./getalltextboxes/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>) | تمام قاب‌های متن روی یک اسلاید در ارائه PPTX را برمی‌گرداند. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetAllTextFrames](./getalltextframes/)([System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>, **bool**) | تمام قاب‌های متن در یک ارائه PPTX را برمی‌گرداند. |
| static [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\>\> [GetTextBoxesContainsText](./gettextboxescontainstext/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\>, [System::String](../../system/string/), **bool**) | تمام قاب‌های متن روی اسلاید مشخص‌شده که متن داده‌شده را شامل می‌شوند، برمی‌گرداند. |
|  [SlideUtil](./slideutil/)() |  |
| static [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) [ToSaveFormat](./tosaveformat/)([SourceFormat](../../aspose.slides/sourceformat/)) | فرمت فایل منبع را به [Aspose::Slides::Export::SaveFormat](../../aspose.slides.export/saveformat/) متناظر تبدیل می‌کند. |

## موارد مرتبط

* فضای نام [Aspose::Slides::Util](../)
* کتابخانه [Aspose.Slides](../../)