---
title: Videos
second_title: Aspose.Sildes for .NET API referencia
description: Visszaadja a prezentációban beágyazott összes videofájl gyűjteményét. Csak olvasható IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /hu/aspose.slides/presentation/videos/
---
## Presentation.Videos tulajdonság

Visszaadja a prezentációban beágyazott összes videofájl gyűjteményét. Csak olvasható [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Példák

Az alábbi példák bemutatják, hogyan hozható létre beágyazott Video Frame egy PowerPoint prezentációban.

```csharp
[C#]
// A PPTX-et képviselő Presentation osztály példányosítása
using (Presentation pres = new Presentation())
{
    // Az első dia lekérése
    ISlide sld = pres.Slides[0];
    // Videó beágyazása a prezentációba
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Video Frame hozzáadása
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Videó beállítása a Video Frame-hez
    vf.EmbeddedVideo = vid;
    // A videó lejátszási módjának és hangerőjének beállítása
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // A PPTX fájl írása lemezre
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Az alábbi példák bemutatják, hogyan adhatunk hozzá videót a fájl elérési útjának közvetlen átadásával az AddVideoFrame metódusba egy PowerPoint prezentációhoz.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Az alábbi példák bemutatják, hogyan adhatunk hozzá nagy fájlt BLOB-on keresztül egy prezentációhoz.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Új prezentáció létrehozása, amelyhez a videót hozzáadjuk
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Adjunk hozzá egy videót a prezentációhoz - a KeepLocked viselkedést választottuk, mert
        // nem szándékozunk hozzáférni a "veryLargeVideo.avi" fájlhoz.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Mentse a prezentációt. Miközben egy nagy prezentáció kerül kiírásra, a memóriahasználat
        // alacsony marad a pres objektum életciklusa során
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Az alábbi példák bemutatják, hogyan exportálhatunk nagy fájlt BLOB-on keresztül egy PowerPoint prezentációból.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Zárolja a forrásfájlt, és NEM tölti be a memóriába
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Létrehoz egy Presentation példányt, és zárolja a "hugePresentationWithAudiosAndVideos.pptx" fájlt.
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Mentse el minden videót egy fájlba. A magas memóriahasználat elkerülése érdekében egy puffert kell használnunk
	// az adatok átviteléhez a prezentáció videófolyamából egy újból létrehozott videófájl streamjébe.
	byte[] buffer = new byte[8 * 1024];
	// Végigiterál a videókon
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Megnyitja a prezentáció videófolyamát. Kérjük, vegye figyelembe, hogy szándékosan elkerültük a tulajdonságok elérését
		// mint a video.BinaryData - mivel ez a tulajdonság egy egész videót tartalmazó bájt tömböt ad vissza, ami
		// memóriába tölt be bájtokat. A video.GetStream-et használjuk, amely Stream-et ad vissza - és NEM
		//  igényli, hogy az egész videót betöltsük a memóriába.
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
		// A memóriafelhasználás alacsony marad a videó vagy a prezentáció méretétől függetlenül,
	}
	// Szükség esetén ugyanazokat a lépéseket alkalmazhatja hangfájlokra is.
}
```

Az alábbi példák bemutatják, hogyan adhatunk hiperhivatkozást egy videóhoz egy PowerPoint prezentációban.

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

Az alábbi példák bemutatják, hogyan hozhatunk létre Video Frame-et Web Source-ból származó videóval egy PowerPoint prezentációban.

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
    // videoFrame hozzáadása
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // bélyegkép betöltése
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Az alábbi példák bemutatják, hogyan nyerhetünk ki videót egy PowerPoint prezentáció diájából.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
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

### Lásd még

* interfész [IVideoCollection](../../ivideocollection)
* osztály [Presentation](../../presentation)
* névtér [Aspose.Slides](../../presentation)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->