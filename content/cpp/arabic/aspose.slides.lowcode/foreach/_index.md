---
title: ForEach
second_title: مرجع API Aspose.Slides للغة C++
description: يمثّل مجموعة من الأساليب المصممة للتكرار عبر كائنات نموذج Presentation المختلفة. يمكن أن تكون هذه الأساليب مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق أو محتوى بعض عناصر Presentation، على سبيل المثال تغيير تنسيق كل جزء.
type: docs
weight: 40
url: /ar/aspose.slides.lowcode/foreach/
---
## ForEach فئة

يمثل مجموعة من الأساليب المصممة للتكرار عبر كائنات النموذج [Presentation](../../aspose.slides/presentation/) المختلفة. يمكن أن تكون هذه الأساليب مفيدة إذا كنت بحاجة إلى التكرار وتغيير تنسيق أو محتوى بعض عناصر [Presentation](../../aspose.slides/presentation/)، مثل تغيير تنسيق كل جزء.

```cpp
class ForEach
```

## الطرق

| الطريقة | الوصف |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | تكرار كل [ForEach::LayoutSlide](./layoutslide/) في [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | تكرار كل [ForEach::MasterSlide](./masterslide/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | تكرار كل [ForEach::Paragraph](./paragraph/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | تكرار كل [ForEach::Paragraph](./paragraph/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | تكرار كل [ForEach::Portion](./portion/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | تكرار كل [ForEach::Portion](./portion/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | تكرار كل [ForEach::Shape](./shape/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | تكرار كل [ForEach::Shape](./shape/) في [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | تكرار كل [ForEach::Shape](./shape/) في [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | تكرار كل [ForEach::Slide](./slide/) في [Presentation](../../aspose.slides/presentation/). |

## تعريفات الأنواع

| تعريف نوع | الوصف |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::Slide](./slide/) في [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::MasterSlide](./masterslide/) في [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::LayoutSlide](./layoutslide/) في [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::Shape](./shape/) في [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::Paragraph](./paragraph/) على [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | استدعاء رد نداء سيُستدعى لكل [ForEach::Portion](./portion/) في [ForEach::Paragraph](./paragraph/) على [BaseSlide](../../aspose.slides/baseslide/). |

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* النطاق [Aspose::Slides::LowCode](../)
* المكتبة [Aspose.Slides](../../)