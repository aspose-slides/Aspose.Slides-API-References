---
title: IInkBrush
second_title: Aspose.Slides for Java API 레퍼런스
description: 흔적 브러시를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

흔적 브러시를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor()](#getColor--) | 선에 대한 브러시 색상을 가져오거나 설정합니다. |
| [setColor(Color value)](#setColor-java.awt.Color-) | 선에 대한 브러시 색상을 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 포인트 단위로 선의 브러시 크기를 가져오거나 설정합니다. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | 포인트 단위로 선의 브러시 크기를 가져오거나 설정합니다. |
| [getInkEffect()](#getInkEffect--) | 잉크 스트로크의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


선에 대한 브러시 색상을 가져오거나 설정합니다.

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

**반환:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


선에 대한 브러시 색상을 가져오거나 설정합니다.

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
public abstract Dimension2D getSize()
```


포인트 단위로 선의 브러시 크기를 가져오거나 설정합니다.

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

**반환:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


포인트 단위로 선의 브러시 크기를 가져오거나 설정합니다.

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
public abstract int getInkEffect()
```


잉크 스트로크의 시각적 스타일을 정의하는 잉크 효과 유형(예: Galaxy, Gold, Silver)을 가져옵니다. 브러시 속성 "inkEffects"에서 값이 구문 분석됩니다. 인식된 효과가 지정되지 않으면 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)가 반환됩니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환:**
int