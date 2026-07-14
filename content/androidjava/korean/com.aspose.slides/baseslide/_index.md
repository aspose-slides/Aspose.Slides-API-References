---
title: BaseSlide
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/baseslide/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapes()](#getShapes--) | 슬라이드의 모양을 반환합니다. |
| [getControls()](#getControls--) | 슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다. |
| [getName()](#getName--) | 슬라이드의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 슬라이드의 이름을 반환하거나 설정합니다. |
| [getSlideId()](#getSlideId--) | 슬라이드의 ID를 반환합니다. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 두 IBaseSlide 인스턴스가 같은지 여부를 결정합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 허용된 모양의 모든 단락에서 동일한 서식을 가진 실행을 결합합니다. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | 모든 허용된 모양의 모든 단락에서 동일한 서식을 가진 실행을 결합합니다. |
| [createThemeEffective()](#createThemeEffective--) | 이 슬라이드에 대한 유효 테마를 반환합니다. |
| [getCustomData()](#getCustomData--) | 슬라이드의 사용자 정의 데이터를 반환합니다. |
| [getTimeline()](#getTimeline--) | 애니메이션 타임라인 객체를 반환합니다. |
| [getSlideShowTransition()](#getSlideShowTransition--) | 슬라이드 쇼 중에 지정된 슬라이드가 진행되는 방식에 대한 정보를 포함하는 Transition 객체를 반환합니다. |
| [getBackground()](#getBackground--) | 슬라이드의 배경을 반환합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 모양을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 모양을 슬라이드에 표시할지 여부를 지정합니다. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 지정된 대체 텍스트를 가진 모양의 첫 번째 발생을 찾습니다. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | IPresentation 인터페이스를 반환합니다. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

슬라이드의 모양을 반환합니다. 읽기 전용 [IShapeCollection](../../com.aspose.slides/ishapecollection).

**반환:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

슬라이드에 있는 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [IControlCollection](../../com.aspose.slides/icontrolcollection).

**반환:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

슬라이드의 ID를 반환합니다. 읽기 전용 long.

**반환:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

두 IBaseSlide 인스턴스가 동일한지 여부를 결정합니다. 반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 모양, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드가 동일합니다. 비교에서는 고유 식별자 값(예: SlideId) 및 동적 콘텐츠(예: 날짜 자리표시자의 현재 날짜 값)는 고려되지 않습니다.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 현재 IBaseSlide와 비교할 IBaseSlide. |

**반환:**
boolean -  **true**  if the specified IBaseSlide is equal to the current IBaseSlide; otherwise,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

모든 허용된 모양의 모든 단락에서 동일한 서식을 가진 실행을 결합합니다.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

모든 허용된 모양의 모든 단락에서 동일한 서식을 가진 실행을 결합합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

이 슬라이드에 대한 유효 테마를 반환합니다.

**반환:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

슬라이드의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**반환:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

슬라이드 쇼 중에 지정된 슬라이드가 진행되는 방식에 대한 정보를 포함하는 Transition 객체를 반환합니다. 읽기 전용 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**반환:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

슬라이드의 배경을 반환합니다. 읽기 전용 [IBackground](../../com.aspose.slides/ibackground).

**반환:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다. 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

마스터 슬라이드의 모양을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean.

**반환:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

마스터 슬라이드의 모양을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체의 경우 이 속성은 항상 false를 반환합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

지정된 대체 텍스트를 가진 모양의 첫 번째 발생을 찾습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| altText | java.lang.String | 대체 텍스트. |

**반환:**
[IShape](../../com.aspose.slides/ishape) - Shape object 또는 null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

IPresentation 인터페이스를 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

기본 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)