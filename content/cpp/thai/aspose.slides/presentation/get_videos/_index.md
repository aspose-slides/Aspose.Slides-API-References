---
title: get_Videos()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว IVideoCollection.
type: docs
weight: 235
url: /th/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() เมธอด

ส่งคืนคอลเลกชันของไฟล์วิดีโอที่ฝังทั้งหมดในงานนำเสนอ. อ่านอย่างเดียว [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีสร้าง [Video](../../video/) Frame ที่ฝังใน PowerPoint [Presentation](../). 
```cpp
// สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์ PPTX
auto pres = System::MakeObject<Presentation>();

// รับสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);

// ฝังวิดีโอในงานนำเสนอ
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// เพิ่ม Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// ตั้งค่าวิดีโอให้กับ Video Frame
vf->set_EmbeddedVideo(video);
// ตั้งโหมดการเล่นและระดับเสียงของวิดีโอ

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// บันทึกไฟล์ PPTX ลงดิสก์
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มวิดีโอโดยส่งพาธไปยังไฟล์วิดีโอตรงเข้า AddVideoFrame เมธอดสำหรับ PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มไฟล์ขนาดใหญ่ผ่าน BLOB ไปยัง [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// สร้างการนำเสนอใหม่ที่วิดีโอจะถูกเพิ่มเข้ามา
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// เราจะเพิ่มวิดีโอลงในงานนำเสนอ - เราเลือกพฤติกรรม KeepLocked เพราะเราต้องการ
// ไม่ได้ตั้งใจเข้าถึงไฟล์ "veryLargeVideo.avi"
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// บันทึกการนำเสนอ ขณะที่การนำเสนอขนาดใหญ่ถูกส่งออก การใช้หน่วยความจำยังคงต่ำ
// คงที่ต่ำตลอดอายุการใช้งานของอ็อบเจ็กต์ pres
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีส่งออกไฟล์ขนาดใหญ่ผ่าน BLOB จาก PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// สร้างอินสแตนซ์ Presentation และล็อคไฟล์ "hugePresentationWithAudiosAndVideos.pptx"
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// เราจะบันทึกแต่ละวิดีโอลงไฟล์ เพื่อป้องกันการใช้หน่วยความจำสูง เราต้องการบัฟเฟอร์ที่จะใช้
// เพื่อโอนย้ายข้อมูลจากสตรีมวิดีโอของงานนำเสนอไปยังสตรีมของไฟล์วิดีโอใหม่ที่สร้าง
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// วนซ้ำผ่านวิดีโอต่างๆ
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // เปิดสตรีมวิดีโอของงานนำเสนอ โปรดทราบว่าเราตั้งใจหลีกเลี่ยงการเข้าถึงคุณสมบัติ
    // อย่าง video.BinaryData - เนื่องจากคุณสมบัตินี้คืนอาเรย์ของไบต์ที่มีวิดีโอเต็ม ซึ่ง
    // ทำให้ไบต์ถูกโหลดเข้าเมมโมรี เราใช้ video.GetStream ซึ่งจะคืนค่า Stream - และไม่ได้
    //  ต้องการให้เราต้องโหลดวิดีโอทั้งหมดเข้าเมมโมรี
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // การใช้หน่วยความจำจะคงที่ต่ำไม่ว่าจะเป็นขนาดของวิดีโอหรือการนำเสนอ,
}
// หากจำเป็นคุณสามารถใช้ขั้นตอนเดียวกันกับไฟล์เสียงได้.
```
 ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มไฮเปอร์ลิงก์ไปยังวิดีโอใน PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีสร้าง [Video](../../video/) Frame ด้วย [Video](../../video/) จากแหล่งเว็บใน PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // เพิ่ม videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // โหลดภาพย่อ
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 ตัวอย่างต่อไปนี้แสดงวิธีดึง [Video](../../video/) จากสไลด์ของ PowerPoint [Presentation](../). 
```cpp
// สร้างอ็อบเจกต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
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

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IVideoCollection](../../ivideocollection/)
* คลาส [Presentation](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)