---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: 공통 슬라이드 보기 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

공통 슬라이드 보기 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getScale()](#getScale--) | 백분율로 보기 스케일 비율을 지정합니다. |
| [setScale(int value)](#setScale-int-) | 백분율로 보기 스케일 비율을 지정합니다. |
| [getVariableScale()](#getVariableScale--) | 보기 콘텐츠가 현재 창 크기에 가장 잘 맞도록 자동으로 스케일링되도록 지정합니다. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | 보기 콘텐츠가 현재 창 크기에 가장 잘 맞도록 자동으로 스케일링되도록 지정합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 그리기 가이드 컬렉션을 반환합니다. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

백분율로 보기 스케일 비율을 지정합니다. 읽기/쓰기 int.

**반환:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

백분율로 보기 스케일 비율을 지정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

보기 콘텐츠가 현재 창 크기에 가장 잘 맞도록 자동으로 스케일링되도록 지정합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

보기 콘텐츠가 현재 창 크기에 가장 잘 맞도록 자동으로 스케일링되도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

그리기 가이드 컬렉션을 반환합니다. 읽기 전용 [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // 슬라이드 중앙 오른쪽에 새로운 수직 그리기 가이드를 추가합니다
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // 슬라이드 중앙 아래에 새로운 수평 그리기 가이드를 추가합니다
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)