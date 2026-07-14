---
title: ZoomObject
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 슬라이드에서 Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/zoomobject/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**모든 구현된 인터페이스:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

슬라이드의 Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getImageType()](#getImageType--) | Zoom 객체의 이미지 유형을 가져오거나 설정합니다. |
| [setImageType(int value)](#setImageType-int-) | Zoom 객체의 이미지 유형을 가져오거나 설정합니다. |
| [getReturnToParent()](#getReturnToParent--) | 슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | 슬라이드쇼에서 탐색 동작을 가져오거나 설정합니다. |
| [getShowBackground()](#getShowBackground--) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. |
| [getZoomImage()](#getZoomImage--) | Zoom 객체의 이미지를 가져오거나 설정합니다. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Zoom 객체의 이미지를 가져오거나 설정합니다. |
| [getTransitionDuration()](#getTransitionDuration--) | Zoom과 슬라이드 사이 전환의 지속 시간을 가져오거나 설정합니다. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Zoom과 슬라이드 사이 전환의 지속 시간을 가져오거나 설정합니다. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```


Zoom 객체의 이미지 유형을 가져오거나 설정합니다. 읽기/쓰기 [ZoomImageType](../../com.aspose.slides/zoomimagetype). 기본값: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Zoom 객체가 슬라이드 미리보기 또는 표지 이미지를 사용하는지 지정합니다.

**반환값:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```


Zoom 객체의 이미지 유형을 가져오거나 설정합니다. 읽기/쓰기 [ZoomImageType](../../com.aspose.slides/zoomimagetype). 기본값: Preview

--------------------

> ```
> Next example demonstrates changing Image Type to Preview value. 
>  In this case current image of a Zoom object changes to slide image:
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

Zoom 객체가 슬라이드 미리보기 또는 표지 이미지를 사용하는지 지정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
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
public final void setReturnToParent(boolean value)
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```


Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
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
public final void setShowBackground(boolean value)
```


Zoom이 대상 슬라이드의 배경을 사용할지 여부를 지정하는 값을 가져오거나 설정합니다. 읽기/쓰기 boolean. 기본값: true

--------------------

> ```
> the example demonstrates removing the background of an image of a Zoom object:
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```


Zoom 객체의 이미지를 가져오거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
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
public final void setZoomImage(IPPImage value)
```


Zoom 객체의 이미지를 가져오거나 설정합니다. 읽기/쓰기 [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> the example demonstrates changing an image of a Zoom object:
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```


Zoom과 슬라이드 사이 전환의 지속 시간을 가져오거나 설정합니다. 읽기/쓰기 float. 기본값: 1.0f

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

--------------------

지정되지 않은 경우 (TransitionDur = 0), 대상 슬라이드 전환과 해당 전환에 연결된 타이밍을 사용합니다.

**반환값:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```


Zoom과 슬라이드 사이 전환의 지속 시간을 가져오거나 설정합니다. 읽기/쓰기 float. 기본값: 1.0f

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

--------------------

지정되지 않은 경우 (TransitionDur = 0), 대상 슬라이드 전환과 해당 전환에 연결된 타이밍을 사용합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |