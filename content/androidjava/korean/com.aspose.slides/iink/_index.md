---
title: IInk
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 잉크 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iink/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

슬라이드에 있는 잉크 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTraces()](#getTraces--) | IInk 요소에 포함된 모든 트레이스를 가져옵니다 [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

IInk 요소에 포함된 모든 트레이스를 가져옵니다 [IInkTrace](../../com.aspose.slides/iinktrace). 읽기 전용.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
com.aspose.slides.IInkTrace[]