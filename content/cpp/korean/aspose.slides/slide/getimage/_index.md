---
title: GetImage()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 맞춤 스케일링을 적용한 Thumbnail Image 객체를 반환합니다.
type: docs
weight: 144
url: /ko/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) 메서드

맞춤 스케일링을 적용한 Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | **float** | 이 Thumbnail을 x축 방향으로 스케일링하는 값입니다. |
| scaleY | **float** | 이 Thumbnail을 y축 방향으로 스케일링하는 값입니다. |

### 반환값

[IImage](../../iimage/) 객체.

## 비고

다음 예제는 PowerPoint [Presentation](../../presentation/)에서 썸네일을 생성하는 방법을 보여줍니다:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```  
다음 예제는 슬라이드를 비트맵으로 변환하고 PNG 형식으로 저장하는 방법을 보여줍니다:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 프레젠테이션의 첫 번째 슬라이드를 Bitmap 객체로 변환합니다
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// 이미지를 PNG 형식으로 저장합니다
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```  
다음 예제는 PowerPoint PPT/PPTX를 JPG로 변환하는 방법을 보여줍니다:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // 전체 크기의 이미지를 생성합니다
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // 이미지를 JPEG 형식으로 디스크에 저장합니다
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```  
다음 예제는 지정된 크기로 PowerPoint PPT/PPTX를 JPG로 변환하는 방법을 보여줍니다:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// 차원 정의
int32_t desiredX = 1200;
int32_t desiredY = 800;
// X와 Y의 스케일된 값 얻기
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // 전체 크기의 이미지를 생성합니다
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // 이미지를 JPEG 형식으로 디스크에 저장합니다
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() 메서드

실제 크기의 20 %인 Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) 메서드

지정된 크기의 Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Image 객체.

## 비고

다음 예제는 C#을 사용하여 사용자 지정 크기로 슬라이드를 이미지로 변환하는 방법을 보여줍니다.  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// 프레젠테이션의 첫 번째 슬라이드를 지정된 크기의 Bitmap으로 변환합니다
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// 이미지를 JPEG 형식으로 저장합니다
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```

## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) 메서드

지정된 매개변수로 Thumbnail tiff 이미지 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff 옵션입니다. |

### 반환값

Image 객체.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) 메서드

Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션입니다. |

### 반환값

Image 객체.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) 메서드

맞춤 스케일링을 적용한 Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션입니다. |
| scaleX | **float** | 이 Thumbnail을 x축 방향으로 스케일링하는 값입니다. |
| scaleY | **float** | 이 Thumbnail을 y축 방향으로 스케일링하는 값입니다. |

### 반환값

Bitmap 객체.

## 비고

다음 예제는 C#을 사용하여 노트와 주석이 포함된 슬라이드를 [Images](../../images/)로 변환하는 방법을 보여줍니다.  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Create the rendering options
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Create notes and comments layouting options
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Sets the position of the notes on the page
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Sets the position of the comments on the page
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Sets the width of the comment output area
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Sets the color for the comments area
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Set layout options for rendering
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Converts the first slide of the presentation to a IImage object
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Saves the image in the GIF format
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) 메서드

지정된 크기의 Thumbnail Image 개체를 반환합니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션입니다. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성할 이미지의 크기입니다. |

### 반환값

Image 객체.

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../iimage/)
* 클래스 [Slide](../)
* 클래스 [Size](../../../system.drawing/size/)
* 클래스 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 클래스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)