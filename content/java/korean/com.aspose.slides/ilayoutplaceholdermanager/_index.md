---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Reference
description: Represents manager that allows you to add placeholders to the layout slide.
type: docs
url: /ko/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

레이아웃 슬라이드에 자리 표시자를 추가할 수 있는 관리자를 나타냅니다.
## Methods

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 내용(그림, 표, 미디어 또는 텍스트 등)을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 내용(그림, 표, 미디어 또는 텍스트 등)을 수직 방향으로 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 텍스트 내용을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 텍스트 내용을 수직 방향으로 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 그림을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 차트를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 표를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 SmartArt 다이어그램을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 미디어 개체를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 온라인 이미지를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 내용(그림, 표, 미디어 또는 텍스트 등)을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Content 자리 표시자로 생성했습니다.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 내용(그림, 표, 미디어 또는 텍스트 등)을 수직 방향으로 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Content (Vertical) 자리 표시자로 생성했습니다.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 텍스트 내용을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Text 자리 표시자로 생성했습니다.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 텍스트 내용을 수직 방향으로 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Text (Vertical) 자리 표시자로 생성했습니다.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 그림을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> 다음 예제는 레이아웃 슬라이드에 Picture 자리 표시자 모양을 추가하는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Picture 자리 표시자로 생성했습니다.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 차트를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Chart 자리 표시자로 생성했습니다.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 표를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Table 자리 표시자로 생성했습니다.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 SmartArt 다이어그램을 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 SmartArt 자리 표시자로 생성했습니다.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 미디어 개체를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> 다음 예제는 레이아웃 슬라이드에 Media 자리 표시자 모양을 추가하는 방법을 보여줍니다.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Media 자리 표시자로 생성했습니다.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 온라인 이미지를 보관하기 위한 새로운 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개 변수:**
| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환값:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape)를 Online Image 자리 표시자로 생성했습니다.