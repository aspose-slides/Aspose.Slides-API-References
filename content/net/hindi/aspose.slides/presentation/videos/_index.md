---
title: Videos
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /hi/aspose.slides/presentation/videos/
---
## Presentation.Videos प्रॉपर्टी

प्रस्तुति में सभी एम्बेडेड वीडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### उदाहरण

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति में एम्बेडेड Video Frame कैसे बनायें।

```csharp
[C#]
// PPTX का प्रतिनिधित्व करने वाला Presentation क्लास बनाएं
using (Presentation pres = new Presentation())
{
    // पहली स्लाइड प्राप्त करें
    ISlide sld = pres.Slides[0];
    // प्रस्तुति में वीडियो एम्बेड करें
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // वीडियो फ्रेम जोड़ें
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // वीडियो को वीडियो फ्रेम पर सेट करें
    vf.EmbeddedVideo = vid;
    // वीडियो के प्ले मोड और वॉल्यूम सेट करें
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // PPTX फ़ाइल को डिस्क पर लिखें
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति के लिए AddVideoFrame मेथड में सीधे वीडियो फ़ाइल का पथ पास करके वीडियो कैसे जोड़ें।

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

निम्नलिखित उदाहरण दिखाते हैं कि प्रस्तुति में बड़े फ़ाइल को BLOB के माध्यम से कैसे जोड़ें।

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// एक नया प्रेजेंटेशन बनाता है जिसमें वीडियो जोड़ा जाएगा
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // चलिए वीडियो को प्रेजेंटेशन में जोड़ते हैं - हमने KeepLocked व्यवहार चुना क्योंकि हम
        // "veryLargeVideo.avi" फ़ाइल तक पहुँचने का इरादा नहीं रखते।
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // प्रेजेंटेशन को सहेजता है। जबकि एक बड़ी प्रेजेंटेशन आउटपुट होती है, मेमोरी खपत
        // प्रेजेंटेशन ऑब्जेक्ट के जीवनचक्र में कम रहती है
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति से बड़े फ़ाइल को BLOB के माध्यम से कैसे निर्यात करें।

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// स्रोत फ़ाइल को लॉक करता है और इसे मेमोरी में लोड नहीं करता
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// एक Presentation का instance बनाता है, "hugePresentationWithAudiosAndVideos.pptx" फ़ाइल को लॉक करता है।
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// चलिए प्रत्येक वीडियो को फ़ाइल में सहेजते हैं। अधिक मेमोरी उपयोग को रोकने के लिए हमें एक बफ़र की आवश्यकता होगी जो उपयोग किया जाएगा
	// प्रस्तुति के वीडियो स्ट्रीम से डेटा को नए बनाए गए वीडियो फ़ाइल की स्ट्रीम में स्थानांतरित करने के लिए।
	byte[] buffer = new byte[8 * 1024];
	// वीडियो पर इटरेट करता है
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// प्रस्तुति के वीडियो स्ट्रीम को खोलता है। कृपया ध्यान दें कि हमने जानबूझकर प्रॉपर्टी एक्सेस करने से बचा रहे हैं
		// जैसे video.BinaryData - क्योंकि यह प्रॉपर्टी पूरी वीडियो वाला बाइट ऐरे लौटाता है, जो फिर
		// मेमोरी में बाइट्स को लोड कर देता है। हम video.GetStream का उपयोग करते हैं, जो Stream लौटाता है - और नहीं
		//  हमें पूरी वीडियो को मेमोरी में लोड करने की आवश्यकता नहीं पड़ती।
		using (Stream presVideoStream = video.GetStream())
		{
			using (FileStream outputFileStream = File.OpenWrite($"video{index}.avi"))
			{
				int bytesRead;
				while ((bytesRead = presVideoStream.Read(buffer, 0, buffer.Length)) > 0)
				{
					outputFileStream.Write(buffer, 0, bytesRead);
				}
			}
		}
		// मेमोरी खपत वीडियो या प्रस्तुति के आकार की परवाह किए बिना कम रहेगी,
	}
	// यदि आवश्यक हो, आप ऑडियो फ़ाइलों के लिए भी वही चरण लागू कर सकते हैं।
}
```

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति में वीडियो में हाइपरलिंक कैसे जोड़ें।

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.avi"));
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 100, 100, video);
    videoFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    videoFrame.HyperlinkClick.Tooltip = "More than 70% Fortune 100 companies trust Aspose APIs";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति में वेब स्रोत से Video के साथ Video Frame कैसे बनायें।

```csharp
[C#]
public static void Run()
{
    using (Presentation pres = new Presentation())
    {
        AddVideoFromYouTube(pres, "Tj75Arhq5ho");
        pres.Save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
    }
}
private static void AddVideoFromYouTube(Presentation pres, string videoId)
{
    // वीडियो फ्रेम जोड़ें
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // थंबनेल लोड करें
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

निम्नलिखित उदाहरण दिखाते हैं कि PowerPoint प्रस्तुति की स्लाइड से Video कैसे निकालें।

```csharp
[C#]
// एक Presentation ऑब्जेक्ट बनाएं जो एक प्रेजेंटेशन फ़ाइल का प्रतिनिधित्व करता है
using (Presentation presentation = new Presentation("Video.pptx"))
{
	foreach (ISlide slide in presentation.Slides)
	{
		foreach (IShape shape in presentation.Slides[0].Shapes)
		{
			if (shape is VideoFrame)
			{
				IVideoFrame vf = shape as IVideoFrame;
				String type = vf.EmbeddedVideo.ContentType;
				int ss = type.LastIndexOf('/');
				type = type.Remove(0, type.LastIndexOf('/') + 1);
				Byte[] buffer = vf.EmbeddedVideo.BinaryData;
				using (FileStream stream = new FileStream("NewVideo_out." + type, FileMode.Create, FileAccess.Write, FileShare.Read))
				{
					stream.Write(buffer, 0, buffer.Length);
				}
			}
		}
	}
}
```

### संबंधित देखें

* इंटरफ़ेस [IVideoCollection](../../ivideocollection)
* क्लास [Presentation](../../presentation)
* नामस्थान [Aspose.Slides](../../presentation)
* असेंबली [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->