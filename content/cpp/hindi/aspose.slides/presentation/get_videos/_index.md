---
title: get_Videos()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रेजेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य IVideoCollection.
type: docs
weight: 235
url: /hi/aspose.slides/presentation/get_videos/
---
## Presentation::get_Videos() विधि

प्रेजेंटेशन में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IVideoCollection](../../ivideocollection/)।

```cpp
System::SharedPtr<IVideoCollection> Aspose::Slides::Presentation::get_Videos() override
```

## टिप्पणी

निम्नलिखित उदाहरण दिखाते हैं कि कैसे एम्बेडेड [Video](../../video/) फ़्रेम PowerPoint [Presentation](../) में बनाया जाए। 
```cpp
// PPTX को दर्शाने वाली Presentation क्लास का उदाहरण बनाएं
auto pres = System::MakeObject<Presentation>();

// पहली स्लाइड प्राप्त करें
auto slide = pres->get_Slides()->idx_get(0);

// प्रेजेंटेशन में वीडियो एम्बेड करें
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::MakeObject<System::IO::FileStream>(u"Wildlife.mp4", System::IO::FileMode::Open));

// वीडियो फ्रेम जोड़ें
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 350.0f, video);

// वीडियो को वीडियो फ्रेम में सेट करें
vf->set_EmbeddedVideo(video);
// वीडियो का प्ले मोड और वॉल्यूम सेट करें

vf->set_PlayMode(VideoPlayModePreset::Auto);
vf->set_Volume(AudioVolumeMode::Loud);

// PPTX फ़ाइल को डिस्क पर लिखें
pres->Save(u"VideoFrame_out.pptx", SaveFormat::Pptx);
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे वीडियो फ़ाइल का पथ पास करके सीधे AddVideoFrame मेथड में PowerPoint [Presentation](../) के लिए जोड़ा जाए। 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto vf = slide->get_Shapes()->AddVideoFrame(50.0f, 150.0f, 300.0f, 150.0f, u"video1.avi");
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे BLOB के माध्यम से बड़ी फ़ाइल [Presentation](../) में जोड़ी जाए। 
```cpp
const System::String pathToVeryLargeVideo = u"veryLargeVideo.avi";
// एक नई प्रस्तुति बनाता है जिसमें वीडियो जोड़ा जाएगा
auto pres = System::MakeObject<Presentation>();

auto fileStream = System::MakeObject<System::IO::FileStream>(pathToVeryLargeVideo, System::IO::FileMode::Open);

// आइए वीडियो को प्रस्तुति में जोड़ते हैं - हमने KeepLocked व्यवहार चुना क्योंकि हम
// "veryLargeVideo.avi" फ़ाइल को एक्सेस करने का इरादा नहीं रखते।
System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(fileStream, LoadingStreamBehavior::KeepLocked);
pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(0.0f, 0.0f, 480.0f, 270.0f, video);

