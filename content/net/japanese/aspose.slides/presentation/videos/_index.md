---
title: Videos
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーション内のすべての埋め込みビデオファイルのコレクションを返します。読み取り専用 IVideoCollectionaspose.slides/ivideocollection.
type: docs
weight: 290
url: /ja/aspose.slides/presentation/videos/
---
## Presentation.Videos プロパティ

プレゼンテーション内のすべての埋め込みビデオファイルのコレクションを返します。読み取り専用 [`IVideoCollection`](../../ivideocollection)。

```csharp
public IVideoCollection Videos { get; }
```

### 例

以下の例は、PowerPoint プレゼンテーションで埋め込みビデオフレームを作成する方法を示します。

```csharp
[C#]
// PPTX を表す Presentation クラスのインスタンス化
using (Presentation pres = new Presentation())
{
    // 最初のスライドを取得
    ISlide sld = pres.Slides[0];
    // プレゼンテーションにビデオを埋め込む
    IVideo vid = pres.Videos.AddVideo(new FileStream("Wildlife.mp4", FileMode.Open));
    // ビデオフレームを追加
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 350, vid);
    // ビデオをビデオフレームに設定
    vf.EmbeddedVideo = vid;
    // ビデオの再生モードと音量を設定
    vf.PlayMode = VideoPlayModePreset.Auto;
    vf.Volume = AudioVolumeMode.Loud;
    // PPTX ファイルを書き込む
    pres.Save("VideoFrame_out.pptx", SaveFormat.Pptx);
}
```

以下の例は、PowerPoint プレゼンテーションの AddVideoFrame メソッドにビデオファイルへのパスを直接渡してビデオを追加する方法を示します。

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IVideoFrame vf = sld.Shapes.AddVideoFrame(50, 150, 300, 150, "video1.avi");
}
```

以下の例は、BLOB を使用してプレゼンテーションに大きなファイルを追加する方法を示します。

```csharp
[C#]
const string pathToVeryLargeVideo = "veryLargeVideo.avi";
// ビデオを追加する新しいプレゼンテーションを作成します
using (Presentation pres = new Presentation())
{
    using (FileStream fileStream = new FileStream(pathToVeryLargeVideo, FileMode.Open))
    {
        // ビデオをプレゼンテーションに追加します - KeepLocked 動作を選択したのは、
        //「veryLargeVideo.avi」ファイルにアクセスするつもりがありません。
        IVideo video = pres.Videos.AddVideo(fileStream, LoadingStreamBehavior.KeepLocked);
        pres.Slides[0].Shapes.AddVideoFrame(0, 0, 480, 270, video);
        // プレゼンテーションを保存します。大きなプレゼンテーションが出力される間、メモリ使用量は
        // pres オブジェクトのライフサイクル全体で低く保たれます
        pres.Save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
    }
}
```

以下の例は、PowerPoint プレゼンテーションから BLOB を介して大きなファイルをエクスポートする方法を示します。

```csharp
[C#]
const string hugePresentationWithAudiosAndVideosFile = @"Large  Video File Test1.pptx";
LoadOptions loadOptions = new LoadOptions
{
	BlobManagementOptions = {
		// ソースファイルをロックし、メモリに読み込まない
		PresentationLockingBehavior = PresentationLockingBehavior.KeepLocked,
	}
};
// Presentation のインスタンスを作成し、"hugePresentationWithAudiosAndVideos.pptx" ファイルをロックします。
using (Presentation pres = new Presentation(hugePresentationWithAudiosAndVideosFile, loadOptions))
{
	// 各ビデオをファイルに保存します。高いメモリ使用を防ぐために、バッファが必要です。
	// プレゼンテーションのビデオストリームから新しく作成したビデオファイル用のストリームへデータを転送するために使用されます。
	byte[] buffer = new byte[8 * 1024];
	for (var index = 0; index < pres.Videos.Count; index++)
	{
		IVideo video = pres.Videos[index];
		// プレゼンテーションのビデオストリームを開きます。注意点として、意図的にプロパティへのアクセスを避けています。
		// video.BinaryData のようなプロパティは、フルビデオを含むバイト配列を返すため、
		// メモリに読み込まれてしまいます。代わりに video.GetStream を使用し、Stream を返すので、
		// ビデオ全体をメモリにロードする必要はありません。
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
		// ビデオやプレゼンテーションのサイズに関わらず、メモリ消費は低く抑えられます。
	}
	// 必要に応じて、オーディオファイルにも同じ手順を適用できます。
}
```

以下の例は、PowerPoint プレゼンテーションのビデオにハイパーリンクを追加する方法を示します。

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

以下の例は、PowerPoint プレゼンテーションでWeb ソースからのビデオを使用してビデオフレームを作成する方法を示します。

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
    //ビデオフレームを追加
    IVideoFrame videoFrame = pres.Slides[0].Shapes.AddVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
    videoFrame.PlayMode = VideoPlayModePreset.Auto;
    //サムネイルを読み込む
    using (WebClient client = new WebClient())
    {
        string thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
        videoFrame.PictureFormat.Picture.Image = pres.Images.AddImage(client.DownloadData(thumbnailUri));
    }
}
```

以下の例は、PowerPoint プレゼンテーションのスライドからビデオを抽出する方法を示します。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
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

### 参照

* インターフェイス [IVideoCollection](../../ivideocollection)
* クラス [Presentation](../../presentation)
* 名前空間 [Aspose.Slides](../../presentation)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->