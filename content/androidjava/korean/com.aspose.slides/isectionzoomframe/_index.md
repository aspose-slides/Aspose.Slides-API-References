---
title: ISectionZoomFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드의 Section Zoom 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isectionzoomframe/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

슬라이드의 Section Zoom 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Section Zoom 객체가 연결된 섹션 객체를 가져오거나 설정합니다. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Section Zoom 객체가 연결된 섹션 객체를 가져오거나 설정합니다. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Section Zoom 객체가 연결된 섹션 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Section Zoom 객체가 연결된 섹션 객체를 가져오거나 설정합니다. 읽기/쓰기 [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |