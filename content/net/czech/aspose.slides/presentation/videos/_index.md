---
title: Videos
second_title: Aspose.Sildes pro .NET API Reference
description: Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /cs/aspose.slides/presentation/videos/
---
## Presentation.Videos vlastnost

Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Příklady

Následující příklady ukazují, jak vytvořit vložený Video Frame v prezentaci PowerPoint.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje soubor PPTX
using (Presentation pres = new Presentation())
{
    // Získejte první snímek
    ISlide sld = pres.Slides[0];
    // Vložte video do prezentace
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Přidejte Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Nastavte video do Video Frame
    vf.EmbeddedVideo = vid;
    // Nastavte režim přehrávání a hlasitost videa
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Uložte soubor PPTX na disk
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Následující příklady ukazují, jak přidat video předáním cesty k video souboru přímo do metody AddVideoFrame pro prezentaci PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Následující příklady ukazují, jak přidat velký soubor pomocí BLOB do prezentace.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Vytvoří novou prezentaci, do které bude video přidáno
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Přidáme video do prezentace - zvolili jsme chování KeepLocked, protože
        // neplánujeme přistupovat k souboru "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Uloží prezentaci. I když je výstupní prezentace velká, spotřeba paměti
        // zůstává nízká během životního cyklu objektu pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Následující příklady ukazují, jak exportovat velký soubor pomocí BLOB z prezentace PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Zamkne zdrojový soubor a NENAČTE ho do paměti
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Vytvoří instanci třídy Presentation a zamkne soubor "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Uložíme každé video do souboru. Abychom zabránili vysoké spotřebě paměti, potřebujeme buffer, který bude použit
	// k přenosu dat ze streamu videa v prezentaci do streamu nově vytvořeného video souboru.
	byte[] buffer = new byte[8 * 1024];
	// Iteruje přes videa
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Otevře stream videa v prezentaci. Všimněte si, že jsme úmyslně vyhnuli přístupu k vlastnostem
		// jako video.BinaryData - protože tato vlastnost vrací pole bajtů obsahující celé video, což
		// způsobí načtení bajtů do paměti. Používáme video.GetStream, který vrátí Stream - a NENÁKLÁDÁ
		// nevyžaduje načtení celého videa do paměti.
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
		// Spotřeba paměti zůstane nízká bez ohledu na velikost videa nebo prezentace,
	}
	// V případě potřeby můžete použít stejné kroky i pro audio soubory.
}
```

Následující příklady ukazují, jak přidat hypertextový odkaz na video v prezentaci PowerPoint.

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

Následující příklady ukazují, jak vytvořit Video Frame s videem z webového zdroje v prezentaci PowerPoint.

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
    //přidat videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //načíst miniaturu
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Následující příklady ukazují, jak extrahovat Video ze snímku prezentace PowerPoint.

```csharp
[C#]
// Vytvořte objekt Presentation, který představuje soubor prezentace
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

### Viz také

* rozhraní [IVideoCollection](../../ivideocollection)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->