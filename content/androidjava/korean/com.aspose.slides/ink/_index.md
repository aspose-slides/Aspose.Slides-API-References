---
title: Ink
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 슬라이드에 있는 잉크 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ink/
---
**상속:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

슬라이드에 있는 잉크 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTraces()](#getTraces--) | IInk 요소 [IInkTrace](../../com.aspose.slides/iinktrace)에 포함된 모든 트레이스를 가져옵니다. |
| [getInkEffectImages()](#getInkEffectImages--) | 잉크 브러시의 시각 효과를 시뮬레이션하는 데 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

IInk 요소 [IInkTrace](../../com.aspose.slides/iinktrace)에 포함된 모든 트레이스를 가져옵니다. 읽기 전용.

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
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

잉크 브러시의 시각 효과를 시뮬레이션하는 데 사용되는 사용자 정의 이미지 컬렉션을 가져옵니다. 이러한 이미지는 특정 [InkEffectType](../../com.aspose.slides/inkeffecttype) 값(예: Galaxy, Rainbow 등)으로 잉크를 렌더링할 때 사용됩니다. 자체 이미지를 제공하면 각 잉크 효과가 표시되는 방식을 제어할 수 있습니다.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

이 속성은 기본 잉크 효과 텍스처를 사용자 정의 텍스처로 교체할 수 있게 하며, 기본 자산이 라이선스로 제한되거나 런타임에 사용할 수 없을 때 특히 유용합니다. 사전의 각 항목은 [InkEffectType](../../com.aspose.slides/inkeffecttype) 값을 해당 [IImage](../../com.aspose.slides/iimage) 객체(예: Bitmap 또는 Aspose 이미지 인터페이스)와 연결해야 합니다.

**반환값:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>