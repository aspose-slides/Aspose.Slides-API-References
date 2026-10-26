---
title: InkBrush
second_title: Aspose.Slides for Java API 레퍼런스
description: inkBrush 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/inkbrush/
---
**상속:**  
java.lang.Object

**구현된 모든 인터페이스:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

inkBrush 개체를 나타냅니다.

## 메서드

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | 라인의 브러시 색상을 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-java.awt.Color-) | 라인의 브러시 색상을 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 라인의 브러시 크기를 포인트 단위로 가져오거나 설정합니다. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 라인의 브러시 크기를 포인트 단위로 가져오거나 설정합니다. |
| [getInkEffect()](#getInkEffect--) | 잉크 획의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. |

### getColor() {#getColor--}
```
public final Color getColor()
```

라인의 브러시 색상을 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**  
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

라인의 브러시 색상을 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

라인의 브러시 크기를 포인트 단위로 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

라인의 브러시 크기를 포인트 단위로 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

잉크 획의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. 값은 브러시 속성 "inkEffects"에서 구문 분석됩니다. 인식된 효과가 지정되지 않은 경우 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)이(가) 반환됩니다.

**반환값:**  
int