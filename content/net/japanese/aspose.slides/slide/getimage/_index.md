---
title: GetImage
second_title: Aspose.Sildes の .NET API リファレンス
description: カスタムスケーリングを使用したサムネイル Image オブジェクトを返します。
type: docs
weight: 80
url: /ja/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

カスタムスケーリングを使用したサムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | Single | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | Single | このサムネイルを y 軸方向に拡大縮小する値。 |

### 戻り値

IImage オブジェクト。

### 例

以下の例は、PowerPoint Presentation からサムネイルを生成する方法を示しています。

```csharp
[C#]
// プレゼンテーション ファイルを表す Presentation クラスのインスタンスを作成します
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // 最初のスライドにアクセスします
    ISlide sld = pres.Slides[0];
    // フルスケールの画像を作成します
    IImage bmp = sld.GetImage(1f, 1f);
    // 画像を JPEG 形式でディスクに保存します
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

以下の例は、スライドをビットマップに変換し、PNG で画像を保存する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // プレゼンテーションの最初のスライドを Bitmap オブジェクトに変換します
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // 画像を PNG 形式で保存します
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

以下の例は、PowerPoint PPT/PPTX を JPG に変換する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	 foreach (ISlide sld in pres.Slides)
	 {
		 // フルスケールの画像を作成します
		 IImage bmp = sld.GetImage(1f, 1f);
		 // 画像を JPEG 形式でディスクに保存します
		 bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	 }
}
```

以下の例は、カスタマイズされた寸法で PowerPoint PPT/PPTX を JPG に変換する方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// 次元を定義します
	int desiredX = 1200;
	int desiredY = 800;
	// X と Y のスケーリングされた値を取得します
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// フルスケールの画像を作成します
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// 画像を JPEG 形式でディスクに保存します
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### 参照

* インターフェイス [IImage](../../iimage)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

実際のサイズの 20% のサムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage()
```

### 参照

* インターフェイス [IImage](../../iimage)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

指定されたサイズのサムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage(Size imageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSize | Size | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

### 例

以下の例は、C# を使用してカスタムサイズでスライドを画像に変換する方法を示しています。

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // プレゼンテーション内の最初のスライドを指定サイズの Bitmap に変換します
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // 画像を JPEG 形式で保存します
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### 参照

* インターフェイス [IImage](../../iimage)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

指定されたパラメータでサムネイル TIFF 画像オブジェクトを返します。

```csharp
public IImage GetImage(ITiffOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | ITiffOptions | TIFF オプション。 |

### 戻り値

Image オブジェクト。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption が NotesCommentsLayoutingOptions であり、そのプロパティ NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

### 参照

* インターフェイス [IImage](../../iimage)
* インターフェイス [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

サムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage(IRenderingOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | IRenderingOptions | レンダリングオプション。 |

### 戻り値

Image オブジェクト。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

### 参照

* インターフェイス [IImage](../../iimage)
* インターフェイス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

カスタムスケーリングを使用したサムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | IRenderingOptions | レンダリングオプション。 |
| scaleX | Single | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | Single | このサムネイルを y 軸方向に拡大縮小する値。 |

### 戻り値

Bitmap オブジェクト。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

### 例

以下の例は、C# を使用してノートとコメント付きのスライドを画像に変換する方法を示しています。

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // レンダリングオプションを作成します
    IRenderingOptions options = new RenderingOptions();
    // ノートとコメントのレイアウトオプションを作成します
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // ページ上のノートの位置を設定します
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // ページ上のコメントの位置を設定します
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // コメント出力エリアの幅を設定します
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // コメントエリアの色を設定します
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // レンダリングのレイアウトオプションを設定します
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // プレゼンテーションの最初のスライドを IImage オブジェクトに変換します
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // 画像を GIF 形式で保存します
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### 参照

* インターフェイス [IImage](../../iimage)
* インターフェイス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

指定されたサイズのサムネイル Image オブジェクトを返します。

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | IRenderingOptions | レンダリングオプション。 |
| imageSize | Size | 作成する画像のサイズ。 |

### 戻り値

Image オブジェクト。

### 例外

| 例外 | 条件 |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption が NotesCommentsLayoutingOptions であり、そのプロパティ NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

### 参照

* インターフェイス [IImage](../../iimage)
* インターフェイス [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* クラス [Slide](../../slide)
* 名前空間 [Aspose.Slides](../../slide)
* アセンブリ [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->