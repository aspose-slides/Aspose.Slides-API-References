---
title: Videos
second_title: Aspose.Sildes for .NET API Referansı
description: Sunumda gömülü tüm video dosyalarının koleksiyonunu döndürür. Yalnızca okunabilir IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /tr/aspose.slides/presentation/videos/
---
## Presentation.Videos özelliği

Sunumda yerleştirilmiş tüm video dosyalarının koleksiyonunu döndürür. Yalnızca okunabilir [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Örnekler

Aşağıdaki örnekler, bir PowerPoint Sunumu'nda gömülü Video Çerçevesi oluşturmayı gösterir.

```csharp
[C#]
// PPTX'i temsil eden Presentation sınıfını örnekleyin
using (Presentation pres = new Presentation())
{
    // İlk slaytı al
    ISlide sld = pres.Slides[0];
    // Sunum içinde video göm
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Video Çerçevesi ekle
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Videoyu Video Çerçevesine ayarla
    vf.EmbeddedVideo = vid;
    // Videonun Oynatma Modunu ve Ses Seviyesini ayarla
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // PPTX dosyasını diske kaydet
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Aşağıdaki örnekler, PowerPoint Sunumu için AddVideoFrame metoduna video dosyasının yolunu doğrudan geçirerek bir video eklemeyi gösterir.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Aşağıdaki örnekler, bir Sunuma BLOB aracılığıyla büyük dosya eklemeyi gösterir.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
    // Videonun ekleneceği yeni bir sunum oluşturur
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Videoyu sunuma ekleyelim - KeepLocked davranışını seçtik çünkü biz
        //"veryLargeVideo.avi" dosyasına erişmeyi amaçlamıyoruz.
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Sunumu kaydeder. Büyük bir sunum çıktısı alınırken, bellek tüketimi
        // pres nesnesinin yaşam döngüsü boyunca düşük kalır
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Aşağıdaki örnekler, bir PowerPoint Sunumu'ndan BLOB aracılığıyla büyük dosya dışa aktarmayı gösterir.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Kaynak dosyayı kilitler ve belleğe YÜKLEMEZ
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Bir Presentation örneği oluşturur, "hugePresentationWithAudiosAndVideos.pptx" dosyasını kilitler.
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Her videoyu bir dosyaya kaydedelim. Yüksek bellek kullanımını önlemek için bir tampon gerekir
	// sunumun video akışından yeni oluşturulan bir video dosyasına bir akışa veri aktarmak için.
	byte[] buffer = new byte[8 * 1024];
	// Videoları dolaşır
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Sunumun video akışını açar. Lütfen, kasıtlı olarak özelliklere erişimden kaçındığımızı unutmayın
		// video.BinaryData gibi - çünkü bu özellik tam bir video içeren bir bayt dizisi döndürür, bu da
		// baytların belleğe yüklenmesine neden olur. video.GetStream kullanıyoruz, bu bir Stream döndürür - ve BELLEKTE YÜKLEMEZ
		//  tüm videoyu belleğe yüklememizi gerektirmez.
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
		// Bellek tüketimi, video ya da sunumun boyutundan bağımsız olarak düşük kalacaktır,
	}
	// Gerekirse, aynı adımları ses dosyaları için de uygulayabilirsiniz.
}
```

Aşağıdaki örnekler, bir PowerPoint Sunumu'ndaki videoya bir köprü eklemeyi gösterir.

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

Aşağıdaki örnekler, bir PowerPoint Sunumu'nda Web Kaynağından Video ile Video Çerçevesi oluşturmayı gösterir.

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
        // video çerçevesi ekle
        IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
        videoFrame.PlayMode = VideoPlayModePreset.Auto;
        // küçük resmi yükle
        using (WebClient client = new WebClient())
        {
            string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
            videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
        }
}
```

Aşağıdaki örnekler, bir PowerPoint Sunumu slaytından Video çıkarmayı gösterir.

```csharp
[C#]
// Sunum dosyasını temsil eden bir Presentation nesnesi oluşturur
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

### Ayrıca Bakınız

* arayüz [IVideoCollection](../../ivideocollection)
* sınıf [Presentation](../../presentation)
* ad alanı [Aspose.Slides](../../presentation)
* derleme [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->