---
title: IZoomObject
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 슬라이드에서 Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/izoomobject/
---
**구현된 모든 인터페이스:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

슬라이드에서 Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImageType()](#getImageType--) | 줌 객체의 이미지 유형을 가져오거나 설정합니다. |
| [setImageType(int value)](#setImageType-int-) | 줌 객체의 이미지 유형을 가져오거나 설정합니다. |
| [getReturnToParent()](#getReturnToParent--) | 슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. |
| [getShowBackground()](#getShowBackground--) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. |
| [getZoomImage()](#getZoomImage--) | 줌 객체의 이미지를 가져오거나 설정합니다. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | 줌 객체의 이미지를 가져오거나 설정합니다. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

줌 객체의 이미지 유형을 가져오거나 설정합니다. 읽기/쓰기 [ZoomImageType](../../com.aspose.slides/zoomimagetype). 기본값: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom 객체가 슬라이드 미리보기 또는 커버 이미지를 사용하고 있는지 여부를 지정합니다.

**반환값:**
int
### setImageType(int value) {#setImageType-int-}
```
public abstract void setImageType(int value)
```

줌 객체의 이미지 유형을 가져오거나 설정합니다. 읽기/쓰기 [ZoomImageType](../../com.aspose.slides/zoomimagetype). 기본값: Preview

--------------------

> ```
> This example demonstrates changing Image Type to Preview value. 
>  In this case the current image of a Zoom object changes to slide image:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Zoom 객체가 슬라이드 미리보기 또는 커버 이미지를 사용하고 있는지 여부를 지정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public abstract boolean getReturnToParent()
```

슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

속성의 true 값은 슬라이드쇼에서 상위 반환 탐색 동작을 지정합니다.

**반환값:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

속성의 true 값은 슬라이드쇼에서 상위 반환 탐색 동작을 지정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public abstract void setShowBackground(boolean value)
```

Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: true

--------------------

> ```
> The example demonstrates removing the background of an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public abstract IPPImage getZoomImage()
```

줌 객체의 이미지를 가져오거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> The example demonstrates changing an image of a Zoom object:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public abstract void setZoomImage(IPPImage value)
```

줌 객체의 이미지를 가져오거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> 예제는 Zoom 객체의 이미지를 변경하는 방법을 보여줍니다:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public abstract float getTransitionDuration()
```

Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다. 읽기/쓰기 float. 기본값: 1.0f

--------------------

> ```
> 이 예제는 Zoom과 슬라이드 사이 전환 지속 시간을 변경하는 방법을 보여줍니다:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


지정되지 않은 경우 (TransitionDur = 0), 대상 슬라이드 전환 및 해당 전환에 연결된 타이밍을 사용합니다.

**반환값:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Zoom과 슬라이드 사이 전환 지속 시간을 가져오거나 설정합니다. 읽기/쓰기 float. 기본값: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

지정되지 않은 경우 (TransitionDur = 0), 대상 슬라이드 전환 및 해당 전환에 연결된 타이밍을 사용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | float |  |