---
title: get_Videos()
second_title: Aspose.Slides for C++ API Reference
description: Returns the collection of all embedded video files in the presentation. Read-only IVideoCollection.
type: docs
weight: 235
url: /aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() method


Returns the collection of all embedded video files in the presentation. Read-only [IVideoCollection](../../ivideocollection/).

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## Remarks


The following examples shows how to create embedded [Video](../../video/) Frame in a PowerPoint [Presentation](../). 
```cpp
// Instantiate Presentation class that represents the PPTX
auto pres = System::MakeObject<Presentation>();

// Get the first slide
auto slide = pres->get_Slides()->idx_get(0);

// Embed video inside presentation
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// Add Video Frame
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// Set video to Video Frame
vf->set_EmbeddedVideo(video);
// Set Play Mode and Volume of the Video

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// Write the PPTX file to disk
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
 The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
 The following examples shows how to add large file through BLOB to a [Presentation](../). 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// Creates a new presentation to which the video will be added
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// Let's add the video to the presentation - we chose the KeepLocked behavior because we do
// not intend to access the "veryLargeVideo.avi" file.
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// Saves the presentation. While a large presentation gets outputted, the memory consumption
// stays low through the pres object's lifecycle
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
 The following examples shows how to export large file through BLOB from PowerPoint [Presentation](../). 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
// to transfer the data from the presentation's video stream to a stream for a newly created video file.
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// Iterates through the videos
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
    // like video.BinaryData - because this property returns a byte array containing a full video, which then
    // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
    //  require us to load the whole video into the memory.
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // Memory consumption will remain low regardless of the size of the video or presentation,
}
// If necessary, you can apply the same steps for audio files.
```
 The following examples shows how to add a hyperlink to a video in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
 The following examples shows how to create [Video](../../video/) Frame with [Video](../../video/) from Web Source in a PowerPoint [Presentation](../). 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // Add videoFrame
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(Aspose::Slides::VideoPlayModePreset::Auto);

    // Load thumbnail
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
 The following examples shows how to extract [Video](../../video/) from slide of PowerPoint [Presentation](../). 
```cpp
// Instantiate a Presentation object that represents a presentation file
auto presentation = System::MakeObject<Presentation>(u"Video.pptx");

for (auto&& slide : presentation->get_Slides())
{
    for (auto&& shape : slide->get_Shapes())
    {
        if (System::ObjectExt::Is<VideoFrame>(shape))
        {
            System::SharedPtr<IVideoFrame> vf = System::AsCast<Aspose::Slides::IVideoFrame>(shape);
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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IVideoCollection](../../ivideocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)