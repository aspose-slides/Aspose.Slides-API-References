---
title: Videos
second_title: Aspose.Sildes for .NET API Reference
description: Returns the collection of all embedded video files in the presentation. Read-only IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 280
url: /net/aspose.slides/presentation/videos/
---
## Presentation.Videos property

Returns the collection of all embedded video files in the presentation. Read-only [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Examples

The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.

```csharp
[C#]
// Instantiate Presentation class that represents the PPTX
using (Presentation pres = new Presentation())
{

    // Get the first slide
    ISlide sld = pres.Slides[0];

    // Embedd vide inside presentation
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));

    // Add Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);

    // Set video to Video Frame
    vf.EmbeddedVideo = vid;

    // Set Play Mode and Volume of the Video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;

    // Write the PPTX file to disk
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

The following examples shows how to add large file through BLOB to a Presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";

// Creates a new presentation to which the video will be added
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
        //not intend to access the "veryLargeVideo.avi" file.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);

        // Saves the presentation. While a large presentation gets outputted, the memory consumption
        // stays low through the pres object's lifecycle 
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

The following examples shows how to export large file through BLOB from PowerPoint Presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";

LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Locks the source file and does NOT load it into memory
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};

// Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
	// to transfer the data from the presentation's video stream to a stream for a newly created video file.
	byte[] buffer = new byte[8 * 1024];

	// Iterates through the videos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];

		// Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
		// like video.BinaryData - because this property returns a byte array containing a full video, which then
		// causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
		//  require us to load the whole video into the memory.
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

		// Memory consumption will remain low regardless of the size of the video or presentation,
	}

	// If necessary, you can apply the same steps for audio files. 
}
```

The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.

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

The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.

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
    //add videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;

    //load thumbnail
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

The following examples shows how to extract Video from slide of PowerPoint Presentation.

```csharp
[C#]
// Instantiate a Presentation object that represents a presentation file 
Presentation presentation = new Presentation("Video.pptx");

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
```

### See Also

* interface [IVideoCollection](../../ivideocollection)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
