---
title: Videos
second_title: Referensi API Aspose.Sildes untuk .NET
description: Mengembalikan koleksi semua file video tersemat dalam presentasi. Hanya-baca IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /id/aspose.slides/presentation/videos/
---
## Presentation.Videos properti

Mengembalikan koleksi semua file video tersemat dalam presentasi. Hanya-baca [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Contoh

Contoh berikut menunjukkan cara membuat Video Frame tersemat dalam PowerPoint Presentation.

```csharp
[C#]
// Membuat instance kelas Presentation yang mewakili PPTX
using (Presentation pres = new Presentation())
{
    // Dapatkan slide pertama
    ISlide sld = pres.Slides[0];
    // Menyematkan video dalam presentasi
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Tambahkan Video Frame
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Atur video ke Video Frame
    vf.EmbeddedVideo = vid;
    // Atur Mode Pemutaran dan Volume Video
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Tulis file PPTX ke disk
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Contoh berikut menunjukkan cara menambahkan video dengan memberikan path ke file video secara langsung ke metode AddVideoFrame untuk PowerPoint Presentation.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Contoh berikut menunjukkan cara menambahkan file besar melalui BLOB ke sebuah Presentation.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Membuat presentasi baru yang akan ditambahkan video
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Mari tambahkan video ke presentasi - kami memilih perilaku KeepLocked karena kami tidak
        // bermaksud mengakses file "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Menyimpan presentasi. Saat presentasi besar dihasilkan, konsumsi memori
        // tetap rendah selama siklus hidup objek pres
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Contoh berikut menunjukkan cara mengekspor file besar melalui BLOB dari PowerPoint Presentation.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Mengunci file sumber dan TIDAK memuatnya ke memori
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Membuat instance Presentation, mengunci file "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Mari simpan setiap video ke file. Untuk mencegah penggunaan memori tinggi, kita membutuhkan buffer yang akan digunakan
	// untuk mentransfer data dari stream video presentasi ke stream untuk file video yang baru dibuat.
	byte[] buffer = new byte[8 * 1024];
	// Mengiterasi video-video
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Membuka stream video presentasi. Harap dicatat bahwa kami sengaja menghindari mengakses properti
		// seperti video.BinaryData - karena properti ini mengembalikan array byte yang berisi video lengkap, yang kemudian
		// menyebabkan byte-byte dimuat ke memori. Kami menggunakan video.GetStream, yang akan mengembalikan Stream - dan TIDAK
		//  memaksa kami memuat seluruh video ke memori.
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
		// Konsumsi memori akan tetap rendah terlepas dari ukuran video atau presentasi,
	}
	// Jika diperlukan, Anda dapat menerapkan langkah yang sama untuk file audio.
}
```

Contoh berikut menunjukkan cara menambahkan hyperlink ke video dalam PowerPoint Presentation.

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

Contoh berikut menunjukkan cara membuat Video Frame dengan Video dari Sumber Web dalam PowerPoint Presentation.

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
    //tambahkan videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //muat thumbnail
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Contoh berikut menunjukkan cara mengekstrak Video dari slide PowerPoint Presentation.

```csharp
[C#]
// Instansiasi objek Presentation yang mewakili file presentasi
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

### Lihat Juga

* antarmuka [IVideoCollection](../../ivideocollection)
* kelas [Presentation](../../presentation)
* ruang nama [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->