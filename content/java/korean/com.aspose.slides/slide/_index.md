---
title: Slide
second_title: Aspose.Slides for Java API 레퍼런스
description: 프레젠테이션의 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/slide/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**All Implemented Interfaces:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

프레젠테이션의 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getThemeManager()](#getThemeManager--) | 오버라이드 테마 관리자를 반환합니다. |
| [getSlideNumber()](#getSlideNumber--) | 슬라이드 번호를 반환합니다. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 슬라이드 번호를 반환합니다. |
| [getHidden()](#getHidden--) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 판단합니다. |
| [setHidden(boolean value)](#setHidden-boolean-) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 판단합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 사용자 지정 스케일링을 적용한 썸네일 이미지 개체를 반환합니다. |
| [getImage()](#getImage--) | 실제 크기의 20%인 썸네일 이미지 개체를 반환합니다. |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 지정된 크기의 썸네일 이미지 개체를 반환합니다. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 지정된 매개변수로 썸네일 TIFF 이미지 개체를 반환합니다. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 썸네일 이미지 개체를 반환합니다. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 사용자 지정 스케일링을 적용한 썸네일 이미지 개체를 반환합니다. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 지정된 크기의 썸네일 이미지 개체를 반환합니다. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 슬라이드 내용을 EMF 파일로 저장합니다. |
| [remove()](#remove--) | 프레젠테이션에서 슬라이드를 제거합니다. |
| [getLayoutSlide()](#getLayoutSlide--) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. |
| [reset()](#reset--) | LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다. |
| [getNotesSlideManager()](#getNotesSlideManager--) | 노트 슬라이드에 접근하고, 추가 및 제거할 수 있습니다. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 허용된 도형의 모든 단락에서 동일한 서식을 가진 실행(run)을 결합합니다. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```


슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**반환:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```


오버라이드 테마 관리자를 반환합니다. 읽기 전용 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**반환:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


슬라이드 번호를 반환합니다. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 컬렉션에서 슬라이드 인덱스는 항상 SlideNumber - Presentation.FirstSlideNumber와 같습니다. 읽기/쓰기 int.

**반환:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


슬라이드 번호를 반환합니다. [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) 컬렉션에서 슬라이드 인덱스는 항상 SlideNumber - Presentation.FirstSlideNumber와 같습니다. 읽기/쓰기 int.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 판단합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 판단합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


사용자 지정 스케일링을 적용한 썸네일 이미지 개체를 반환합니다.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // 첫 번째 슬라이드에 접근합니다
>      ISlide sld = pres.getSlides().get_Item(0);
>      // 전체 크기의 이미지를 생성합니다
>      IImage bmp = sld.getImage(1f, 1f);
>      // 이미지를 JPEG 형식으로 디스크에 저장합니다
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // 프레젠테이션의 첫 번째 슬라이드를 Bitmap 객체로 변환합니다
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // 이미지를 PNG 형식으로 저장합니다
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // 전체 크기의 이미지를 생성합니다
>          IImage bmp = sld.getImage(1f, 1f);
>          // 이미지를 JPEG 형식으로 디스크에 저장합니다
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // 차원 정의
>      int desiredX = 1200;
>      int desiredY = 800;
>      // X와 Y의 스케일 값을 계산합니다
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // 전체 크기의 이미지를 생성합니다
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // 이미지를 JPEG 형식으로 디스크에 저장합니다
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | 이 썸네일을 x축 방향으로 스케일링할 값. |
| scaleY | float | 이 썸네일을 y축 방향으로 스케일링할 값. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - IImage object.
### getImage() {#getImage--}
```
public final IImage getImage()
```


실제 크기의 20%인 썸네일 이미지 개체를 반환합니다.

**반환:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```


지정된 크기의 썸네일 이미지 개체를 반환합니다.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // 첫 번째 슬라이드를 지정된 크기의 Bitmap으로 변환합니다
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // 이미지를 JPEG 형식으로 저장합니다
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 생성할 이미지의 크기. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```


지정된 매개변수로 썸네일 TIFF 이미지 개체를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 옵션. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```


썸네일 이미지 개체를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


사용자 지정 스케일링을 적용한 썸네일 이미지 개체를 반환합니다.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // 렌더링 옵션을 생성합니다
>      IRenderingOptions options = new RenderingOptions();
>      // 노트 및 댓글 레이아웃 옵션을 생성합니다
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // 페이지에서 노트의 위치를 설정합니다
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // 페이지에서 댓글의 위치를 설정합니다
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // 댓글 출력 영역의 너비를 설정합니다
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // 댓글 영역의 색상을 설정합니다
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // 렌더링을 위한 레이아웃 옵션을 설정합니다
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // 프레젠테이션의 첫 번째 슬라이드를 BufferedImage 객체로 변환합니다
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // 이미지를 GIF 형식으로 저장합니다
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| scaleX | float | 이 썸네일을 x축 방향으로 스케일링할 값. |
| scaleY | float | 이 썸네일을 y축 방향으로 스케일링할 값. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```


지정된 크기의 썸네일 이미지 개체를 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| imageSize | java.awt.Dimension | 생성할 이미지의 크기. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```


슬라이드 내용을 SVG 파일로 저장합니다.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // 첫 번째 슬라이드를 SVG 파일로 저장합니다
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```


슬라이드 내용을 SVG 파일로 저장합니다.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // 첫 번째 슬라이드를 SVG 파일로 저장합니다
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 생성 옵션 |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


슬라이드 내용을 EMF 파일로 저장합니다.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // 첫 번째 슬라이드를 메타파일로 저장합니다
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
### remove() {#remove--}
```
public final void remove()
```


프레젠테이션에서 슬라이드를 제거합니다.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```


현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```


현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```


LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```


노트 슬라이드에 접근하고, 추가 및 제거할 수 있습니다. 읽기 전용 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**반환:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```


특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 찾을 주석의 작성자 또는 모든 주석을 반환하려면 null. |

**반환:**
com.aspose.slides.IComment[] - Array of [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


모든 허용된 도형의 모든 단락에서 동일한 서식을 가진 실행(run)을 결합합니다.