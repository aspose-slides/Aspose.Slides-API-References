---
title: IInkBrush
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 트레이스 브러시를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

트레이스 브러시를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getColor()](#getColor--) | 선의 브러시 색상을 가져오거나 설정합니다. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | 선의 브러시 색상을 가져오거나 설정합니다. |
| [getSize()](#getSize--) | 선의 브러시 크기를 포인트 단위로 가져오거나 설정합니다. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | 선의 브러시 크기를 포인트 단위로 가져오거나 설정합니다. |
| [getInkEffect()](#getInkEffect--) | 잉크 획의 시각적 스타일을 정의하는 잉크 효과 유형(e.g., Galaxy, Gold, Silver)을 가져옵니다. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

선의 브러시 색상을 가져오거나 설정합니다.

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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

선의 브러시 색상을 가져오거나 설정합니다.

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
| value | java.lang.Integer |  |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

선의 브러시 크기를 포인트 단위로 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

선의 브러시 크기를 포인트 단위로 가져오거나 설정합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

잉크 획의 시각적 스타일을 정의하는 잉크 효과 유형(e.g., Galaxy, Gold, Silver)을 가져옵니다. 이 값은 브러시 속성 "inkEffects"에서 구문 분석됩니다. 인식된 효과가 지정되지 않으면 [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined)이 반환됩니다.

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

**반환값:**
int