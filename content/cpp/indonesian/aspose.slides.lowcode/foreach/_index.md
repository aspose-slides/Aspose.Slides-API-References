---
title: ForEach
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili sekumpulan metode yang ditujukan untuk mengiterasi berbagai objek model Presentation. Metode-metode ini dapat berguna jika Anda perlu mengiterasi dan mengubah pemformatan atau konten beberapa elemen Presentation' , misalnya mengubah pemformatan setiap bagian.
type: docs
weight: 40
url: /id/aspose.slides.lowcode/foreach/
---
## ForEach kelas

Mewakili sekelompok metode yang ditujukan untuk mengiterasi berbagai objek model [Presentation](../../aspose.slides/presentation/). Metode-metode ini dapat berguna jika Anda perlu mengiterasi dan mengubah pemformatan atau konten beberapa elemen [Presentation](../../aspose.slides/presentation/), misalnya mengubah pemformatan setiap bagian.

```cpp
class ForEach
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Iterasi setiap [ForEach::LayoutSlide](./layoutslide/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Iterasi setiap [ForEach::MasterSlide](./masterslide/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterasi setiap [ForEach::Paragraph](./paragraph/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Iterasi setiap [ForEach::Paragraph](./paragraph/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterasi setiap [ForEach::Portion](./portion/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Iterasi setiap [ForEach::Portion](./portion/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterasi setiap [ForEach::Shape](./shape/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterasi setiap [ForEach::Shape](./shape/) dalam [Presentation](../../aspose.slides/presentation/). |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Iterasi setiap [ForEach::Shape](./shape/) dalam [BaseSlide](../../aspose.slides/baseslide/). |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Iterasi setiap [ForEach::Slide](./slide/) dalam [Presentation](../../aspose.slides/presentation/). |

## Tipe-def

| Typedef | Deskripsi |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Callback yang akan dipanggil untuk setiap [ForEach::Slide](./slide/) dalam [Presentation](../../aspose.slides/presentation/). |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Callback yang akan dipanggil untuk setiap [ForEach::MasterSlide](./masterslide/) dalam [Presentation](../../aspose.slides/presentation/). |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Callback yang akan dipanggil untuk setiap [ForEach::LayoutSlide](./layoutslide/) dalam [Presentation](../../aspose.slides/presentation/). |
| [ForEachShapeCallback](./foreachshapecallback/) | Callback yang akan dipanggil untuk setiap [ForEach::Shape](./shape/) dalam [Presentation](../../aspose.slides/presentation/). |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Callback yang akan dipanggil untuk setiap [ForEach::Paragraph](./paragraph/) pada [BaseSlide](../../aspose.slides/baseslide/). |
| [ForEachPortionCallback](./foreachportioncallback/) | Callback yang akan dipanggil untuk setiap [ForEach::Portion](./portion/) dalam [ForEach::Paragraph](./paragraph/) pada [BaseSlide](../../aspose.slides/baseslide/). |

## Catatan



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

## Lihat Juga

* Ruang nama [Aspose::Slides::LowCode](../)
* Perpustakaan [Aspose.Slides](../../)