// प्रस्तुति को सहेजता है। जबकि एक बड़ी प्रस्तुति आउटपुट होती है, मेमोरी उपयोग
// pres ऑब्जेक्ट के जीवनचक्र में कम रहता है।
pres->Save(u"presentationWithLargeVideo.pptx", Export::SaveFormat::Pptx);
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे BLOB के माध्यम से बड़ी फ़ाइल PowerPoint [Presentation](../) से निर्यात की जाए। 
```cpp
const System::String hugePresentationWithAudiosAndVideosFile = u"Large  Video File Test1.pptx";
auto loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_BlobManagementOptions(System::MakeObject<BlobManagementOptions>());
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);

// एक Presentation का उदाहरण बनाता है, "hugePresentationWithAudiosAndVideos.pptx" फ़ाइल को लॉक करता है।
auto pres = System::MakeObject<Presentation>(hugePresentationWithAudiosAndVideosFile, loadOptions);

// प्रत्येक वीडियो को फ़ाइल में सहेजें। उच्च मेमोरी उपयोग को रोकने के लिए हमें एक बफ़र चाहिए जो उपयोग किया जाएगा
// प्रस्तुति के वीडियो स्ट्रीम से डेटा को नई बनाई गई वीडियो फ़ाइल के स्ट्रीम में स्थानांतरित करने के लिए।
System::ArrayPtr<uint8_t> buffer = System::MakeArray<uint8_t>(8 * 1024, 0);
// वीडियो को क्रम में चलाता है
for (int32_t index = 0; index < pres->get_Videos()->get_Count(); index++)
{
    System::SharedPtr<IVideo> video = pres->get_Videos()->idx_get(index);
    // प्रस्तुति के वीडियो स्ट्रीम को खोलता है। कृपया ध्यान दें कि हमने जानबूझकर प्रॉपर्टीज़ तक पहुँचने से बचा है
    // जैसे video.BinaryData - क्योंकि यह प्रॉपर्टी पूरी वीडियो वाली बाइट ऐरे वापस करती है, जो तब
    // बाइट्स को मेमोरी में लोड करने का कारण बनती है। हम video.GetStream का उपयोग करते हैं, जो Stream लौटाएगा - और यह नहीं करेगा
    //  हमें पूरी वीडियो को मेमोरी में लोड करने की आवश्यकता नहीं पड़ेगी।
    auto presVideoStream = video->GetStream();

    auto outputFileStream = System::IO::File::OpenWrite(System::String::Format(u"video{0}.avi", index));

    int32_t bytesRead;
    while ((bytesRead = presVideoStream->Read(buffer, 0, buffer->get_Length())) > 0)
    {
        outputFileStream->Write(buffer, 0, bytesRead);
    }
    // वीडियो या प्रस्तुति के आकार की परवाह किए बिना मेमोरी उपयोग कम रहेगा,
}
// यदि आवश्यक हो, तो आप ऑडियो फ़ाइलों के लिए भी वही चरण लागू कर सकते हैं।
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे PowerPoint [Presentation](../) में वीडियो में हाइपरलिंक जोड़ा जाए। 
```cpp
auto pres = System::MakeObject<Presentation>();

System::SharedPtr<IVideo> video = pres->get_Videos()->AddVideo(System::IO::File::ReadAllBytes(u"video.avi"));
System::SharedPtr<IVideoFrame> videoFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 100.0f, 100.0f, video);
videoFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
videoFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे [Video](../../video/) फ़्रेम [Video](../../video/) के साथ वेब स्रोत से PowerPoint [Presentation](../) में बनाया जाए। 
```cpp
void Run()
{
    auto pres = System::MakeObject<Presentation>();

    AddVideoFromYouTube(pres, u"Tj75Arhq5ho");
    pres->Save(u"AddVideoFrameFromWebSource_out.pptx", SaveFormat::Pptx);
}

void AddVideoFromYouTube(System::SharedPtr<Presentation> pres, System::String videoId)
{
    // वीडियो फ्रेम जोड़ें
    auto slide = pres->get_Slides()->idx_get(0);
    System::SharedPtr<IVideoFrame> videoFrame = slide->get_Shapes()->AddVideoFrame(10.0f, 10.0f, 427.0f, 240.0f, System::String(u"https://www.youtube.com/embed/") + videoId);
    videoFrame->set_PlayMode(VideoPlayModePreset::Auto);

    // थंबनेल लोड करें
    auto client = System::MakeObject<System::Net::WebClient>();
    System::String thumbnailUri = System::String(u"http://img.youtube.com/vi/") + videoId + u"/hqdefault.jpg";
    videoFrame->get_PictureFormat()->get_Picture()->set_Image(pres->get_Images()->AddImage(client->DownloadData(thumbnailUri)));
}
```
निम्नलिखित उदाहरण दिखाते हैं कि कैसे PowerPoint [Presentation](../) की स्लाइड से [Video](../../video/) निकाला जाए। 
```cpp
// प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला एक Presentation ऑब्जेक्ट बनाएं
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

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IVideoCollection](../../ivideocollection/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)