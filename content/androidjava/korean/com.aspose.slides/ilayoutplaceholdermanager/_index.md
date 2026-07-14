---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: 레이아웃 슬라이드에 자리 표시자를 추가할 수 있는 관리자를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

레이아웃 슬라이드에 자리 표시자를 추가할 수 있는 관리자를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보유할 수 있는 새 자리 표시자 모양을 추가합니다. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | 레이아웃 슬라이드에 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 수직 방향으로 보유할 수 있는 새 자리 표시자 모양을 추가합니다. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | 텍스트 콘텐츠를 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | 텍스트 콘텐츠를 수직 방향으로 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | 그림을 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | 차트를 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | 표를 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | SmartArt 다이어그램을 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | 미디어 개체를 보유하는 새 자리 표시자 모양을 추가합니다. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | 온라인 이미지를 보유하는 새 자리 표시자 모양을 추가합니다. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 보유할 수 있는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 콘텐츠 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


레이아웃 슬라이드에 그림, 표, 미디어 또는 텍스트와 같은 콘텐츠를 수직 방향으로 보유할 수 있는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 수직 콘텐츠 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


텍스트 콘텐츠를 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 텍스트 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


텍스트 콘텐츠를 수직 방향으로 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 수직 텍스트 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


그림을 보유하는 새 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 그림 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


차트를 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 차트 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


표를 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 표 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


SmartArt 다이어그램을 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - SmartArt 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


미디어 개체를 보유하는 새 자리 표시자 모양을 추가합니다.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 미디어 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


온라인 이미지를 보유하는 새 자리 표시자 모양을 추가합니다.

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

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | float | 새 자리 표시자 모양의 X 좌표입니다. |
| y | float | 새 자리 표시자 모양의 Y 좌표입니다. |
| width | float | 새 자리 표시자 모양의 너비입니다. |
| height | float | 새 자리 표시자 모양의 높이입니다. |

**반환:**
[IAutoShape](../../com.aspose.slides/iautoshape) - 온라인 이미지 자리 표시자가 포함된 [IAutoShape](../../com.aspose.slides/iautoshape)를 생성했습니다.