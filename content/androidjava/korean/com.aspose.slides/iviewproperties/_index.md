---
title: IViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation wide view properties.
type: docs
url: /ko/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

프레젠테이션 전체 보기 속성.
## 메서드

| Method | Description |
| --- | --- |
| [getLastView()](#getLastView--) | 프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. |
| [setLastView(int value)](#setLastView-int-) | 프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. |
| [getShowComments()](#getShowComments--) | 슬라이드 주석을 표시할지 여부를 지정합니다. |
| [setShowComments(byte value)](#setShowComments-byte-) | 슬라이드 주석을 표시할지 여부를 지정합니다. |
| [getSlideViewProperties()](#getSlideViewProperties--) | 슬라이드 보기 모드와 연관된 일반 보기 속성을 지정합니다. |
| [getNotesViewProperties()](#getNotesViewProperties--) | 노트 보기 모드와 연관된 일반 보기 속성을 지정합니다. |
| [getNormalViewProperties()](#getNormalViewProperties--) | 일반 보기 속성을 나타냅니다. |
| [getGridSpacing()](#getGridSpacing--) | 프레젠테이션 문서의 기본 그리드에 사용할 그리드 간격을 포인트 단위로 반환하거나 설정합니다. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | 프레젠테이션 문서의 기본 그리드에 사용할 그리드 간격을 포인트 단위로 반환하거나 설정합니다. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. 읽기/쓰기 [ViewType](../../com.aspose.slides/viewtype).

**반환값:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

프레젠테이션 문서가 마지막으로 저장될 때 사용된 보기 모드를 지정합니다. 읽기/쓰기 [ViewType](../../com.aspose.slides/viewtype).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

슬라이드 주석을 표시할지 여부를 지정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**반환값:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

슬라이드 주석을 표시할지 여부를 지정합니다. 읽기/쓰기 [NullableBool](../../com.aspose.slides/nullablebool).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

슬라이드 보기 모드와 연관된 일반 보기 속성을 지정합니다. 읽기 전용 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**반환값:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

노트 보기 모드와 연관된 일반 보기 속성을 지정합니다. 읽기 전용 [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**반환값:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

일반 보기 속성을 나타냅니다. 일반 보기는 세 개의 콘텐츠 영역으로 구성됩니다: 슬라이드 자체, 측면 콘텐츠 영역, 그리고 하단 콘텐츠 영역. 읽기 전용 [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**반환값:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

프레젠테이션 문서의 기본 그리드에 사용할 그리드 간격을 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm(2.8349607 포인트)에서 2 인치(144 포인트)까지입니다.

**반환값:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

프레젠테이션 문서의 기본 그리드에 사용할 그리드 간격을 포인트 단위로 반환하거나 설정합니다. 읽기/쓰기 float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

그리드 간격 값은 양수여야 합니다. 일반적인 값 범위는 1 mm(2.8349607 포인트)에서 2 인치(144 포인트)까지입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | float |  |