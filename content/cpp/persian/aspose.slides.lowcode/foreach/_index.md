---
title: ForEach
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر یک گروه از متدهایی است که برای پیمایش اشیاء مدل Presentation طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به پیمایش و تغییر قالب‌بندی یا محتوای برخی عناصر Presentation داشته باشید، به عنوان مثال تغییر قالب‌بندی هر بخش.
type: docs
weight: 40
url: /fa/aspose.slides.lowcode/foreach/
---
## کلاس ForEach

نمایشگر گروهی از متدها که برای پیمایش اشیاء مدل [Presentation](../../aspose.slides/presentation/) مختلف طراحی شده‌اند. این متدها می‌توانند مفید باشند اگر نیاز به پیمایش و تغییر فرمت یا محتوای برخی عناصر [Presentation](../../aspose.slides/presentation/) داشته باشید، برای مثال تغییر فرمت هر بخش.

```cpp
class ForEach
```

## متدها

| Method | Description |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | هر [ForEach::LayoutSlide](./layoutslide/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | هر [ForEach::MasterSlide](./masterslide/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | هر [ForEach::Paragraph](./paragraph/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | هر [ForEach::Paragraph](./paragraph/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | هر [ForEach::Portion](./portion/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | هر [ForEach::Portion](./portion/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | هر [ForEach::Shape](./shape/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | هر [ForEach::Shape](./shape/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | هر [ForEach::Shape](./shape/) در [BaseSlide](../../aspose.slides/baseslide/) را پیمایش کنید. |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | هر [ForEach::Slide](./slide/) در [Presentation](../../aspose.slides/presentation/) را پیمایش کنید. |

## تعاریف نوع

| Typedef | Description |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | بازگشت‌خوانی که برای هر [ForEach::Slide](./slide/) در [Presentation](../../aspose.slides/presentation/) فراخوانی می‌شود. |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | بازگشت‌خوانی که برای هر [ForEach::MasterSlide](./masterslide/) در [Presentation](../../aspose.slides/presentation/) فراخوانی می‌شود. |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | بازگشت‌خوانی که برای هر [ForEach::LayoutSlide](./layoutslide/) در [Presentation](../../aspose.slides/presentation/) فراخوانی می‌شود. |
| [ForEachShapeCallback](./foreachshapecallback/) | بازگشت‌خوانی که برای هر [ForEach::Shape](./shape/) در [Presentation](../../aspose.slides/presentation/) فراخوانی می‌شود. |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | بازگشت‌خوانی که برای هر [ForEach::Paragraph](./paragraph/) بر روی [BaseSlide](../../aspose.slides/baseslide/) فراخوانی می‌شود. |
| [ForEachPortionCallback](./foreachportioncallback/) | بازگشت‌خوانی که برای هر [ForEach::Portion](./portion/) در [ForEach::Paragraph](./paragraph/) بر روی [BaseSlide](../../aspose.slides/baseslide/) فراخوانی می‌شود. |

## توضیحات

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

## موارد مرتبط

* فضایی [Aspose::Slides::LowCode](../)
* کتابخانه [Aspose.Slides](../../)