---
title: IBaseSlide
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibaseslide/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

모든 슬라이드 유형에 대한 공통 데이터를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShapes()](#getShapes--) | 슬라이드의 도형을 반환합니다. |
| [getControls()](#getControls--) | 슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다. |
| [getName()](#getName--) | 슬라이드의 이름을 반환하거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 슬라이드의 이름을 반환하거나 설정합니다. |
| [getSlideId()](#getSlideId--) | 슬라이드의 ID를 반환합니다. |
| [getCustomData()](#getCustomData--) | 슬라이드의 사용자 정의 데이터를 반환합니다. |
| [getTimeline()](#getTimeline--) | 애니메이션 타임라인 객체를 반환합니다. |
| [getSlideShowTransition()](#getSlideShowTransition--) | 지정된 슬라이드가 슬라이드 쇼 동안 진행되는 방식을 포함하는 TransitionEx 객체를 반환합니다. |
| [getBackground()](#getBackground--) | 슬라이드의 배경을 반환합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다. |
| [getShowMasterShapes()](#getShowMasterShapes--) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | 마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | 지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 허용된 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | 두 IBaseSlide 인스턴스가 동일한지 판단합니다. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

슬라이드의 도형을 반환합니다. 읽기 전용 [IShapeCollection](../../com.aspose.slides/ishapecollection).

**반환:**  
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

슬라이드의 ActiveX 컨트롤 컬렉션을 반환합니다. 읽기 전용 [IControlCollection](../../com.aspose.slides/icontrolcollection).

**반환:**  
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

슬라이드의 이름을 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

슬라이드의 ID를 반환합니다. 읽기 전용 long.

**반환:**  
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

슬라이드의 사용자 정의 데이터를 반환합니다. 읽기 전용 [ICustomData](../../com.aspose.slides/icustomdata).

**반환:**  
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

애니메이션 타임라인 객체를 반환합니다. 읽기 전용 [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**반환:**  
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

지정된 슬라이드가 슬라이드 쇼 동안 진행되는 방식을 포함하는 TransitionEx 객체를 반환합니다. 읽기 전용 [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**반환:**  
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

슬라이드의 배경을 반환합니다. 읽기 전용 [IBackground](../../com.aspose.slides/ibackground).

**반환:**  
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

포함된 하이퍼링크에 대한 쉬운 액세스를 제공합니다. 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체에서는 이 속성이 항상 false를 반환합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

마스터 슬라이드의 도형을 슬라이드에 표시할지 여부를 지정합니다. 마스터 슬라이드 자체에서는 이 속성이 항상 false를 반환합니다. 읽기/쓰기 boolean.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

지정된 대체 텍스트를 가진 도형의 첫 번째 발생을 찾습니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| altText | java.lang.String | 대체 텍스트. |

**반환:**  
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

모든 허용된 도형의 모든 단락에서 동일한 서식의 실행을 결합합니다.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

두 IBaseSlide 인스턴스가 동일한지 판단합니다. 반환값은 슬라이드의 구조와 정적 콘텐츠를 기반으로 계산됩니다. 모든 도형, 스타일, 텍스트, 애니메이션 및 기타 설정 등이 동일하면 두 슬라이드는 동일합니다. 비교에서는 고유 식별자 값(예: SlideId)과 동적 콘텐츠(예: 날짜 자리표시자의 현재 날짜 값)는 고려되지 않습니다.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 현재 IBaseSlide와 비교할 IBaseSlide. |

**반환:**  
boolean - **true** 지정된 IBaseSlide가 현재 IBaseSlide와 동일하면; 그렇지 않으면 **false**.