---
title: GetImage
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 맞춤 배율을 사용하여 Thumbnail Image 객체를 반환합니다.
type: docs
weight: 80
url: /ko/aspose.slides/slide/getimage/
---
## GetImage(float, float) {#getimage_5}

맞춤 배율을 적용한 Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | Single | 이 Thumbnail을 x축 방향으로 배율 조정하는 값입니다. |
| scaleY | Single | 이 Thumbnail을 y축 방향으로 배율 조정하는 값입니다. |

### 반환 값

IImage 객체.

### 예제

다음 예제는 PowerPoint 프레젠테이션에서 썸네일을 생성하는 방법을 보여줍니다.

```csharp
[C#]
// 프레젠테이션 파일을 나타내는 Presentation 클래스를 인스턴스화합니다
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // 첫 번째 슬라이드에 접근합니다
    ISlide sld = pres.Slides[0];
    // 전체 배율 이미지 생성
    IImage bmp = sld.GetImage(1f, 1f);
    // 이미지를 JPEG 형식으로 디스크에 저장합니다
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

다음 예제는 슬라이드를 비트맵으로 변환하고 PNG 형식으로 저장하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 프레젠테이션의 첫 번째 슬라이드를 Bitmap 객체로 변환합니다
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // 이미지를 PNG 형식으로 저장합니다
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

다음 예제는 PowerPoint PPT/PPTX를 JPG로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// 전체 배율 이미지 생성
		IImage bmp = sld.GetImage(1f, 1f);
		// 이미지를 JPEG 형식으로 디스크에 저장합니다
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

다음 예제는 맞춤 크기로 PowerPoint PPT/PPTX를 JPG로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// 차원 정의
	int desiredX = 1200;
	int desiredY = 800;
	// X와 Y의 배율값을 계산합니다
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// 전체 배율 이미지 생성
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// 이미지를 JPEG 형식으로 디스크에 저장합니다
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

실제 크기의 20%인 Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage()
```

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

지정된 크기의 Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage(Size imageSize)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageSize | Size | 생성할 이미지의 크기입니다. |

### 반환 값

Image 객체.

### 예제

다음 예제는 C#을 사용하여 맞춤 크기로 슬라이드를 이미지로 변환하는 방법을 보여줍니다.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // 프레젠테이션의 첫 번째 슬라이드를 지정된 크기의 Bitmap으로 변환합니다
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // 이미지를 JPEG 형식으로 저장합니다
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

지정된 매개변수로 Thumbnail tiff 이미지 객체를 반환합니다.

```csharp
public IImage GetImage(ITiffOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | ITiffOptions | Tiff 옵션. |

### 반환 값

Image 객체.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption이 NotesCommentsLayoutOptions이고 그 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 인터페이스 [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | IRenderingOptions | 렌더링 옵션. |

### 반환 값

Image 객체.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 인터페이스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

맞춤 배율을 적용한 Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | IRenderingOptions | 렌더링 옵션. |
| scaleX | Single | 이 Thumbnail을 x축 방향으로 배율 조정하는 값입니다. |
| scaleY | Single | 이 Thumbnail을 y축 방향으로 배율 조정하는 값입니다. |

### 반환 값

Bitmap 객체.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | notesCommentsLayouting.NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

### 예제

다음 예제는 C#을 사용하여 노트와 댓글이 포함된 슬라이드를 이미지로 변환하는 방법을 보여줍니다.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // 렌더링 옵션을 생성합니다
    IRenderingOptions options = new RenderingOptions();
    // 노트 및 댓글 레이아웃 옵션을 생성합니다
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // 페이지에서 노트의 위치를 설정합니다
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // 페이지에서 댓글의 위치를 설정합니다
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // 댓글 출력 영역의 너비를 설정합니다
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // 댓글 영역의 색상을 설정합니다
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // 렌더링을 위한 레이아웃 옵션을 설정합니다
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // 프레젠테이션의 첫 번째 슬라이드를 IImage 객체로 변환합니다
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // 이미지를 GIF 형식으로 저장합니다
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 인터페이스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

지정된 크기의 Thumbnail Image 객체를 반환합니다.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | IRenderingOptions | 렌더링 옵션. |
| imageSize | Size | 생성할 이미지의 크기입니다. |

### 반환 값

Image 객체.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | options.SlideLayoutOption이 NotesCommentsLayoutOptions이고 그 속성 NotesPosition이 NotesPositions.BottomFull 값을 가질 때 발생합니다. |

### 관련 항목

* 인터페이스 [IImage](../../iimage)
* 인터페이스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* 클래스 [Slide](../../slide)
* 네임스페이스 [Aspose.Slides](../../slide)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->