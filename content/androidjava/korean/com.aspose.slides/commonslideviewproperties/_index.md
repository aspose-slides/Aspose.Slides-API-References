---
title: CommonSlideViewProperties
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 공통 슬라이드 뷰 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/commonslideviewproperties/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

공통 슬라이드 뷰 속성을 나타냅니다.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // 프레젠테이션 파일을 나타내는 Presentation 객체를 인스턴스화합니다.
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // 프레젠테이션의 뷰 속성을 설정합니다.
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // 슬라이드 뷰의 확대 비율(백분율) 값
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // 노트 뷰의 확대 비율(백분율) 값
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getScale()](#getScale--) | 백분율로 뷰 스케일 비율을 지정합니다. |
| [setScale(int value)](#setScale-int-) | 백분율로 뷰 스케일 비율을 지정합니다. |
| [getVariableScale()](#getVariableScale--) | 뷰 콘텐츠가 현재 창 크기에 최적 맞춤되도록 자동으로 스케일링되도록 지정합니다. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | 뷰 콘텐츠가 현재 창 크기에 최적 맞춤되도록 자동으로 스케일링되도록 지정합니다. |
| [getDrawingGuides()](#getDrawingGuides--) | 그리기 가이드 컬렉션을 반환합니다. |
### getScale() {#getScale--}
```
public final int getScale()
```


백분율로 뷰 스케일 비율을 지정합니다. 읽기/쓰기 int.

**반환값:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


백분율로 뷰 스케일 비율을 지정합니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```


뷰 콘텐츠가 현재 창 크기에 최적 맞춤되도록 자동으로 스케일링되도록 지정합니다. 읽기/쓰기 boolean.

**반환값:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```


뷰 콘텐츠가 현재 창 크기에 최적 맞춤되도록 자동으로 스케일링되도록 지정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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
>      // 새로운 수직 그리기 가이드를 슬라이드 중앙 오른쪽에 추가합니다
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // 새로운 수평 그리기 가이드를 슬라이드 중앙 아래에 추가합니다
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)