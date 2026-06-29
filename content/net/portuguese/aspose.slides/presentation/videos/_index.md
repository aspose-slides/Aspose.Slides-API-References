---
title: Videos
second_title: Aspose.Sildes para .NET Referência da API
description: Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /pt/aspose.slides/presentation/videos/
---
## Presentation.Videos propriedade

Retorna a coleção de todos os arquivos de vídeo incorporados na apresentação. Somente leitura [`IVideoCollection`](../../ivideocollection).

```csharp
public IVideoCollection Videos { get; }
```

### Exemplos

Os exemplos a seguir mostram como criar um Video Frame incorporado em uma Apresentação PowerPoint.

```csharp
[C#]
// Instancia a classe Presentation que representa o PPTX
using (Presentation pres = new Presentation())
{
    // Obtém o primeiro slide
    ISlide sld = pres.Slides[0];
    // Incorpora vídeo dentro da apresentação
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // Adiciona um quadro de vídeo
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // Define o vídeo no Video Frame
    vf.EmbeddedVideo = vid;
    // Define o modo de reprodução e volume do vídeo
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // Grava o arquivo PPTX no disco
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

Os exemplos a seguir mostram como adicionar um vídeo passando o caminho do arquivo de vídeo diretamente ao método AddVideoFrame para uma Apresentação PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

Os exemplos a seguir mostram como adicionar um arquivo grande via BLOB a uma Apresentação.

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// Cria uma nova apresentação à qual o vídeo será adicionado
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // Vamos adicionar o vídeo à apresentação - escolhemos o comportamento KeepLocked porque
        // não pretendemos acessar o arquivo "veryLargeVideo.avi".
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // Salva a apresentação. Enquanto uma apresentação grande é exportada, o consumo de memória
        // permanece baixo ao longo do ciclo de vida do objeto pres.
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

Os exemplos a seguir mostram como exportar um arquivo grande via BLOB de uma Apresentação PowerPoint.

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// Bloqueia o arquivo de origem e NÃO o carrega na memória
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Cria uma instância de Presentation, bloqueia o arquivo "hugePresentationWithAudiosAndVideos.pptx".
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// Vamos salvar cada vídeo em um arquivo. Para evitar alto consumo de memória, precisamos de um buffer que será usado
	// para transferir os dados do fluxo de vídeo da apresentação para um fluxo de um arquivo de vídeo recém-criado.
	byte[] buffer = new byte[8 * 1024];
	// Percorre os vídeos
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// Abre o fluxo de vídeo da apresentação. Observe que evitamos intencionalmente acessar propriedades
		// como video.BinaryData - porque essa propriedade retorna um array de bytes contendo um vídeo completo, o que então
		// faz com que bytes sejam carregados na memória. Usamos video.GetStream, que retornará um Stream - e NÃO
		//  exige que carreguemos o vídeo inteiro na memória.
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
		// O consumo de memória permanecerá baixo independentemente do tamanho do vídeo ou da apresentação,
	}
	// Se necessário, você pode aplicar os mesmos passos para arquivos de áudio.
}
```

Os exemplos a seguir mostram como adicionar um hyperlink a um vídeo em uma Apresentação PowerPoint.

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

Os exemplos a seguir mostram como criar um Video Frame com Vídeo de Fonte Web em uma Apresentação PowerPoint.

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
    // adiciona videoFrame
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    // carrega miniatura
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

Os exemplos a seguir mostram como extrair Vídeo de um slide de uma Apresentação PowerPoint.

```csharp
[C#]
// Instancia um objeto Presentation que representa um arquivo de apresentação
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

### Veja Também

* interface [IVideoCollection](../../ivideocollection)
* classe [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->