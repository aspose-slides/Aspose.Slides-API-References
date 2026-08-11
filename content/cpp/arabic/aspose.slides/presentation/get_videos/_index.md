---
title: get_Videos()
second_title: Aspose.Slides لمرجع API C++
description: تُعيد مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. للقراءة فقط IVideoCollection.
type: docs
weight: 235
url: /ar/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() طريقة

تُعيد مجموعة جميع ملفات الفيديو المدمجة في العرض التقديمي. للقراءة فقط [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## ملاحظات

تظهر الأمثلة التالية كيفية إنشاء إطار [Video](../../video/) مدمج في PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن من فئة Presentation التي تمثل ملف PPTX
auto pres = System::MakeObject<Presentation>();

// الحصول على الشريحة الأولى
auto slide = pres->get_Slides()->idx_get(0);

// إدراج فيديو داخل العرض التقديمي
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// إضافة إطار فيديو
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// تعيين الفيديو لإطار الفيديو
vf->set_EmbeddedVideo(video);
// تعيين وضع التشغيل وحجم الصوت للفيديو

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// كتابة ملف PPTX إلى القرص
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
تظهر الأمثلة التالية כיצד إضافة فيديو بتمرير مسار ملف الفيديو مباشرة إلى طريقة AddVideoFrame لPowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
تظهر الأمثلة التالية كيفية إضافة ملف كبير عبر BLOB إلى [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// ينشئ عرضًا تقديميًا جديدًا سيتم إضافة الفيديو إليه
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// لنضيف الفيديو إلى العرض التقديمي - اخترنا سلوك KeepLocked لأننا
// لا ننوي الوصول إلى ملف "veryLargeVideo.avi".
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// يحفظ العرض التقديمي. أثناء إخراج عرض تقديمي كبير,
// يبقى استهلاك الذاكرة منخفضًا طوال دورة حياة كائن pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
تظهر الأمثلة التالية كيفية تصدير ملف كبير عبر BLOB من PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// ينشئ مثيلًا لـ Presentation، ويقفل ملف "hugePresentationWithAudiosAndVideos.pptx".
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// لنحفظ كل فيديو في ملف. لتجنب استهلاك عالي للذاكرة، نحتاج إلى مخزن مؤقت سيُستخدم
// لنقل البيانات من تدفق الفيديو في العرض التقديمي إلى تدفق لملف فيديو تم إنشاؤه حديثًا.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// يتكرّر عبر الفيديوهات
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // يفتح تدفق فيديو العرض التقديمي. يرجى ملاحظة أننا تجنبنا عمدًا الوصول إلى الخصائص
    // مثل video.BinaryData - لأن هذه الخاصية تُرجع مصفوفة بايت تحتوي على الفيديو بالكامل، مما يؤدي إلى
    // تحميل البايتات إلى الذاكرة. نستخدم video.GetStream، التي تُرجع Stream - ولا
    // تتطلب تحميل الفيديو الكامل إلى الذاكرة.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // ستظل استهلاكات الذاكرة منخفضة بغض النظر عن حجم الفيديو أو العرض التقديمي،
}
// إذا لزم الأمر، يمكنك تطبيق نفس الخطوات على ملفات الصوت.
```
تظهر الأمثلة التالية كيفية إضافة ارتباط تشعبي إلى فيديو في PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
تظهر الأمثلة التالية كيفية إنشاء إطار [Video](../../video/) مع [Video](../../video/) من مصدر ويب في PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // إضافة إطار فيديو
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // تحميل الصورة المصغرة
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
تظهر الأمثلة التالية كيفية استخراج [Video](../../video/) من شريحة PowerPoint [Presentation](../). 
```cpp
// إنشاء كائن Presentation يمثل ملف عرض تقديمي
auto presentation = System::MakeObject<Presentation>(u"Video.pptx");

for (auto&& slide : presentation->get_Slides())
{
    for (auto&& shape : slide->get_Shapes())
    {
        if (System::ObjectExt::Is<VideoFrame>(shape))
        {
            System::SharedPtr<IVideoFrame> vf = System::AsCast<IVideoFrame>(shape);
            System::String type = vf->get_EmbeddedVideo()->get_ContentType();
            int32_t ss = type.LastIndexOf(u'/');
            type = type.Remove(0, type.LastIndexOf(u'/') + 1);
            System::ArrayPtr<uint8_t> buffer = vf->get_EmbeddedVideo()->get_BinaryData();
            auto stream = System::MakeObject<System::IO::FileStream>(System::String(u"NewVideo_out.") + type,
                                                                     System::IO::FileMode::Create,
                                                                     System::IO::FileAccess::Write,
                                                                     System::IO::FileShare::Read);
            stream->Write(buffer, 0, buffer->get_Length());
        }
    }
}
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IVideoCollection](../../ivideocollection/)
* فئة [Presentation](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)